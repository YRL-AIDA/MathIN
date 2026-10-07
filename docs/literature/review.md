# Цель

Исследовать возможности, ограничения, риски AI в работе с математической литературой.

Рекомендуемые системы для поиска: Google Scholar, Chat DeepSeek, а также встроенный поиск

Репозитории с исследованиями:

<https://github.com/handsome-rich/Awesome-Auto-Research-Tools#1>

# Вопросы:

- [ ] Какие системы есть для автоматических проведений исследований?

- [ ] Можно ли использовать такие системы для математических исследований?

- [ ] Как представить математическое знание?

- [ ] Чем так интересны языки типа Lean в вопросах автоматизации исследований

- [ ] Если представлять математическое знание в виде графа, то что есть узел (какие они бывают), что есть связь (какие они бывают)?

- [ ] Как извлекать знания из документов?

- [ ] Есть ли специальные форматы, которые позволят хранить такие данные?

- [ ] Как распознать формулу из документа?

- [ ] Дорого ли использовать LLM для чтения статей?

- [ ] Как писать промпты и как должны выглядить навыки для такой работы?

- [ ] Какой вид более удобный для представления проекта: навык, утилита или приложение?

- [ ] Что будет с моделью, если ей дать неизвестную или плохо известную область (например, Нелокальные формулы улучшения в задачах ОУ?)

- [ ] Как долго система будет проводить исследование?

- [ ] Какие этапы являются самыми сложными для LLM?

- [ ] 

## Ключевые слова и термины:

