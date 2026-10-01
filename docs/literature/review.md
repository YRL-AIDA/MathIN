# Цель

Исследовать возможности, ограничения, риски LLM в работе с математической литературой.

Рекомендуемые системы для поиска: Google Scholar, Chat DeepSeek, а также встроенный поиск в

### Ключевые слова и термины:

| ru | en |
| --- | --- |
| Большие языковые модели (БЯМ) | Large Language Models (LLM) |
| Математические рассуждения | Mathematical Reasoning |
| Решение сюжетных задач | **Contextualized problems** |
| Просто вычисления | **Direct mathematical problems** |

### Запросы:

LLM+"Mathematical Reasoning"

### Журналы и конференции:

- [Intelligent Systems with Applications](https://www.scimagojr.com/journalsearch.php?q=21101051831&tip=sid&clean=0) (Q1)
- <span style="color: rgb(0, 0, 0);">NeurIPS (A\*)</span>
- [ACM Computing Surveys ](https://www.scimagojr.com/journalsearch.php?q=23038&tip=sid&clean=0)(Q1)
- ACL (A\*)
- ICLR (A\*)

## Ключевые работы:

Ограничения: не больше 20 работ, Q1 и A\*, есть исходники (воспроизводимость)

## Свежие работы (1 год):

Ограничения: допускаются preprint, статьи в журналах и результаты конференций, есть исходники (воспроизводимость), &lt; 1 года.

## Актуальные работы (5 лет):

Ограничения: Q3-Q1 и A\*, есть исходники (воспроизводимость)

## Программные средства

Ссылки на страницы продуктов

### Реестр публикаций

| read? | id | Авторы | Название | Год | Ссылка или DOI | Комментарий (1-3 предложений) |
| --- | --- | --- | --- | --- | --- | --- |
|  | 2026_Forootani_review | Ali Forootani,<span style="color: rgb(31, 31, 31);"> </span>Danial Esmaeili Aliabadi<span style="color: rgb(31, 31, 31);">, </span>Daniela Thrän | A survey on mathematical reasoning and optimization with large language models | 2025 | 10.1016/j.iswa.2026.200712 | Обзор |
|  |  | Luke Alexander, Eric Leonen, Sophie Szeto and et.al | Semantic Search over 9 Million Mathematical Theorems | 2026 | <https://arxiv.org/pdf/2602.05216> | Математическая теория, очень большой объем |
|  |  | Guijin Son, Seungyeop Yi, Minju Gwak, Hyunwoo Ko, Wongi Jang, Youngjae Yu | ResearchMath-14K: Scaling Research-Level Mathematics via Agents | 2026 | <http://arxiv.org/abs/2605.28003> | Набор данных |
|  |  | Fabian Gloeckle, Ahmad Rammal, Charles Arnal, Remi Munos, Vivien Cabannes, Gabriel Synnaeve, Amaury Hayat | Automatic Textbook Formalization | 2026 | <http://arxiv.org/abs/2604.03071> | 30 000 агентов переволят учебник 500 страниц в Lean, 130 строк кода |
|  |  | Kaiyu Yang, Aidan M. Swope, Alex Gu, Rahul Chalamala, Peiyang Song, Shixing Yu, Saad Godil, Ryan Prenger, Anima Anandkumar | LeanDojo: Theorem Proving with Retrieval-Augmented Language Models | 2023 | <https://arxiv.org/abs/2604.03071> | Среда доказательства LeanDojo |
|  |  | Wentao Liu, Hanglei Hu, Jie Zhou, Yuyang Ding, Junsong Li, Jiayi Zeng, Mengliang He, Qin Chen, Bo Jiang, Aimin Zhou, Liang He | Mathematical Language Models: A Survey | 2025 | <https://dl.acm.org/doi/10.1145/3773985> | Обзор |
|  |  | Janice Ahn, Rishu Verma, Renze Lou, Di Liu, Rui Zhang, and Wenpeng Yin | Large Language Models for Mathematical Reasoning: Progresses and Challenges | 2024 | <https://aclanthology.org/2024.eacl-srw.17.pdf> | Обзор: 1) какие задачи и наборы данных; 2) Методы для БЯМ 3) Проблемы и факторы влияющие на качество 4) Разъяснение проблем |
|  |  | Shima Imani, Liang Du, Harsh Shrivastava | MathPrompter: Mathematical Reasoning using Large Language Models | 2023 | <https://aclanthology.org/2023.acl-industry.4.pdf> | Повышение уровня уверености в задачах |
|  |  | Youliang Yuan, Qiuyang Mang, Jingbang Chen, Hong Wan, Xiaoyuan Liu, Junjielong Xu, Jen-tse Huang, Wenxuan Wang, Wenxiang Jiao, Pinjia He | Curing Miracle Steps in LLM Mathematical Reasoning with Rubric Rewards | 2026 | <https://aclanthology.org/2026.acl-long.844.pdf> | Оценка цепочек рассуждения, а не ответов. Поскольку модель подгоняет под ответ, запомнив его. |
|  |  | Yuanhe Zhang, Ilja Kuzborskij, Jason D. Lee, Chenlei Leng, Fanghui Liu | DAG-MATH: GRAPH-OF-THOUGHT GUIDED MATHE- MATICAL REASONING IN LLMS | 2026 | <https://arxiv.org/abs/2510.19842> | Набор данных с цепочками размышлений |

### Реестр программ

| id | Название | Год появления | Ссылка на страницу | Комментарий (1-3 предложений) |
| --- | --- | --- | --- | --- |
|  | codex-paper-reader |  | <https://github.com/Lihui-Liu/codex-paper-reader> | Навык |
|  | Paper-Reading-Skill |  | <https://github.com/sunny2109/Paper-Reading-Skill> | Навык |

### Что ожидается на выходе

| Решение (и ссылка) | Умеет работать с коллекциями документов | Способ извлечения из документов | Поддержка языков типа Lean (какой) | Наличие поиска | Наличие редактора и ввода | Наличие возможности выдвижения гипотез | Автоматическая проверка доказательств | Поддержка ДУЧП и ОУ | Работа с поисковиком | Наличие возможности консультации | Распознавание математических формул |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  |  |  |  |  |  |  |  |  |  |  |  |
