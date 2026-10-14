# Цель

Исследовать возможности, ограничения, риски AI в работе с математической литературой.

Рекомендуемые системы для поиска: Google Scholar, Chat DeepSeek, а также встроенный поиск

Репозитории с исследованиями:

<https://github.com/handsome-rich/Awesome-Auto-Research-Tools#1>

# Вопросы:

## Группа 1. Представление математического знания

- [ ] Какие уровни представления нужны: неформальный текст, LaTeX, MathML, OpenMath, OMDoc, Lean, граф знаний?

- [ ] Какая онтология математики нужна: типы утверждений, доказательств, понятий, формул?

- [ ] Почему Lean важен: проверяемость, mathlib, зависимые типы, autoformalization, обучение моделей?

- [ ] Какие форматы хранения выбирать: RDF/OWL/JSON-LD, property graph, Neo4j, Lean, SQL, vector DB?

- [ ] Как обеспечивать прослеживаемость и цитирование?

- [ ] Как обновлять граф знаний при появлении новых статей?

- [ ] Как связывать разные источники и обозначения?

- [ ] Как интегрировать Lean и кто проверяет формализацию?

## Группа 2. Извлечение знаний из документов

- [ ] Как из PDF/LaTeX/arXiv извлекать теоремы, определения, доказательства, формулы и связи?

- [ ] Как распознавать формулы: LaTeX-OCR, MathML, мультимодальные модели?

- [ ] Какова стоимость LLM-пайплайна: токены, OCR, эмбеддинги, кэширование, локальные модели?

- [ ] Как обрабатывать противоречия и ошибки в литературе?

## Группа 3. Системы автоматизации исследований и их применемость к математике

- [ ] Какие классы систем автоматизации research существуют: LLM-агенты, neuro-symbolic системы, theorem provers, symbolic discovery, literature-review системы?

- [ ] Какие этапы математического исследования они покрывают: обзор литературы, генерация гипотез, доказательство, формализация, проверка, поиск контрпримеров?

- [ ] Какие архитектуры применимы именно к математике: multi-agent, tool-use, RAG, Lean-интеграция, человек-в-цикле?

## Группа 4. Инженерия AI-компонентов

- [ ] Как проектировать промпты и навыки для математических задач: извлечение, формализация, доказательство, критика?

- [ ] Что выбрать на раннем этапе: skill, utility или app?

- [ ] Как масштабировать и воспроизводить эксперименты?

## Группа 5. Оценка, ограничения, динамика

- [ ] Что будет с моделью, если ей дать неизвестную или плохо известную область?

- [ ] Что будет с моделью, если ей дать неизвестную или плохо известную область? Как долго система будет проводить исследование?

- [ ] Какие этапы являются самыми сложными для LLM?

- [ ] Как определять новизну и значимость результата?

- [ ] Как оценивать качество извлечения и графа?

- [ ] Как избежать галлюцинаций?

- [ ] Какова этика, авторство и лицензии?

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

