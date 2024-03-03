# db-course

### Домашнее задание 0 
- DragonFly – AP, обеспечивает лишь eventually consistency
- ScyllaDB – AP, однако это система с tunable consistency, настраивая consistency_level (`All`, `Quorum`, `One`) можно с большей гарантирией получать консистентные данные, жертвуя latency

- ArenaDataDB - CP, судя по описанию схемы обработки в GreenPlum (на основе которого судя по всему сделана ArenaDataDB), однако нормальной информации о самом ArenaDataDB очень мало