| ru | en |
| --- | --- |
| Большие языковые модели (БЯМ) | Large Language Models (LLM) |
| Предобученные языковые модели | <span style="color: rgb(15, 17, 21);">Pre-trained Language Models (</span>PLM) |
| Математические рассуждения | Mathematical Reasoning |
| Решение сюжетных задач | **Contextualized problems** |
| Задача вычисления (решения) | **Direct mathematical problems** |
| Математические текстовые задачи | <span style="color: rgb(15, 17, 21);">Math Word Problems</span> |
| Цепочки рассуждений | **Chain-of-Thought (CoT)** |
| <span style="color: rgb(15, 17, 21);">Основы CoT</span> | **Foundation of CoT** |
| <span style="color: rgb(15, 17, 21);">Построение CoT</span> | **Construction of CoT** |
| Отсеиватель | <span style="color: rgb(15, 17, 21);">Pruner</span> |
| <span style="color: rgb(15, 17, 21);">контекстный однорукий бандит</span> | <span style="color: rgb(15, 17, 21);">contextual bandit</span> |

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
| V | 2026_Forootani_review | Ali Forootani,<span style="color: rgb(31, 31, 31);"> </span>Danial Esmaeili Aliabadi<span style="color: rgb(31, 31, 31);">, </span>Daniela Thrän | A survey on mathematical reasoning and optimization with large language models | 2025 | 10.1016/j.iswa.2026.200712 | Обзор на 354 источника, рассматриваются модели, классифицируются задачи, выборка наборов данных и анализ проблем (даже для топовых больших языковых моделей) |
| V | 2025_Liu_review.md | Wentao Liu, Hanglei Hu, Jie Zhou, Yuyang Ding, Junsong Li, Jiayi Zeng, Mengliang He, Qin Chen, Bo Jiang, Aimin Zhou, Liang He | Mathematical Language Models: A Survey | 2025 | <https://dl.acm.org/doi/10.1145/3773985> | Обзор, акцент на PLM и LLM подходы |
| V | 2026_Zhang_DAG-Math.md | Zhang, Y., Kuzborskij, I., Lee, J. D., Leng, C., & Liu, F. | DAG-MATH: GRAPH-OF-THOUGHT GUIDED MATHE- MATICAL REASONING IN LLMS | 2026 |  | <span style="color: rgb(15, 17, 21);">Работа предлагает DAG-MATH — моделирование CoT как DAG с метриками logical closeness и perfect reasoning; PASS@1 завышает реальную способность рассуждать.</span> |
|  |  | Luke Alexander, Eric Leonen, Sophie Szeto and et.al | Semantic Search over 9 Million Mathematical Theorems | 2026 | <https://arxiv.org/pdf/2602.05216> | Математическая теория, очень большой объем |
|  |  | Guijin Son, Seungyeop Yi, Minju Gwak, Hyunwoo Ko, Wongi Jang, Youngjae Yu | ResearchMath-14K: Scaling Research-Level Mathematics via Agents | 2026 | <http://arxiv.org/abs/2605.28003> | Набор данных |
|  |  | Fabian Gloeckle, Ahmad Rammal, Charles Arnal, Remi Munos, Vivien Cabannes, Gabriel Synnaeve, Amaury Hayat | Automatic Textbook Formalization | 2026 | <http://arxiv.org/abs/2604.03071> | 30 000 агентов переводят учебник 500 страниц в Lean, 130 строк кода |
|  |  | Kaiyu Yang, Aidan M. Swope, Alex Gu, Rahul Chalamala, Peiyang Song, Shixing Yu, Saad Godil, Ryan Prenger, Anima Anandkumar | LeanDojo: Theorem Proving with Retrieval-Augmented Language Models | 2023 | <https://arxiv.org/abs/2604.03071> | Среда доказательства LeanDojo |
|  |  | Janice Ahn, Rishu Verma, Renze Lou, Di Liu, Rui Zhang, and Wenpeng Yin | Large Language Models for Mathematical Reasoning: Progresses and Challenges | 2024 | <https://aclanthology.org/2024.eacl-srw.17.pdf> | Обзор: 1) какие задачи и наборы данных; 2) Методы для БЯМ 3) Проблемы и факторы влияющие на качество 4) Разъяснение проблем |
|  |  | Shima Imani, Liang Du, Harsh Shrivastava | MathPrompter: Mathematical Reasoning using Large Language Models | 2023 | <https://aclanthology.org/2023.acl-industry.4.pdf> | Повышение уровня уверености в задачах |
|  |  | Youliang Yuan, Qiuyang Mang, Jingbang Chen, Hong Wan, Xiaoyuan Liu, Junjielong Xu, Jen-tse Huang, Wenxuan Wang, Wenxiang Jiao, Pinjia He | Curing Miracle Steps in LLM Mathematical Reasoning with Rubric Rewards | 2026 | <https://aclanthology.org/2026.acl-long.844.pdf> | Оценка цепочек рассуждения, а не ответов. Поскольку модель подгоняет под ответ, запомнив его. |
|  |  | Yuanhe Zhang, Ilja Kuzborskij, Jason D. Lee, Chenlei Leng, Fanghui Liu | DAG-MATH: GRAPH-OF-THOUGHT GUIDED MATHE- MATICAL REASONING IN LLMS | 2026 | <https://arxiv.org/abs/2510.19842> | Набор данных с цепочками размышлений |
|  |  | Pan Lu , Liang Qiu , Wenhao Yu , Sean Welleck , Kai-Wei Chang | A Survey of Deep Learning for Mathematical Reasoning | 2023 | <https://aclanthology.org/2023.acl-long.817/> | Обзор: глубокое обучение для математического размышлений |
|  |  | Shuofei Qiao, Yixin Ou1, Ningyu Zhang, Xiang Chen, Yunzhi Yao, Shumin Deng, Chuanqi Tan, Fei Huang, Huajun Chen | Reasoning with Language Model Prompting: A Survey | 2023 | <https://aclanthology.org/2023.acl-long.294/> | Обзор: общие механизмы размышлений |
|  |  | Zheng Chu, Jingchang Chen, Qianglong Chen, Weijiang Yu, Tao He, Haotian Wang, Weihua Peng, Ming Liu, Bing Qin, Ting Liu | A Survey of Chain of Thought Reasoning: Advances, Frontiers and Future | 2024 | <https://arxiv.org/abs/2309.15402> | Обзор: цепочки мыслей |
|  |  | Xipeng Qiu , Tianxiang Sun, Yige Xu, Yunfan Shao, Ning Dai, Xuanjing Huang | Pre-trained Models for Natural Language Processing: A Survey | 2021 | <https://arxiv.org/abs/2003.08271> | Обзор: предварительно предобученные языковые модели |
|  |  | W. X. Zhao, K. Zhou, J. Li, T. Tang, X. Wang, Y. Hou, Y. Min, B. Zhang, J. Zhang, Z. Dong, et al., | A survey of large language models | 2026 | <https://arxiv.org/abs/2303.18223> | Обзор: предварительно обученные большие языковые модели |
|  |  | Y. Yan, J. Su, J. He, F. Fu, X. Zheng, Y. Lyu, K. Wang, S. Wang, Q. Wen, X. Hu, | A survey of mathematical reasoning in the era of multimodal large language model: Benchmark, method & challenges | 2024 | <https://arxiv.org/abs/2412.11936> |  |
|  |  | Yuhuai Wu, Markus Rabe, Wenda Li, Jimmy Ba, Roger Grosse, Christian Szegedy | LIME: Learning Inductive Bias for Primitives of Mathematical Reasoning | 2021 | <https://arxiv.org/abs/2101.06223> | Понимание ИИ индукции, дедукции и абдукции |
|  |  | Can Xu, Qingfeng Sun, Kai Zheng, Xiubo Geng, Pu Zhao, Jiazhan Feng, Chongyang Tao, Qingwei Lin, Daxin Jiang | WizardLM: Empowering large pre-trained language models to follow complex instructions | 2025 | <https://arxiv.org/abs/2304.12244> | <span style="color: rgb(15, 17, 21);">подход к созданию инструкций для LLM по простым</span> |
|  |  | Shai Shalev-Shwartz, Amnon Shashua | From Reasoning to Super-Intelligence: A Search-Theoretic Perspective | 2025 | <https://arxiv.org/abs/2507.15865> | Diligent Learner |
|  |  | <span style="color: rgb(45, 55, 72);">Ben Prystawski, Michael Li, Noah Goodman</span> | Why think step by step? Reasoning emerges from the locality of experience | 2023 | <https://doi.org/10.52202/075280-3107> |  |
|  |  | Tian Ye, Zicheng Xu \~Zicheng_Xu1 , Yuanzhi Li, Zeyuan Allen-Zhu | Physics of Language Models: Part 2.1, Grade-School Math and the Hidden Reasoning Process | 2025 | <https://openreview.net/forum?id=Tn5B6Udq3E> |  |

