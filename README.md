# cpp-digest-0

Название: C++ Дайджест №0

Дата: 24 июля 2023 – 6 августа 2023

## Аннотация

Привет, Хабр! Сегодня я хочу вам представить подборку интересных новостей и материалов из мира C++.

Это пилотный выпуск, так что любые советы, отзывы и рекомендации, как сделать наш дайджест лучше, в комментариях к статье или же напрямую мне в личные сообщения (habr, tg), приветствуются!

Приятного чтения!

## ⚡️️ Новости и релизы

* [vcpkg 2023.06.20, 2023.07.21](https://devblogs.microsoft.com/cppblog/vcpkg-2023-06-20-and-2023-07-21-releases-github-dependency-graph-support-android-tested-triplets-xbox-triplet-improvements-and-more/) — Добавление поддержки интеграции с [GitHub dependency graph](https://docs.github.com/en/code-security/supply-chain-security/understanding-your-software-supply-chain/about-the-dependency-graph), улучшение поддержки Xbox, и другие улучшения и багфиксы.
* [CLion 2023.2](https://blog.jetbrains.com/clion/2023/07/clion-2023-2-released/) — Обновление встроенных дебаггеров, улучшение интеграции с PlatformIO, добавление AI Assistant и многое другое.
* [ReSharper C++ 2023.2](https://blog.jetbrains.com/rscpp/2023/08/02/resharper-cpp-2023-2/) — Добавление AI Assistant, поддержки C++20 и C++23, операции безопасного удаления, улучшенная поддержка Unreal Engine Blueprints и другое.
* [Dear ImGui 1.89.8](https://github.com/ocornut/imgui/releases/tag/v1.89.8) — Небольшие изменения, багфиксы и новые демонстрационные примеры программ.
* [Godot 4.2 dev 2](https://godotengine.org/article/dev-snapshot-godot-4-2-dev-2/) — Добавление поддержки [OpenXR API](https://registry.khronos.org/OpenXR/specs/1.0/man/html/openxr.html), отладки мультипоточного кода в дебаггере скриптов, багфиксы и прочее.
* [GCC 13.2](https://gcc.gnu.org/gcc-13/) — Багфиксы и устранение регрессий относительно прошлых релизов.
* [mold 2.0.0](https://github.com/rui314/mold/releases/tag/v2.0.0) — Изменение лицензии с APGL на MIT и другие изменения.

## 📝 Статьи

1. 🇷🇺 Habr: [Базовые алгоритмы на графах](https://habr.com/ru/companies/timeweb/articles/751762/) — Обзор самых популярных графовых алгоритмов с рассмотрением их реализации на C++.
2. 🇷🇺 Habr: [Дизайн API в С++](https://habr.com/ru/articles/752420/) — О правилах проектирования хороших API с рассмотрением множества примеров их практического применения.
3. Andreas Fertig: [A strongly typed bool](https://andreasfertig.blog/2023/08/a-strongly-typed-bool/) — Практический пример использования одного из популярных паттернов программирования, _strong types_, для улучшения читабельности кода и предохранения от ошибок.
4. Bartlomiej Filipek: [Understanding Ranges Views and View Adaptors Objects in C++20/C++23](https://www.cppstories.com/2023/cpp20-understanding-views-impl/) — О различиях между _views_ и _view adaptors objects_ в C++20 и C++23, с рассмотрением их реалзиации в [MSVC's STL](https://github.com/microsoft/STL).
5. Jonathan Boccara: [Usage First, Implementation After: A Principle of Software Development](https://www.fluentcpp.com/2022/06/25/usage-first-implementation-after-a-principle-of-software-development/) — О подходе к разработке через ~~тестирование~~ использование, и какие преимущества он может дать.
6. Jonathan Müller: [Should we stop writing functions?](https://www.foonathan.net/2023/08/stop-writing-functions/#content) — Обзор недостатков функций и преимуществ лямбд: может, функции нам больше и не нужны?
7. Rainer Grimm: [C++23: Syntactic Sugar with Deducing This](https://www.modernescpp.com/index.php/c23-syntactic-sugar-with-deducing-this/) — О том, как [Deducing this](https://habr.com/ru/articles/722668/), нововведение C++23, устраняет необходимость в использовании [Curiously Recurring Template Pattern](https://en.cppreference.com/w/cpp/language/crtp).
8. Rainer Grimm: [C++23: The Small Pearls in the Core Language](https://www.modernescpp.com/index.php/c23-the-small-pearls-in-the-core-language/) — О небольших, но полезных нововведениях в C++23, таких как _literal suffixes_, _if consteval_ и _auto(x)_.
9. Raymond Chen: [Perfect forwarding forwards objects, not braced things that are trying to become objects](https://devblogs.microsoft.com/oldnewthing/20230727-00/?p=108494) — Заметка об особенностях работы _perfect forwarding_.
10. Raymond Chen: [Inside STL: The pair and the compressed pair](https://devblogs.microsoft.com/oldnewthing/20230801-00/?p=108509), [Inside STL: The vector](https://devblogs.microsoft.com/oldnewthing/20230802-00/?p=108524), [Inside STL: The string](https://devblogs.microsoft.com/oldnewthing/20230803-00/?p=108532), [Inside STL: The lists](https://devblogs.microsoft.com/oldnewthing/20230804-00/?p=108547) — Серия статей, рассматривающая особенности реализации популярных классов стандартной библиотеки в ее реализациях от _clang_, _gcc_ и _msvc_.
11. Sandor Dargo: [C++23: static operator() and static operator[]](https://www.sandordargo.com/blog/2023/07/26/cpp23-static-call-and-subscript-operator) — Обзор двух нововведений C++23, статических _operator()_ и _operator[]_.
12. Izzy Muerte: [Everything You Never Wanted to Know About CMake](https://izzys.casa/2023/06/everything-you-never-wanted-to-know-about-cmake-redux/) — О ловушках и трюках современного _CMake_.
13. Martin Bond: [CMake Presets](https://blog.feabhas.com/2023/08/cmake-presets/) — Обзор [cmake-presets](https://cmake.org/cmake/help/latest/manual/cmake-presets.7.html), нововведения _CMake 3.19_, значительно упрощающего конфигурирование и сборку проектов.
14. Daniel Lemire: [Decoding base16 sequences quickly](https://lemire.me/blog/2023/07/27/decoding-base16-sequences-quickly/) — Обзор быстрого алгоритма декодирования _base16_, основанного на векторизации с использованием _SSE2_ и _SSE3_ инструкций.

## 📺 Видео

1. Jason Turner: [C++ Weekly - Ep 386 - C++23's Lambda Attributes ](https://www.youtube.com/watch?v=YlmxNJnone0)
2. Jason Turner: [C++ Weekly - SE - Interview with Stephen Berry - ODE's, Physics, constexpr, High Performance C++](https://www.youtube.com/watch?v=NS9rh_DuL_E)
3. Jason Turner: [C++ Weekly - Ep 387 - My Customized C++ Programming Keyboard!](https://www.youtube.com/watch?v=LwxBLG8aGlo) — Обзор самодельной клавиатуры, позволяющей набирать _const_, _constexpr_ и прочие ключевые слова с недостижимой ранее скоростью.
4. The Cherno: [Instant Messaging App in C++ // Code Review](https://www.youtube.com/watch?v=HAn6B7TTtuQ) — Код-ревью [простенького чатика](https://github.com/TheCherno/Walnut-Chat), написанного самим же автором видео.

## 🎙️Подкасты

1. CppCast: [Episode 366, How CLion works under the hood](https://cppcast.com/how_clion_works_under_the_hood/) — Об особенностях внутренней машинерии CLion: парсеров, семантических анализаторов и прочего, вдыхающей жизнь в весь продукт.
2. Algorithms + Data Structures = Programs:  [Episode 140: 🇨🇦 CppNorth Live 🇨🇦 Victor Ciura, Andreas Weis & More!](https://adspthepodcast.com/2023/07/28/Episode-140.html),  [Episode 141: 🇨🇦 CppNorth Live 🇨🇦 Kate Gregory, Jessica Kerr & Kristen Shaker! ](https://adspthepodcast.com/2023/08/04/Episode-141.html)
