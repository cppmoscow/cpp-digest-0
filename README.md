# cpp-digest-0

Название: C++ Дайджест №0

Дата: 24 июля 2023 – 6 августа 2023

## Новости и релизы

* [vcpkg 2023.06.20, 2023.07.21](https://devblogs.microsoft.com/cppblog/vcpkg-2023-06-20-and-2023-07-21-releases-github-dependency-graph-support-android-tested-triplets-xbox-triplet-improvements-and-more/) — Добавление поддержки интеграции с [GitHub dependency graph](https://docs.github.com/en/code-security/supply-chain-security/understanding-your-software-supply-chain/about-the-dependency-graph), улучшение поддержки Xbox, и другие улучшения и багфиксы.

## Статьи

1. Andreas Fertig: [A strongly typed bool](https://andreasfertig.blog/2023/08/a-strongly-typed-bool/) — Практический пример использования одного из популярных паттернов программирования, _strong types_, для улучшения читабельности кода и предохранения от ошибок.
2. Bartlomiej Filipek: [Understanding Ranges Views and View Adaptors Objects in C++20/C++23](https://www.cppstories.com/2023/cpp20-understanding-views-impl/) — О различиях между _views_ и _view adaptors objects_ в C++20 и C++23, с рассмотрением их реалзиации в [MSVC's STL](https://github.com/microsoft/STL).
3. Jonathan Boccara: [Usage First, Implementation After: A Principle of Software Development](https://www.fluentcpp.com/2022/06/25/usage-first-implementation-after-a-principle-of-software-development/) — О подходе к разработке через ~~тестирование~~ использование, и какие преимущества он может дать.
4. Jonathan Müller: [Should we stop writing functions?](https://www.foonathan.net/2023/08/stop-writing-functions/#content) — Обзор недостатков функций и преимуществ лямбд: может, функции нам больше и не нужны?
5. Rainer Grimm: [C++23: Syntactic Sugar with Deducing This](https://www.modernescpp.com/index.php/c23-syntactic-sugar-with-deducing-this/) — О том, как [Deducing this](https://habr.com/ru/articles/722668/), нововведение C++23, устраняет необходимость в использовании [Curiously Recurring Template Pattern](https://en.cppreference.com/w/cpp/language/crtp).
6. Rainer Grimm: [C++23: The Small Pearls in the Core Language](https://www.modernescpp.com/index.php/c23-the-small-pearls-in-the-core-language/) — О небольших, но полезных нововведениях в C++23, таких как _literal suffixes_, _if consteval_ и _auto(x)_.
7. Raymond Chen: [Perfect forwarding forwards objects, not braced things that are trying to become objects](https://devblogs.microsoft.com/oldnewthing/20230727-00/?p=108494) — Заметка об особенностях работы _perfect forwarding_.
8. Raymond Chen: [Inside STL: The pair and the compressed pair](https://devblogs.microsoft.com/oldnewthing/20230801-00/?p=108509), [Inside STL: The vector](https://devblogs.microsoft.com/oldnewthing/20230802-00/?p=108524), [Inside STL: The string](https://devblogs.microsoft.com/oldnewthing/20230803-00/?p=108532), [Inside STL: The lists](https://devblogs.microsoft.com/oldnewthing/20230804-00/?p=108547) — Серия статей, рассматривающая особенности реализации популярных классов стандартной библиотеки в ее реализациях от _clang_, _gcc_ и _msvc_.