### Реестр программ

| id | Название | Год появления | Ссылка на страницу | Комментарий (1-3 предложений) |
| --- | --- | --- | --- | --- |
|  | codex-paper-reader |  | <https://github.com/Lihui-Liu/codex-paper-reader> | Навык |
|  | Paper-Reading-Skill |  | <https://github.com/sunny2109/Paper-Reading-Skill> | Навык |

### Что ожидается на выходе

| Решение (и ссылка) | Умеет работать с коллекциями документов | Способ извлечения из документов | Поддержка языков типа Lean (какой) | Наличие поиска | Наличие редактора и ввода | Наличие возможности выдвижения гипотез | Автоматическая проверка доказательств | Поддержка ДУЧП и ОУ | Работа с поисковиком | Наличие возможности консультации | Распознавание математических формул |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| <https://github.com/SakanaAI/AI-Scientist> |  |  |  |  |  |  |  |  |  |  |  |
| <https://github.com/microsoft/RD-Agent> |  |  |  |  |  |  |  |  |  |  |  |
| <https://github.com/aiming-lab/AutoResearchClaw> |  |  |  |  |  |  |  |  |  |  |  |
| <https://github.com/EvoScientist/EvoScientist> |  |  |  |  |  |  |  |  |  |  |  |
| <https://deerflow.tech/demo/threads/fe3f7974-1bcb-4a01-a950-79673baafefd/user-data/outputs/index.html?download=true> |  |  |  |  |  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |  |  |  |  |  |