<table style="min-width: 175px;">
<colgroup><col style="min-width: 25px;"><col style="min-width: 25px;"><col style="min-width: 25px;"><col style="min-width: 25px;"><col style="min-width: 25px;"><col style="min-width: 25px;"><col style="min-width: 25px;"></colgroup><tbody><tr><th colspan="1" rowspan="1"><p>read?</p></th><th colspan="1" rowspan="1"><p>id</p></th><th colspan="1" rowspan="1"><p>Авторы</p></th><th colspan="1" rowspan="1"><p>Название</p></th><th colspan="1" rowspan="1"><p>Год</p></th><th colspan="1" rowspan="1"><p>Ссылка или DOI</p></th><th colspan="1" rowspan="1"><p>Комментарий (1-3 предложений)</p></th></tr><tr><td colspan="1" rowspan="1"><p>V</p></td><td colspan="1" rowspan="1"><p>2026_Forootani_review</p></td><td colspan="1" rowspan="1"><p>Ali Forootani,<span style="color: rgb(31, 31, 31);"> </span>Danial Esmaeili Aliabadi<span style="color: rgb(31, 31, 31);">, </span>Daniela Thrän</p></td><td colspan="1" rowspan="1"><p>A survey on mathematical reasoning and optimization with large language models</p></td><td colspan="1" rowspan="1"><p>2025</p></td><td colspan="1" rowspan="1"><p>10.1016/j.iswa.2026.200712</p></td><td colspan="1" rowspan="1"><p>Обзор на 354 источника, рассматриваются модели, классифицируются задачи, выборка наборов данных и анализ проблем (даже для топовых больших языковых моделей)</p></td></tr><tr><td colspan="1" rowspan="1"><p>V</p></td><td colspan="1" rowspan="1"><p>2025_Liu_review.md</p></td><td colspan="1" rowspan="1"><p>Wentao Liu, Hanglei Hu, Jie Zhou, Yuyang Ding, Junsong Li, Jiayi Zeng, Mengliang He, Qin Chen, Bo Jiang, Aimin Zhou, Liang He</p></td><td colspan="1" rowspan="1"><p>Mathematical Language Models: A Survey</p></td><td colspan="1" rowspan="1"><p>2025</p></td><td colspan="1" rowspan="1"><p><a target="_blank" rel="noopener noreferrer nofollow" href="https://dl.acm.org/doi/10.1145/3773985">https://dl.acm.org/doi/10.1145/3773985</a></p></td><td colspan="1" rowspan="1"><p>Обзор, акцент на PLM и LLM подходы</p></td></tr><tr><td colspan="1" rowspan="1"><p>V</p></td><td colspan="1" rowspan="1"><p>2026_Zhang_DAG-Math.md</p></td><td colspan="1" rowspan="1"><p>Zhang, Y., Kuzborskij, I., Lee, J. D., Leng, C., &amp; Liu, F.</p></td><td colspan="1" rowspan="1"><p>DAG-MATH: GRAPH-OF-THOUGHT GUIDED MATHE- MATICAL REASONING IN LLMS</p></td><td colspan="1" rowspan="1"><p>2026</p></td><td colspan="1" rowspan="1"><p></p></td><td colspan="1" rowspan="1"><p><span style="color: rgb(15, 17, 21);">Работа предлагает DAG-MATH — моделирование CoT как DAG с метриками logical closeness и perfect reasoning; PASS@1 завышает реальную способность рассуждать.</span></p></td></tr><tr><td colspan="1" rowspan="1"><p>V</p></td><td colspan="1" rowspan="1"><p>2026_Luke_set_9B_theorems.md</p><p></p></td><td colspan="1" rowspan="1"><p>Luke Alexander, Eric Leonen, Sophie Szeto and et.al</p></td><td colspan="1" rowspan="1"><p>Semantic Search over 9 Million Mathematical Theorems</p></td><td colspan="1" rowspan="1"><p>2026</p><p></p></td><td colspan="1" rowspan="1"><p><a target="_blank" rel="noopener noreferrer nofollow" href="https://arxiv.org/pdf/2602.05216">https://arxiv.org/pdf/2602.05216</a></p><p></p></td><td colspan="1" rowspan="1"><p>Математическая теория, очень большой объем</p><p></p></td></tr><tr><td colspan="1" rowspan="1"><p></p></td><td colspan="1" rowspan="1"><p></p></td><td colspan="1" rowspan="1"><p>Guijin Son, Seungyeop Yi, Minju Gwak, Hyunwoo Ko, Wongi Jang, Youngjae Yu</p></td><td colspan="1" rowspan="1"><p>ResearchMath-14K: Scaling Research-Level Mathematics via Agents</p></td><td colspan="1" rowspan="1"><p>2026</p></td><td colspan="1" rowspan="1"><p><a target="_blank" rel="noopener noreferrer nofollow" href="http://arxiv.org/abs/2605.28003">http://arxiv.org/abs/2605.28003</a></p></td><td colspan="1" rowspan="1"><p>Набор данных</p></td></tr><tr><td colspan="1" rowspan="1"><p></p></td><td colspan="1" rowspan="1"><p></p></td><td colspan="1" rowspan="1"><p>Fabian Gloeckle, Ahmad Rammal, Charles Arnal, Remi Munos, Vivien Cabannes, Gabriel Synnaeve, Amaury Hayat</p></td><td colspan="1" rowspan="1"><p>Automatic Textbook Formalization</p></td><td colspan="1" rowspan="1"><p>2026</p></td><td colspan="1" rowspan="1"><p><a target="_blank" rel="noopener noreferrer nofollow" href="http://arxiv.org/abs/2604.03071">http://arxiv.org/abs/2604.03071</a></p></td><td colspan="1" rowspan="1"><p>30 000 агентов переводят учебник 500 страниц в Lean, 130 строк кода</p></td></tr><tr><td colspan="1" rowspan="1"><p></p></td><td colspan="1" rowspan="1"><p></p></td><td colspan="1" rowspan="1"><p>Kaiyu Yang, Aidan M. Swope, Alex Gu, Rahul Chalamala, Peiyang Song, Shixing Yu, Saad Godil, Ryan Prenger, Anima Anandkumar</p></td><td colspan="1" rowspan="1"><p>LeanDojo: Theorem Proving with Retrieval-Augmented Language Models</p></td><td colspan="1" rowspan="1"><p>2023</p></td><td colspan="1" rowspan="1"><p><a target="_blank" rel="noopener noreferrer nofollow" href="https://arxiv.org/abs/2604.03071">https://arxiv.org/abs/2604.03071</a></p></td><td colspan="1" rowspan="1"><p>Среда доказательства LeanDojo</p></td></tr><tr><td colspan="1" rowspan="1"><p></p></td><td colspan="1" rowspan="1"><p></p></td><td colspan="1" rowspan="1"><p>Janice Ahn, Rishu Verma, Renze Lou, Di Liu, Rui Zhang, and Wenpeng Yin</p></td><td colspan="1" rowspan="1"><p>Large Language Models for Mathematical Reasoning: Progresses and Challenges</p></td><td colspan="1" rowspan="1"><p>2024</p></td><td colspan="1" rowspan="1"><p><a target="_blank" rel="noopener noreferrer nofollow" href="https://aclanthology.org/2024.eacl-srw.17.pdf">https://aclanthology.org/2024.eacl-srw.17.pdf</a></p></td><td colspan="1" rowspan="1"><p>Обзор: 1) какие задачи и наборы данных; 2) Методы для БЯМ 3) Проблемы и факторы влияющие на качество 4) Разъяснение проблем</p></td></tr><tr><td colspan="1" rowspan="1"><p></p></td><td colspan="1" rowspan="1"><p></p></td><td colspan="1" rowspan="1"><p>Shima Imani, Liang Du, Harsh Shrivastava</p></td><td colspan="1" rowspan="1"><p>MathPrompter: Mathematical Reasoning using Large Language Models</p></td><td colspan="1" rowspan="1"><p>2023</p></td><td colspan="1" rowspan="1"><p><a target="_blank" rel="noopener noreferrer nofollow" href="https://aclanthology.org/2023.acl-industry.4.pdf">https://aclanthology.org/2023.acl-industry.4.pdf</a></p></td><td colspan="1" rowspan="1"><p>Повышение уровня уверености в задачах</p></td></tr><tr><td colspan="1" rowspan="1"><p></p></td><td colspan="1" rowspan="1"><p></p></td><td colspan="1" rowspan="1"><p>Youliang Yuan, Qiuyang Mang, Jingbang Chen, Hong Wan, Xiaoyuan Liu, Junjielong Xu, Jen-tse Huang, Wenxuan Wang, Wenxiang Jiao, Pinjia He</p></td><td colspan="1" rowspan="1"><p>Curing Miracle Steps in LLM Mathematical Reasoning with Rubric Rewards</p></td><td colspan="1" rowspan="1"><p>2026</p></td><td colspan="1" rowspan="1"><p><a target="_blank" rel="noopener noreferrer nofollow" href="https://aclanthology.org/2026.acl-long.844.pdf">https://aclanthology.org/2026.acl-long.844.pdf</a></p></td><td colspan="1" rowspan="1"><p>Оценка цепочек рассуждения, а не ответов. Поскольку модель подгоняет под ответ, запомнив его.</p></td></tr><tr><td colspan="1" rowspan="1"><p></p></td><td colspan="1" rowspan="1"><p></p></td><td colspan="1" rowspan="1"><p>Yuanhe Zhang, Ilja Kuzborskij, Jason D. Lee, Chenlei Leng, Fanghui Liu</p></td><td colspan="1" rowspan="1"><p>DAG-MATH: GRAPH-OF-THOUGHT GUIDED MATHE- MATICAL REASONING IN LLMS</p></td><td colspan="1" rowspan="1"><p>2026</p></td><td colspan="1" rowspan="1"><p><a target="_blank" rel="noopener noreferrer nofollow" href="https://arxiv.org/abs/2510.19842">https://arxiv.org/abs/2510.19842</a></p></td><td colspan="1" rowspan="1"><p>Набор данных с цепочками размышлений</p></td></tr><tr><td colspan="1" rowspan="1"><p></p></td><td colspan="1" rowspan="1"><p></p></td><td colspan="1" rowspan="1"><p>Pan Lu , Liang Qiu , Wenhao Yu , Sean Welleck , Kai-Wei Chang</p></td><td colspan="1" rowspan="1"><p>A Survey of Deep Learning for Mathematical Reasoning</p></td><td colspan="1" rowspan="1"><p>2023</p></td><td colspan="1" rowspan="1"><p><a target="_blank" rel="noopener noreferrer nofollow" href="https://aclanthology.org/2023.acl-long.817/">https://aclanthology.org/2023.acl-long.817/</a></p></td><td colspan="1" rowspan="1"><p>Обзор: глубокое обучение для математического размышлений</p></td></tr><tr><td colspan="1" rowspan="1"><p></p></td><td colspan="1" rowspan="1"><p></p></td><td colspan="1" rowspan="1"><p>Shuofei Qiao, Yixin Ou1, Ningyu Zhang, Xiang Chen, Yunzhi Yao, Shumin Deng, Chuanqi Tan, Fei Huang, Huajun Chen</p></td><td colspan="1" rowspan="1"><p>Reasoning with Language Model Prompting: A Survey</p></td><td colspan="1" rowspan="1"><p>2023</p></td><td colspan="1" rowspan="1"><p><a target="_blank" rel="noopener noreferrer nofollow" href="https://aclanthology.org/2023.acl-long.294/">https://aclanthology.org/2023.acl-long.294/</a></p></td><td colspan="1" rowspan="1"><p>Обзор: общие механизмы размышлений</p></td></tr><tr><td colspan="1" rowspan="1"><p></p></td><td colspan="1" rowspan="1"><p></p></td><td colspan="1" rowspan="1"><p>Zheng Chu, Jingchang Chen, Qianglong Chen, Weijiang Yu, Tao He, Haotian Wang, Weihua Peng, Ming Liu, Bing Qin, Ting Liu</p></td><td colspan="1" rowspan="1"><p>A Survey of Chain of Thought Reasoning: Advances, Frontiers and Future</p></td><td colspan="1" rowspan="1"><p>2024</p></td><td colspan="1" rowspan="1"><p><a target="_blank" rel="noopener noreferrer nofollow" href="https://arxiv.org/abs/2309.15402">https://arxiv.org/abs/2309.15402</a></p></td><td colspan="1" rowspan="1"><p>Обзор: цепочки мыслей</p></td></tr><tr><td colspan="1" rowspan="1"><p></p></td><td colspan="1" rowspan="1"><p></p></td><td colspan="1" rowspan="1"><p>Xipeng Qiu , Tianxiang Sun, Yige Xu, Yunfan Shao, Ning Dai, Xuanjing Huang</p></td><td colspan="1" rowspan="1"><p>Pre-trained Models for Natural Language Processing: A Survey</p></td><td colspan="1" rowspan="1"><p>2021</p></td><td colspan="1" rowspan="1"><p><a target="_blank" rel="noopener noreferrer nofollow" href="https://arxiv.org/abs/2003.08271">https://arxiv.org/abs/2003.08271</a></p></td><td colspan="1" rowspan="1"><p>Обзор: предварительно предобученные языковые модели</p></td></tr><tr><td colspan="1" rowspan="1"><p></p></td><td colspan="1" rowspan="1"><p></p></td><td colspan="1" rowspan="1"><p>W. X. Zhao, K. Zhou, J. Li, T. Tang, X. Wang, Y. Hou, Y. Min, B. Zhang, J. Zhang, Z. Dong, et al.,</p></td><td colspan="1" rowspan="1"><p>A survey of large language models</p></td><td colspan="1" rowspan="1"><p>2026</p></td><td colspan="1" rowspan="1"><p><a target="_blank" rel="noopener noreferrer nofollow" href="https://arxiv.org/abs/2303.18223">https://arxiv.org/abs/2303.18223</a></p></td><td colspan="1" rowspan="1"><p>Обзор: предварительно обученные большие языковые модели</p></td></tr><tr><td colspan="1" rowspan="1"><p></p></td><td colspan="1" rowspan="1"><p></p></td><td colspan="1" rowspan="1"><p>Y. Yan, J. Su, J. He, F. Fu, X. Zheng, Y. Lyu, K. Wang, S. Wang, Q. Wen, X. Hu,</p></td><td colspan="1" rowspan="1"><p>A survey of mathematical reasoning in the era of multimodal large language model: Benchmark, method &amp; challenges</p></td><td colspan="1" rowspan="1"><p>2024</p></td><td colspan="1" rowspan="1"><p><a target="_blank" rel="noopener noreferrer nofollow" href="https://arxiv.org/abs/2412.11936">https://arxiv.org/abs/2412.11936</a></p></td><td colspan="1" rowspan="1"><p></p></td></tr><tr><td colspan="1" rowspan="1"><p></p></td><td colspan="1" rowspan="1"><p></p></td><td colspan="1" rowspan="1"><p>Yuhuai Wu, Markus Rabe, Wenda Li, Jimmy Ba, Roger Grosse, Christian Szegedy</p></td><td colspan="1" rowspan="1"><p>LIME: Learning Inductive Bias for Primitives of Mathematical Reasoning</p></td><td colspan="1" rowspan="1"><p>2021</p></td><td colspan="1" rowspan="1"><p><a target="_blank" rel="noopener noreferrer nofollow" href="https://arxiv.org/abs/2101.06223">https://arxiv.org/abs/2101.06223</a></p></td><td colspan="1" rowspan="1"><p>Понимание ИИ индукции, дедукции и абдукции</p></td></tr><tr><td colspan="1" rowspan="1"><p></p></td><td colspan="1" rowspan="1"><p></p></td><td colspan="1" rowspan="1"><p>Can Xu, Qingfeng Sun, Kai Zheng, Xiubo Geng, Pu Zhao, Jiazhan Feng, Chongyang Tao, Qingwei Lin, Daxin Jiang</p></td><td colspan="1" rowspan="1"><p>WizardLM: Empowering large pre-trained language models to follow complex instructions</p></td><td colspan="1" rowspan="1"><p>2025</p></td><td colspan="1" rowspan="1"><p><a target="_blank" rel="noopener noreferrer nofollow" href="https://arxiv.org/abs/2304.12244">https://arxiv.org/abs/2304.12244</a></p></td><td colspan="1" rowspan="1"><p><span style="color: rgb(15, 17, 21);">подход к созданию инструкций для LLM по простым</span></p></td></tr><tr><td colspan="1" rowspan="1"><p></p></td><td colspan="1" rowspan="1"><p></p></td><td colspan="1" rowspan="1"><p>Shai Shalev-Shwartz, Amnon Shashua</p></td><td colspan="1" rowspan="1"><p>From Reasoning to Super-Intelligence: A Search-Theoretic Perspective</p></td><td colspan="1" rowspan="1"><p>2025</p></td><td colspan="1" rowspan="1"><p><a target="_blank" rel="noopener noreferrer nofollow" href="https://arxiv.org/abs/2507.15865">https://arxiv.org/abs/2507.15865</a></p></td><td colspan="1" rowspan="1"><p>Diligent Learner</p></td></tr><tr><td colspan="1" rowspan="1"><p></p></td><td colspan="1" rowspan="1"><p></p></td><td colspan="1" rowspan="1"><p><span style="color: rgb(45, 55, 72);">Ben Prystawski, Michael Li, Noah Goodman</span></p></td><td colspan="1" rowspan="1"><p>Why think step by step? Reasoning emerges from the locality of experience</p></td><td colspan="1" rowspan="1"><p>2023</p></td><td colspan="1" rowspan="1"><p><a target="_blank" rel="noopener noreferrer nofollow" href="https://doi.org/10.52202/075280-3107">https://doi.org/10.52202/075280-3107</a></p></td><td colspan="1" rowspan="1"><p></p></td></tr><tr><td colspan="1" rowspan="1"><p></p></td><td colspan="1" rowspan="1"><p></p></td><td colspan="1" rowspan="1"><p>Tian Ye, Zicheng Xu ~Zicheng_Xu1 , Yuanzhi Li, Zeyuan Allen-Zhu</p></td><td colspan="1" rowspan="1"><p>Physics of Language Models: Part 2.1, Grade-School Math and the Hidden Reasoning Process</p></td><td colspan="1" rowspan="1"><p>2025</p></td><td colspan="1" rowspan="1"><p><a target="_blank" rel="noopener noreferrer nofollow" href="https://openreview.net/forum?id=Tn5B6Udq3E">https://openreview.net/forum?id=Tn5B6Udq3E</a></p></td><td colspan="1" rowspan="1"><p></p></td></tr><tr><td colspan="1" rowspan="1"><p></p></td><td colspan="1" rowspan="1"><p></p></td><td colspan="1" rowspan="1"><p></p></td><td colspan="1" rowspan="1"><p>NTCIR-11 Math-2 Task Overview</p></td><td colspan="1" rowspan="1"><p>2014</p></td><td colspan="1" rowspan="1"><p><a target="_blank" rel="noopener noreferrer nofollow" href="https://www.researchgate.net/publication/269574014_NTCIR-11_Math-2_Task_Overview">https://www.researchgate.net/publication/269574014_NTCIR-11_Math-2_Task_Overview</a></p></td><td colspan="1" rowspan="1"><p>?Достаточно старая работа по работе с формулами и тексту</p><p></p></td></tr><tr><td colspan="1" rowspan="1"><p></p></td><td colspan="1" rowspan="1"><p></p></td><td colspan="1" rowspan="1"><p></p></td><td colspan="1" rowspan="1"><p>Mathematical Information Retrieval: A Review</p></td><td colspan="1" rowspan="1"><p>2024</p></td><td colspan="1" rowspan="1"><p><a target="_blank" rel="noopener noreferrer nofollow" href="https://dl.acm.org/doi/epdf/10.1145/3699953">https://dl.acm.org/doi/epdf/10.1145/3699953</a></p></td><td colspan="1" rowspan="1"><p>Обзор по поиску формул</p></td></tr><tr><td colspan="1" rowspan="1"><p></p></td><td colspan="1" rowspan="1"><p></p></td><td colspan="1" rowspan="1"><p></p></td><td colspan="1" rowspan="1"><p>Evaluating NLP Embedding Models for Handling Science-Specific Symbolic Expressions in Student Texts</p></td><td colspan="1" rowspan="1"><p>2025</p></td><td colspan="1" rowspan="1"><p><a target="_blank" rel="noopener noreferrer nofollow" href="https://arxiv.org/abs/2505.17950">https://arxiv.org/abs/2505.17950</a></p></td><td colspan="1" rowspan="1"><p>Работа с символами, проблема понимание таких токенов</p></td></tr></tbody>
</table>

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