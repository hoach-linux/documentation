---
sidebar_position: 4
---

# Нейминг

У разных разработчиков разный опыт и контекст, что может привести к недопониманию в команде, когда одни и те же сущности называются по-разному. Например:

- Компоненты для отображения могут называться "ui", "components", "ui-kit", "views", …
- Код, который повторно используется во всем приложении, может называться "core", "shared", "app", …
- Код бизнес-логики может называться "store", "model", "state", …

## Нейминг в Feature-Sliced Design {#naming-in-fsd}

В методологии используются такие специфические термины, как:

- "app", "process", "page", "feature", "entity", "shared" как имена слоев,
- "ui', "model", "lib", "api", "config" как имена сегментов.

Очень важно придерживаться этих терминов, чтобы предотвратить путаницу среди членов команды и новых разработчиков, присоединяющихся к проекту. Использование стандартных названий также помогает при обращении за помощью к сообществу.

## Конфликты нейминга {#when-can-naming-interfere}

Конфликты нейминга могут возникать, когда термины, используемые в методологии FSD, пересекаются с терминами, используемыми в бизнесе:

- `FSD#process` vs моделируемый процесс в приложении,
- `FSD#page` vs страница журнала,
- `FSD#model` vs модель автомобиля.

Например, разработчик, увидев в коде слово "процесс", потратит лишнее время, пытаясь понять, какой процесс подразумевается. Такие **коллизии могут нарушить процесс разработки**.

Когда глоссарий проекта содержит терминологию, характерную для FSD, крайне важно проявлять осторожность при обсуждении этих терминов с командой и техническими незаинтересованными сторонами.

Чтобы эффективно общаться с командой, рекомендуется использовать аббревиатуру "FSD" для префиксации терминов методологии. Например, когда речь идет о процессе, можно сказать: "Мы можем поместить этот процесс на на слой FSD features".

И наоборот, при общении с нетехническими заинтересованными сторонами лучше ограничить использование терминологии FSD и воздержаться от упоминания внутренней структуры кодовой базы.

## См. также {#see-also}

- [(Обсуждение) Адаптивность нейминга][disc-src]
- [(Обсуждение) Опрос по неймингу сущностей][disc-naming]
- [(Обсуждение) "processes" vs "flows" vs ...][disc-processes]
- [(Обсуждение) "model" vs "store" vs ...][disc-model]

[disc-model]: https://github.com/feature-sliced/documentation/discussions/68
[disc-naming]: https://github.com/feature-sliced/documentation/discussions/31#discussioncomment-464894
[disc-processes]: https://github.com/feature-sliced/documentation/discussions/20
[disc-src]: https://github.com/feature-sliced/documentation/discussions/16