### Таксономия задач

1. Вычисления
2. Рассуждения

### **Реестр моделей**

| Название | Тип | Описание | Комментарий | Ссылка |  |  |
| --- | --- | --- | --- | --- | --- | --- |
| GenBERT | PLM |  |  |  |  |  |
| NF-NSM | PLM |  |  |  |  |  |
| MathBERT | PLM |  |  |  |  |  |
| LISA | PLM |  |  |  |  |  |
| <span style="color: rgb(15, 17, 21);">LLEMMA</span> | LLM |  |  |  |  |  |
| <span style="color: rgb(15, 17, 21);">Qwen-Math</span> | LLM |  |  |  |  |  |
| <span style="color: rgb(15, 17, 21);">InternLM-Math</span> | LLM |  |  |  |  |  |
| <span style="color: rgb(15, 17, 21);">o1, o3</span> | LLM |  |  |  |  |  |
| <span style="color: rgb(15, 17, 21);">MathPrompter</span> |  |  | <span style="color: rgb(15, 17, 21);">использует GPT-3 DaVinci для решения математических текстовых задач и демонстрирует способность LLM не только объяснять, но и генерировать сложные математические рассуждения</span> |  |  |  |
| <span style="color: rgb(15, 17, 21);">MetaMath</span> |  |  | <span style="color: rgb(15, 17, 21);">предлагает парадигму, в которой LLM сама генерирует математические задачи, создавая самоподдерживающуюся среду обучения для постоянного улучшения решения задач</span> |  |  |  |
| <span style="color: rgb(15, 17, 21);">WizardMath</span> |  |  | <span style="color: rgb(15, 17, 21);">повышает способности LLM к математическим рассуждениям через усиление эволюционных инструкций, делая шаг к автономному самосовершенствованию модели</span> |  |  |  |
| ASTactic |  |  | <span style="color: rgb(15, 17, 21);">модель, способная автономно генерировать стратегии доказательства теорем</span> |  |  |  |
| GPT-f |  |  | <span style="color: rgb(15, 17, 21);">языковая модель на основе Transformer для автоматического доказательства теорем; некоторые её доказательства были формально признаны математическим сообществом</span> |  |  |  |
| Chameleon |  |  | <span style="color: rgb(15, 17, 21);">инамически составляет программу из множества модулей (поиск, Python, модели зрения, эвристики), чтобы решать сложные многомодальные задачи. Главное - гибко комбинировать инструменты под задачу</span> |  |  |  |
| ART |  |  | <span style="color: rgb(15, 17, 21);">не требует ручных демонстраций: замороженная LLM сама генерирует промежуточные шаги и вызовы инструментов для новых задач. Главное - автоматически строить программы с инструментами</span> |  |  |  |
| CRITIC |  |  | <span style="color: rgb(15, 17, 21);">LLM сначала даёт ответ, а потом с помощью инструментов (поиск, интерпретатор кода) критикует и исправляет его. Главное — повысить надёжность и уменьшить ошибки/галлюцинации</span> |  |  |  |
| ToRA |  |  | <span style="color: rgb(15, 17, 21);">специально дообучается интегрировать вычислительные библиотеки и символьные решатели (Python, SymPy) для решения сложных текстовых задач. Главное — точные вычисления через инструменты, а не только рассуждения</span> |  |  |  |

# Проблемы, которые пытаются решить

## Нехватка данных и оценка моделей

## Галлюцинации

## Открытие новых знаний

## Мультимодальность