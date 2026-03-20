# The Algotrading Book: Machine Learning for Crypto Markets

> 🇬🇧 [Read in English](README.md)

Полный курс из 365 глав — одна глава в день на протяжении года — охватывающий весь спектр методов машинного обучения применительно к торговле криптовалютами. Все реализации используют **Bybit API** (REST + WebSocket) с примерами на **Python** и **Rust**.

---

## Структура

**365 глав · 23 тематических блока · 12 месяцев**

Каждая глава содержит:
- Теоретические основы с математическими выводами
- Реализацию на Python (Bybit API v5)
- Реализацию на Rust (tokio + reqwest)
- 3 практических торговых примера
- Фреймворк для бэктестинга
- Метрики оценки производительности
- Направления развития и список литературы

---

## Содержание

### Блок 1 — Основы и крипторынок (Главы 1–24)

| № | Глава |
|---|-------|
| 1 | [Алгоритмический интеллект: введение в ML для крипто](https://github.com/suenot/001-algorithmic-intelligence-intro/blob/main/README.ru.md) |
| 2 | [Конвейер данных крипторынка](https://github.com/suenot/002-crypto-market-data-pipeline/blob/main/README.ru.md) |
| 3 | [Нестандартные крипто-сигналы](https://github.com/suenot/003-unconventional-crypto-signals/blob/main/README.ru.md) |
| 4 | [Инженерия признаков для крипто](https://github.com/suenot/004-crypto-feature-engineering/blob/main/README.ru.md) |
| 5 | [Риск криптопортфеля](https://github.com/suenot/005-crypto-portfolio-risk/blob/main/README.ru.md) |
| 6 | [Обучение ML на финансовых данных](https://github.com/suenot/006-ml-training-financial-data/blob/main/README.ru.md) |
| 7 | [Линейные методы для крипто](https://github.com/suenot/007-linear-methods-crypto/blob/main/README.ru.md) |
| 8 | [Конвейер симуляции стратегий](https://github.com/suenot/008-strategy-simulation-pipeline/blob/main/README.ru.md) |
| 9 | [Временная динамика в крипто](https://github.com/suenot/009-temporal-dynamics-crypto/blob/main/README.ru.md) |
| 10 | [Байесовские крипто-стратегии](https://github.com/suenot/010-bayesian-crypto-strategies/blob/main/README.ru.md) |
| 11 | [Древесные модели для крипто](https://github.com/suenot/011-tree-models-crypto/blob/main/README.ru.md) |
| 12 | [Градиентный бустинг для крипто](https://github.com/suenot/012-gradient-boosting-crypto/blob/main/README.ru.md) |
| 13 | [Обнаружение структуры без учителя](https://github.com/suenot/013-unsupervised-crypto-structure/blob/main/README.ru.md) |
| 14 | [Обработка текстов крипторынка](https://github.com/suenot/014-crypto-text-processing/blob/main/README.ru.md) |
| 15 | [Тематическое моделирование для крипто](https://github.com/suenot/015-crypto-topic-modeling/blob/main/README.ru.md) |
| 16 | [Эмбеддинги для крипто](https://github.com/suenot/016-crypto-embeddings/blob/main/README.ru.md) |
| 17 | [Основы нейронных сетей для крипто](https://github.com/suenot/017-neural-net-foundations-crypto/blob/main/README.ru.md) |
| 18 | [CNN для паттернов крипто](https://github.com/suenot/018-cnn-crypto-patterns/blob/main/README.ru.md) |
| 19 | [RNN для последовательностей крипто](https://github.com/suenot/019-rnn-sequential-crypto/blob/main/README.ru.md) |
| 20 | [Автоэнкодеры для структуры крипто](https://github.com/suenot/020-autoencoders-crypto-structure/blob/main/README.ru.md) |
| 21 | [GAN для синтетических крипто-данных](https://github.com/suenot/021-gans-synthetic-crypto/blob/main/README.ru.md) |
| 22 | [RL агент для торговли крипто](https://github.com/suenot/022-rl-crypto-trading-agent/blob/main/README.ru.md) |
| 23 | [Производственное развёртывание на Bybit](https://github.com/suenot/023-production-deployment-bybit/blob/main/README.ru.md) |
| 24 | [Сборник крипто-сигналов](https://github.com/suenot/024-crypto-signal-compendium/blob/main/README.ru.md) |

---

### Блок 2 — Прикладные торговые стратегии (Главы 25–38)

| № | Глава |
|---|-------|
| 25 | [Обнаружение режимов рынка с HMM](https://github.com/suenot/025-regime-detection-hmm/blob/main/README.ru.md) |
| 26 | [Прогнозирование сюрпризов прибыли](https://github.com/suenot/026-earnings-surprise-prediction/blob/main/README.ru.md) |
| 27 | [Дисбаланс потока ордеров](https://github.com/suenot/027-order-flow-imbalance/blob/main/README.ru.md) |
| 28 | [Оптимальное исполнение с RL](https://github.com/suenot/028-optimal-execution-rl/blob/main/README.ru.md) |
| 29 | [Межрыночный моментум](https://github.com/suenot/029-cross-asset-momentum/blob/main/README.ru.md) |
| 30 | [Обнаружение аномалий](https://github.com/suenot/030-anomaly-detection/blob/main/README.ru.md) |
| 31 | [Онлайн-обучение и адаптивные стратегии](https://github.com/suenot/031-online-learning-adaptive/blob/main/README.ru.md) |
| 32 | [Мультиагентное обучение с подкреплением](https://github.com/suenot/032-multi-agent-rl/blob/main/README.ru.md) |
| 33 | [Арбитраж на крипто-DEX](https://github.com/suenot/033-crypto-dex-arbitrage/blob/main/README.ru.md) |
| 34 | [Слияние сентимента и моментума](https://github.com/suenot/034-sentiment-momentum-fusion/blob/main/README.ru.md) |
| 35 | [Статистический арбитраж и парная торговля](https://github.com/suenot/035-statistical-arbitrage-pairs/blob/main/README.ru.md) |
| 36 | [Конформное предсказание для трейдинга](https://github.com/suenot/036-conformal-prediction-trading/blob/main/README.ru.md) |
| 37 | [ML для греков опционов](https://github.com/suenot/037-options-ml-greeks/blob/main/README.ru.md) |
| 38 | [Реконструкция LOB с помощью ML](https://github.com/suenot/038-lob-reconstruction-ml/blob/main/README.ru.md) |

---

### Блок 3 — Механизмы внимания и трансформеры (Главы 39–58)

| № | Глава |
|---|-------|
| 39 | [Temporal Fusion Transformers](https://github.com/suenot/039-temporal-fusion-transformers/blob/main/README.ru.md) |
| 40 | [Трансформеры высшего порядка](https://github.com/suenot/040-higher-order-transformers/blob/main/README.ru.md) |
| 41 | [Stockformer: многомерное прогнозирование](https://github.com/suenot/041-stockformer-multivariate/blob/main/README.ru.md) |
| 42 | [Разреженное внимание Probsparse](https://github.com/suenot/042-probsparse-attention/blob/main/README.ru.md) |
| 43 | [Глубокий свёрточный трансформер](https://github.com/suenot/043-deep-convolutional-transformer/blob/main/README.ru.md) |
| 44 | [Сети временного внимания](https://github.com/suenot/044-temporal-attention-networks/blob/main/README.ru.md) |
| 45 | [Перекрёстное внимание для мультиактивов](https://github.com/suenot/045-cross-attention-multi-asset/blob/main/README.ru.md) |
| 46 | [Позиционное кодирование для временных рядов](https://github.com/suenot/046-positional-encoding-timeseries/blob/main/README.ru.md) |
| 47 | [Многомасштабное внимание](https://github.com/suenot/047-multi-scale-attention/blob/main/README.ru.md) |
| 48 | [Трансформеры с дополненной памятью](https://github.com/suenot/048-memory-augmented-transformers/blob/main/README.ru.md) |
| 49 | [Linformer для длинных последовательностей](https://github.com/suenot/049-linformer-long-sequences/blob/main/README.ru.md) |
| 50 | [Performer: эффективное внимание](https://github.com/suenot/050-performer-efficient-attention/blob/main/README.ru.md) |
| 51 | [BigBird: разреженное внимание](https://github.com/suenot/051-bigbird-sparse-attention/blob/main/README.ru.md) |
| 52 | [Reformer: LSH-внимание](https://github.com/suenot/052-reformer-lsh-attention/blob/main/README.ru.md) |
| 53 | [FNet: внимание через Фурье](https://github.com/suenot/053-fnet-fourier-transform/blob/main/README.ru.md) |
| 54 | [Nyströmformer для трейдинга](https://github.com/suenot/054-nystromformer-trading/blob/main/README.ru.md) |
| 55 | [Longformer для финансовых текстов](https://github.com/suenot/055-longformer-financial/blob/main/README.ru.md) |
| 56 | [Flash Attention для трейдинга](https://github.com/suenot/056-flash-attention-trading/blob/main/README.ru.md) |
| 57 | [Grouped Query Attention](https://github.com/suenot/057-grouped-query-attention/blob/main/README.ru.md) |
| 58 | [Оптимизация KV-кэша](https://github.com/suenot/058-kv-cache-optimization/blob/main/README.ru.md) |

---

### Блок 4 — Большие языковые модели (Главы 59–78)

| № | Глава |
|---|-------|
| 59 | [FinGPT: финансовая LLM](https://github.com/suenot/059-fingpt-financial-llm/blob/main/README.ru.md) |
| 60 | [BloombergGPT для трейдинга](https://github.com/suenot/060-bloomberggpt-trading/blob/main/README.ru.md) |
| 61 | [LLM для поиска альфы](https://github.com/suenot/061-llm-alpha-mining/blob/main/README.ru.md) |
| 62 | [Мультиагентная LLM-торговля](https://github.com/suenot/062-multi-agent-llm-trading/blob/main/README.ru.md) |
| 63 | [RAG для трейдинга](https://github.com/suenot/063-rag-for-trading/blob/main/README.ru.md) |
| 64 | [Цепочка рассуждений в трейдинге](https://github.com/suenot/064-chain-of-thought-trading/blob/main/README.ru.md) |
| 65 | [Анализ сентимента с LLM](https://github.com/suenot/065-llm-sentiment-analysis/blob/main/README.ru.md) |
| 66 | [LLM для интерпретации новостей](https://github.com/suenot/066-llm-news-interpretation/blob/main/README.ru.md) |
| 67 | [LLM для анализа звонков о прибыли](https://github.com/suenot/067-llm-earnings-call-analysis/blob/main/README.ru.md) |
| 68 | [Тонкая настройка LLM для финансов](https://github.com/suenot/068-fine-tuning-llm-finance/blob/main/README.ru.md) |
| 69 | [Инжиниринг промптов для трейдинга](https://github.com/suenot/069-prompt-engineering-trading/blob/main/README.ru.md) |
| 70 | [LLM для симуляции рынка](https://github.com/suenot/070-llm-market-simulation/blob/main/README.ru.md) |
| 71 | [LLM для оценки рисков](https://github.com/suenot/071-llm-risk-assessment/blob/main/README.ru.md) |
| 72 | [LLM для построения портфеля](https://github.com/suenot/072-llm-portfolio-construction/blob/main/README.ru.md) |
| 73 | [LLM для поиска факторов](https://github.com/suenot/073-llm-factor-discovery/blob/main/README.ru.md) |
| 74 | [LLM для обнаружения аномалий](https://github.com/suenot/074-llm-anomaly-detection/blob/main/README.ru.md) |
| 75 | [LLM для классификации режимов](https://github.com/suenot/075-llm-regime-classification/blob/main/README.ru.md) |
| 76 | [LLM для исполнения сделок](https://github.com/suenot/076-llm-trade-execution/blob/main/README.ru.md) |
| 77 | [LLM-ассистент бэктестинга](https://github.com/suenot/077-llm-backtesting-assistant/blob/main/README.ru.md) |
| 78 | [LLM для проверки соответствия](https://github.com/suenot/078-llm-compliance-check/blob/main/README.ru.md) |

---

### Блок 5 — NLP, BERT и предобучение (Главы 79–101)

| № | Глава |
|---|-------|
| 79 | [FinBERT для сентимента](https://github.com/suenot/079-finbert-sentiment/blob/main/README.ru.md) |
| 80 | [BERT для финансового NLP](https://github.com/suenot/080-bert-financial-nlp/blob/main/README.ru.md) |
| 81 | [RoBERTa для трейдинга](https://github.com/suenot/081-roberta-trading/blob/main/README.ru.md) |
| 82 | [XLNet для финансов](https://github.com/suenot/082-xlnet-finance/blob/main/README.ru.md) |
| 83 | [ALBERT для трейдинга](https://github.com/suenot/083-albert-trading/blob/main/README.ru.md) |
| 84 | [ELECTRA для финансов](https://github.com/suenot/084-electra-finance/blob/main/README.ru.md) |
| 85 | [DeBERTa для трейдинга](https://github.com/suenot/085-deberta-trading/blob/main/README.ru.md) |
| 86 | [Реферирование финансовых документов](https://github.com/suenot/086-financial-document-summarization/blob/main/README.ru.md) |
| 87 | [Кросс-языковой NLP для финансов](https://github.com/suenot/087-cross-lingual-finance-nlp/blob/main/README.ru.md) |
| 88 | [GPT для финансового анализа](https://github.com/suenot/088-gpt-financial-analysis/blob/main/README.ru.md) |
| 89 | [Распознавание именованных сущностей](https://github.com/suenot/089-named-entity-recognition-finance/blob/main/README.ru.md) |
| 90 | [Извлечение отношений для финансов](https://github.com/suenot/090-relation-extraction-finance/blob/main/README.ru.md) |
| 91 | [Классификация документов в финансах](https://github.com/suenot/091-document-classification-finance/blob/main/README.ru.md) |
| 92 | [Реферирование текстов в финансах](https://github.com/suenot/092-text-summarization-finance/blob/main/README.ru.md) |
| 93 | [Ответы на вопросы в финансах](https://github.com/suenot/093-question-answering-finance/blob/main/README.ru.md) |
| 94 | [Аспектный сентимент в финансах](https://github.com/suenot/094-aspect-sentiment-finance/blob/main/README.ru.md) |
| 95 | [Извлечение событий для трейдинга](https://github.com/suenot/095-event-extraction-trading/blob/main/README.ru.md) |
| 96 | [Временные рассуждения в финансах](https://github.com/suenot/096-temporal-reasoning-finance/blob/main/README.ru.md) |
| 97 | [Мультимодальный NLP для трейдинга](https://github.com/suenot/097-multimodal-nlp-trading/blob/main/README.ru.md) |
| 98 | [Граф знаний для трейдинга](https://github.com/suenot/098-knowledge-graph-trading/blob/main/README.ru.md) |
| 99 | [Доменно-адаптивное предобучение](https://github.com/suenot/099-domain-adaptive-pretraining/blob/main/README.ru.md) |
| 100 | [Инструкционная настройка для финансов](https://github.com/suenot/100-instruction-tuning-finance/blob/main/README.ru.md) |
| 101 | [T5 предобучение для финансов](https://github.com/suenot/101-t5-pretraining-finance/blob/main/README.ru.md) |

---

### Блок 6 — Мета-обучение (Главы 102–111)

| № | Глава |
|---|-------|
| 102 | [MAML для трейдинга](https://github.com/suenot/102-maml-for-trading/blob/main/README.ru.md) |
| 103 | [Алгоритм Reptile для трейдинга](https://github.com/suenot/103-reptile-algorithm-trading/blob/main/README.ru.md) |
| 104 | [Прототипные сети для финансов](https://github.com/suenot/104-prototypical-networks-finance/blob/main/README.ru.md) |
| 105 | [Сети сопоставления для финансов](https://github.com/suenot/105-matching-networks-finance/blob/main/README.ru.md) |
| 106 | [Zero-Shot трейдинг](https://github.com/suenot/106-zero-shot-trading/blob/main/README.ru.md) |
| 107 | [Few-Shot прогнозирование рынка](https://github.com/suenot/107-few-shot-market-prediction/blob/main/README.ru.md) |
| 108 | [Задачно-агностический трейдинг](https://github.com/suenot/108-task-agnostic-trading/blob/main/README.ru.md) |
| 109 | [Мета-RL для трейдинга](https://github.com/suenot/109-meta-rl-trading/blob/main/README.ru.md) |
| 110 | [Непрерывное мета-обучение](https://github.com/suenot/110-continual-meta-learning/blob/main/README.ru.md) |
| 111 | [Оптимизация мета-градиентов](https://github.com/suenot/111-meta-gradient-optimization/blob/main/README.ru.md) |

---

### Блок 7 — Трансферное обучение (Главы 112–116)

| № | Глава |
|---|-------|
| 112 | [Трансферное обучение для трейдинга](https://github.com/suenot/112-transfer-learning-trading/blob/main/README.ru.md) |
| 113 | [Доменная адаптация для финансов](https://github.com/suenot/113-domain-adaptation-finance/blob/main/README.ru.md) |
| 114 | [Многозадачное обучение для трейдинга](https://github.com/suenot/114-multi-task-learning-trading/blob/main/README.ru.md) |
| 115 | [QuantNet: трансфер для квантов](https://github.com/suenot/115-quantnet-transfer-trading/blob/main/README.ru.md) |
| 116 | [Мета-прогнозирование волатильности](https://github.com/suenot/116-meta-volatility-prediction/blob/main/README.ru.md) |

---

### Блок 8 — Причинный вывод (Главы 117–131)

| № | Глава |
|---|-------|
| 117 | [Причинность по Грэнджеру](https://github.com/suenot/117-granger-causality-trading/blob/main/README.ru.md) |
| 118 | [PCMCI: обнаружение причин](https://github.com/suenot/118-pcmci-causal-discovery/blob/main/README.ru.md) |
| 119 | [Трансферная энтропия для трейдинга](https://github.com/suenot/119-transfer-entropy-trading/blob/main/README.ru.md) |
| 120 | [VAR-LiNGAM для рынков](https://github.com/suenot/120-varlingam-markets/blob/main/README.ru.md) |
| 121 | [Обучение DAG для финансов](https://github.com/suenot/121-dag-learning-finance/blob/main/README.ru.md) |
| 122 | [Инструментальные переменные](https://github.com/suenot/122-instrumental-variables-trading/blob/main/README.ru.md) |
| 123 | [Double ML для трейдинга](https://github.com/suenot/123-double-ml-trading/blob/main/README.ru.md) |
| 124 | [Причинные леса для финансов](https://github.com/suenot/124-causal-forests-finance/blob/main/README.ru.md) |
| 125 | [Синтетический контроль](https://github.com/suenot/125-synthetic-control-trading/blob/main/README.ru.md) |
| 126 | [Разность разностей в трейдинге](https://github.com/suenot/126-diff-in-diff-trading/blob/main/README.ru.md) |
| 127 | [Регрессионный разрыв](https://github.com/suenot/127-regression-discontinuity/blob/main/README.ru.md) |
| 128 | [Оценка склонности в трейдинге](https://github.com/suenot/128-propensity-score-trading/blob/main/README.ru.md) |
| 129 | [Анализ медиации в финансах](https://github.com/suenot/129-mediation-analysis-finance/blob/main/README.ru.md) |
| 130 | [Обнаружение причинных факторов](https://github.com/suenot/130-causal-factor-discovery/blob/main/README.ru.md) |
| 131 | [Контрфактический трейдинг](https://github.com/suenot/131-counterfactual-trading/blob/main/README.ru.md) |

---

### Блок 9 — Интерпретируемость и объяснимость (Главы 132–146)

| № | Глава |
|---|-------|
| 132 | [SHAP для трейдинга](https://github.com/suenot/132-shap-trading-interpretability/blob/main/README.ru.md) |
| 133 | [LIME для трейдинга](https://github.com/suenot/133-lime-trading-explanation/blob/main/README.ru.md) |
| 134 | [Интегрированные градиенты для финансов](https://github.com/suenot/134-integrated-gradients-finance/blob/main/README.ru.md) |
| 135 | [Визуализация внимания в трейдинге](https://github.com/suenot/135-attention-visualization-trading/blob/main/README.ru.md) |
| 136 | [Атрибуция признаков в трейдинге](https://github.com/suenot/136-feature-attribution-trading/blob/main/README.ru.md) |
| 137 | [Контрфактические объяснения](https://github.com/suenot/137-counterfactual-explanations/blob/main/README.ru.md) |
| 138 | [Концептуальное бутылочное горлышко](https://github.com/suenot/138-concept-bottleneck-trading/blob/main/README.ru.md) |
| 139 | [Прототипное обучение для трейдинга](https://github.com/suenot/139-prototype-learning-trading/blob/main/README.ru.md) |
| 140 | [Извлечение правил для трейдинга](https://github.com/suenot/140-rule-extraction-trading/blob/main/README.ru.md) |
| 141 | [Карты значимости для трейдинга](https://github.com/suenot/141-saliency-maps-trading/blob/main/README.ru.md) |
| 142 | [Послойное распространение релевантности](https://github.com/suenot/142-layer-wise-relevance/blob/main/README.ru.md) |
| 143 | [DeepLIFT для трейдинга](https://github.com/suenot/143-deeplift-trading/blob/main/README.ru.md) |
| 144 | [GradCAM для финансов](https://github.com/suenot/144-gradcam-finance/blob/main/README.ru.md) |
| 145 | [Attention Rollout для трейдинга](https://github.com/suenot/145-attention-rollout-trading/blob/main/README.ru.md) |
| 146 | [Дистилляция в деревья решений](https://github.com/suenot/146-decision-tree-distillation/blob/main/README.ru.md) |

---

### Блок 10 — Модели пространства состояний и Mamba (Главы 147–161)

| № | Глава |
|---|-------|
| 147 | [Mamba для трейдинга](https://github.com/suenot/147-mamba-for-trading/blob/main/README.ru.md) |
| 148 | [S4: структурированное пространство состояний](https://github.com/suenot/148-s4-trading/blob/main/README.ru.md) |
| 149 | [Жидкие машины состояний](https://github.com/suenot/149-liquid-state-machines/blob/main/README.ru.md) |
| 150 | [MambaTS для временных рядов](https://github.com/suenot/150-mambats-time-series/blob/main/README.ru.md) |
| 151 | [Mamba4Cast: zero-shot прогнозирование](https://github.com/suenot/151-mamba4cast-zero-shot/blob/main/README.ru.md) |
| 152 | [C-Mamba: канальная корреляция](https://github.com/suenot/152-c-mamba-channel-correlation/blob/main/README.ru.md) |
| 153 | [TimeParticle SSM](https://github.com/suenot/153-timeparticle-ssm/blob/main/README.ru.md) |
| 154 | [Фреймворк HiPPO](https://github.com/suenot/154-hippo-framework/blob/main/README.ru.md) |
| 155 | [Линейное внимание SSM](https://github.com/suenot/155-linear-attention-ssm/blob/main/README.ru.md) |
| 156 | [Двунаправленная Mamba](https://github.com/suenot/156-bidirectional-mamba/blob/main/README.ru.md) |
| 157 | [Иерархическая SSM](https://github.com/suenot/157-hierarchical-ssm/blob/main/README.ru.md) |
| 158 | [Вентильная SSM](https://github.com/suenot/158-gated-ssm/blob/main/README.ru.md) |
| 159 | [Диагональная SSM](https://github.com/suenot/159-diagonal-ssm/blob/main/README.ru.md) |
| 160 | [Гибрид SSM-GNN](https://github.com/suenot/160-ssm-gnn-hybrid/blob/main/README.ru.md) |
| 161 | [Гибрид SSM-Transformer](https://github.com/suenot/161-ssm-transformer-hybrid/blob/main/README.ru.md) |

---

### Блок 11 — Физически информированные нейронные сети (Главы 162–176)

| № | Глава |
|---|-------|
| 162 | [PINN для модели Блэка-Шоулса](https://github.com/suenot/162-pinn-black-scholes/blob/main/README.ru.md) |
| 163 | [PINN для американских опционов](https://github.com/suenot/163-pinn-american-options/blob/main/README.ru.md) |
| 164 | [PINN для диффузии с прыжками](https://github.com/suenot/164-pinn-jump-diffusion/blob/main/README.ru.md) |
| 165 | [PINN для модели Хестона](https://github.com/suenot/165-pinn-heston-model/blob/main/README.ru.md) |
| 166 | [PINN для модели Халла-Уайта](https://github.com/suenot/166-pinn-hull-white-rates/blob/main/README.ru.md) |
| 167 | [PINN для модели CIR](https://github.com/suenot/167-pinn-cir-model/blob/main/README.ru.md) |
| 168 | [Нейронные СДУ для трейдинга](https://github.com/suenot/168-neural-sde-trading/blob/main/README.ru.md) |
| 169 | [Нейронные ОДУ для трейдинга](https://github.com/suenot/169-neural-ode-trading/blob/main/README.ru.md) |
| 170 | [Гамильтоновы нейронные сети](https://github.com/suenot/170-hamiltonian-nn-trading/blob/main/README.ru.md) |
| 171 | [Лагранжевы нейронные сети](https://github.com/suenot/171-lagrangian-nn-trading/blob/main/README.ru.md) |
| 172 | [Физически ограниченный GAN](https://github.com/suenot/172-physics-constrained-gan/blob/main/README.ru.md) |
| 173 | [Обучение операторов для финансов](https://github.com/suenot/173-operator-learning-finance/blob/main/README.ru.md) |
| 174 | [DeepONet для финансов](https://github.com/suenot/174-deeponet-finance/blob/main/README.ru.md) |
| 175 | [Нейронный оператор Фурье](https://github.com/suenot/175-fourier-neural-operator/blob/main/README.ru.md) |
| 176 | [Нейронные неявные представления](https://github.com/suenot/176-neural-implicit-finance/blob/main/README.ru.md) |

---

### Блок 12 — Генеративные модели: диффузия, VAE и потоки (Главы 177–196)

| № | Глава |
|---|-------|
| 177 | [Диффузионные модели для трейдинга](https://github.com/suenot/177-diffusion-models-for-trading/blob/main/README.ru.md) |
| 178 | [VAE факторная модель](https://github.com/suenot/178-vae-factor-model/blob/main/README.ru.md) |
| 179 | [Распутанный факторный VAE](https://github.com/suenot/179-disentangled-factor-vae/blob/main/README.ru.md) |
| 180 | [RVRAE: динамическая факторная модель](https://github.com/suenot/180-rvrae-dynamic-factor/blob/main/README.ru.md) |
| 181 | [Beta-VAE для трейдинга](https://github.com/suenot/181-beta-vae-trading/blob/main/README.ru.md) |
| 182 | [VQ-VAE для трейдинга](https://github.com/suenot/182-vq-vae-trading/blob/main/README.ru.md) |
| 183 | [Условный VAE для трейдинга](https://github.com/suenot/183-conditional-vae-trading/blob/main/README.ru.md) |
| 184 | [Иерархический VAE для трейдинга](https://github.com/suenot/184-hierarchical-vae-trading/blob/main/README.ru.md) |
| 185 | [Распутанный VAE для трейдинга](https://github.com/suenot/185-disentangled-vae-trading/blob/main/README.ru.md) |
| 186 | [VAE для генерации портфелей](https://github.com/suenot/186-vae-portfolio-generation/blob/main/README.ru.md) |
| 187 | [VAE для поверхности волатильности](https://github.com/suenot/187-vae-volatility-surface/blob/main/README.ru.md) |
| 188 | [Нормализующие потоки для финансов](https://github.com/suenot/188-normalizing-flows-finance/blob/main/README.ru.md) |
| 189 | [RealNVP для трейдинга](https://github.com/suenot/189-realnvp-trading/blob/main/README.ru.md) |
| 190 | [Glow для трейдинга](https://github.com/suenot/190-glow-trading/blob/main/README.ru.md) |
| 191 | [Нейронные сплайновые потоки](https://github.com/suenot/191-neural-spline-flows/blob/main/README.ru.md) |
| 192 | [Непрерывные нормализующие потоки](https://github.com/suenot/192-continuous-normalizing-flows/blob/main/README.ru.md) |
| 193 | [Согласование оценок для трейдинга](https://github.com/suenot/193-score-matching-trading/blob/main/README.ru.md) |
| 194 | [Энергетические модели](https://github.com/suenot/194-energy-based-models/blob/main/README.ru.md) |
| 195 | [Сети Хопфилда для трейдинга](https://github.com/suenot/195-hopfield-networks-trading/blob/main/README.ru.md) |
| 196 | [Ассоциативная память для трейдинга](https://github.com/suenot/196-associative-memory-trading/blob/main/README.ru.md) |

---

### Блок 13 — Контрастное и самообучение (Главы 197–218)

| № | Глава |
|---|-------|
| 197 | [SimCLR для акций](https://github.com/suenot/197-simclr-for-stocks/blob/main/README.ru.md) |
| 198 | [MoCo для трейдинга](https://github.com/suenot/198-moco-trading/blob/main/README.ru.md) |
| 199 | [BYOL для трейдинга](https://github.com/suenot/199-byol-trading/blob/main/README.ru.md) |
| 200 | [Barlow Twins для финансов](https://github.com/suenot/200-barlow-twins-finance/blob/main/README.ru.md) |
| 201 | [SwAV для трейдинга](https://github.com/suenot/201-swav-trading/blob/main/README.ru.md) |
| 202 | [VICReg для трейдинга](https://github.com/suenot/202-vicreg-trading/blob/main/README.ru.md) |
| 203 | [Триплетное обучение для акций](https://github.com/suenot/203-triplet-learning-stocks/blob/main/README.ru.md) |
| 204 | [Временное контрастное обучение](https://github.com/suenot/204-temporal-contrastive/blob/main/README.ru.md) |
| 205 | [Кросс-модальное контрастное обучение](https://github.com/suenot/205-cross-modal-contrastive/blob/main/README.ru.md) |
| 206 | [Майнинг трудных негативов](https://github.com/suenot/206-hard-negative-mining/blob/main/README.ru.md) |
| 207 | [Контрастное предиктивное кодирование](https://github.com/suenot/207-contrastive-predictive-coding/blob/main/README.ru.md) |
| 208 | [InfoNCE для трейдинга](https://github.com/suenot/208-infonce-trading/blob/main/README.ru.md) |
| 209 | [NT-Xent для трейдинга](https://github.com/suenot/209-nt-xent-trading/blob/main/README.ru.md) |
| 210 | [Supervised Contrastive Learning](https://github.com/suenot/210-supervised-contrastive/blob/main/README.ru.md) |
| 211 | [Proto-Contrastive Learning](https://github.com/suenot/211-proto-contrastive/blob/main/README.ru.md) |
| 212 | [Самообучение для трейдинга](https://github.com/suenot/212-self-supervised-trading/blob/main/README.ru.md) |
| 213 | [Masked Autoencoder для финансов](https://github.com/suenot/213-masked-autoencoder-finance/blob/main/README.ru.md) |
| 214 | [Self-Supervised для финансовых рядов](https://github.com/suenot/214-self-supervised-ts-finance/blob/main/README.ru.md) |
| 215 | [CLIP мультимодальный для трейдинга](https://github.com/suenot/215-clip-multimodal-trading/blob/main/README.ru.md) |
| 216 | [Аугментация данных для трейдинга](https://github.com/suenot/216-data-augmentation-trading/blob/main/README.ru.md) |
| 217 | [Обучение по учебной программе](https://github.com/suenot/217-curriculum-learning-trading/blob/main/README.ru.md) |
| 218 | [Активное обучение для трейдинга](https://github.com/suenot/218-active-learning-trading/blob/main/README.ru.md) |

---

### Блок 14 — Микроструктура рынка и стакан заявок (Главы 219–238)

| № | Глава |
|---|-------|
| 219 | [Глубокое обучение для LOB](https://github.com/suenot/219-lob-deep-learning/blob/main/README.ru.md) |
| 220 | [Маркет-мейкинг с ML](https://github.com/suenot/220-market-making-ml/blob/main/README.ru.md) |
| 221 | [Прогнозирование потока ордеров](https://github.com/suenot/221-order-flow-prediction/blob/main/README.ru.md) |
| 222 | [Моделирование ценового воздействия](https://github.com/suenot/222-price-impact-modeling/blob/main/README.ru.md) |
| 223 | [Прогнозирование тиковых данных](https://github.com/suenot/223-tick-data-forecasting/blob/main/README.ru.md) |
| 224 | [Классификация сделок](https://github.com/suenot/224-trade-classification/blob/main/README.ru.md) |
| 225 | [Предсказание обновлений котировок](https://github.com/suenot/225-quote-update-prediction/blob/main/README.ru.md) |
| 226 | [ML-моделирование спреда](https://github.com/suenot/226-spread-modeling-ml/blob/main/README.ru.md) |
| 227 | [Прогнозирование ликвидности](https://github.com/suenot/227-liquidity-prediction/blob/main/README.ru.md) |
| 228 | [Признаки микроструктуры](https://github.com/suenot/228-microstructure-features/blob/main/README.ru.md) |
| 229 | [DeepLOB: прогнозирование](https://github.com/suenot/229-deeplob-forecasting/blob/main/README.ru.md) |
| 230 | [LOBFrame: бенчмарк](https://github.com/suenot/230-lobframe-benchmark/blob/main/README.ru.md) |
| 231 | [LIT Transformer для LOB](https://github.com/suenot/231-lit-transformer-lob/blob/main/README.ru.md) |
| 232 | [CNN для предсказания LOB](https://github.com/suenot/232-cnn-lob-prediction/blob/main/README.ru.md) |
| 233 | [LSTM для прогнозирования LOB](https://github.com/suenot/233-lstm-lob-forecasting/blob/main/README.ru.md) |
| 234 | [Внимание для LOB](https://github.com/suenot/234-attention-lob/blob/main/README.ru.md) |
| 235 | [GNN для LOB](https://github.com/suenot/235-gnn-lob/blob/main/README.ru.md) |
| 236 | [Вариационный LOB](https://github.com/suenot/236-variational-lob/blob/main/README.ru.md) |
| 237 | [Генеративный LOB](https://github.com/suenot/237-generative-lob/blob/main/README.ru.md) |
| 238 | [RL для LOB](https://github.com/suenot/238-reinforcement-lob/blob/main/README.ru.md) |

---

### Блок 15 — Обучение с подкреплением (Главы 239–268)

| № | Глава |
|---|-------|
| 239 | [TD3 для портфеля](https://github.com/suenot/239-td3-portfolio/blob/main/README.ru.md) |
| 240 | [SAC для трейдинга](https://github.com/suenot/240-sac-trading/blob/main/README.ru.md) |
| 241 | [PPO для портфеля](https://github.com/suenot/241-ppo-portfolio/blob/main/README.ru.md) |
| 242 | [A2C для трейдинга](https://github.com/suenot/242-a2c-trading/blob/main/README.ru.md) |
| 243 | [DDPG для трейдинга](https://github.com/suenot/243-ddpg-trading/blob/main/README.ru.md) |
| 244 | [DQN для портфеля](https://github.com/suenot/244-dqn-portfolio/blob/main/README.ru.md) |
| 245 | [Rainbow DQN для трейдинга](https://github.com/suenot/245-rainbow-dqn-trading/blob/main/README.ru.md) |
| 246 | [C51: дистрибуционный RL](https://github.com/suenot/246-c51-distributional-rl/blob/main/README.ru.md) |
| 247 | [IQN: неявные квантильные сети](https://github.com/suenot/247-iqn-implicit-quantile/blob/main/README.ru.md) |
| 248 | [Иерархический RL для трейдинга](https://github.com/suenot/248-hierarchical-rl-trading/blob/main/README.ru.md) |
| 249 | [Модельно-ориентированный RL](https://github.com/suenot/249-model-based-rl-trading/blob/main/README.ru.md) |
| 250 | [World Models для трейдинга](https://github.com/suenot/250-world-models-trading/blob/main/README.ru.md) |
| 251 | [Dreamer для трейдинга](https://github.com/suenot/251-dreamer-trading/blob/main/README.ru.md) |
| 252 | [MuZero для трейдинга](https://github.com/suenot/252-muzero-trading/blob/main/README.ru.md) |
| 253 | [Обратный RL для трейдинга](https://github.com/suenot/253-inverse-rl-trading/blob/main/README.ru.md) |
| 254 | [Имитационное обучение](https://github.com/suenot/254-imitation-learning-trading/blob/main/README.ru.md) |
| 255 | [Поведенческое клонирование](https://github.com/suenot/255-behavioral-cloning-trading/blob/main/README.ru.md) |
| 256 | [GAIL для трейдинга](https://github.com/suenot/256-gail-trading/blob/main/README.ru.md) |
| 257 | [Формирование вознаграждения](https://github.com/suenot/257-reward-shaping-trading/blob/main/README.ru.md) |
| 258 | [Трейдинг на основе любопытства](https://github.com/suenot/258-curiosity-driven-trading/blob/main/README.ru.md) |
| 259 | [Поиск Монте-Карло по дереву](https://github.com/suenot/259-monte-carlo-tree-search/blob/main/README.ru.md) |
| 260 | [Планирование в RL для трейдинга](https://github.com/suenot/260-planning-rl-trading/blob/main/README.ru.md) |
| 261 | [Офлайн-RL для трейдинга](https://github.com/suenot/261-offline-rl-trading/blob/main/README.ru.md) |
| 262 | [Conservative Q-Learning](https://github.com/suenot/262-conservative-q-learning/blob/main/README.ru.md) |
| 263 | [Decision Transformer](https://github.com/suenot/263-decision-transformer/blob/main/README.ru.md) |
| 264 | [Trajectory Transformer](https://github.com/suenot/264-trajectory-transformer/blob/main/README.ru.md) |
| 265 | [RL с целевым условием](https://github.com/suenot/265-goal-conditioned-rl/blob/main/README.ru.md) |
| 266 | [Фреймворк опций для RL](https://github.com/suenot/266-option-framework-rl/blob/main/README.ru.md) |
| 267 | [Обучение на основе популяции](https://github.com/suenot/267-population-based-training/blob/main/README.ru.md) |
| 268 | [Многоцелевой RL для трейдинга](https://github.com/suenot/268-multi-objective-rl-trading/blob/main/README.ru.md) |

---

### Блок 16 — Квантификация неопределённости и байесовские методы (Главы 269–279)

| № | Глава |
|---|-------|
| 269 | [Байесовская оптимизация для трейдинга](https://github.com/suenot/269-bayesian-optimization-trading/blob/main/README.ru.md) |
| 270 | [Гауссовский процесс для трейдинга](https://github.com/suenot/270-gaussian-process-trading/blob/main/README.ru.md) |
| 271 | [Квантификация неопределённости](https://github.com/suenot/271-uncertainty-quantification/blob/main/README.ru.md) |
| 272 | [Неопределённость ансамблей](https://github.com/suenot/272-ensemble-uncertainty/blob/main/README.ru.md) |
| 273 | [MC Dropout для трейдинга](https://github.com/suenot/273-mc-dropout-trading/blob/main/README.ru.md) |
| 274 | [Глубокие ансамбли для трейдинга](https://github.com/suenot/274-deep-ensembles-trading/blob/main/README.ru.md) |
| 275 | [Байесовские нейронные сети](https://github.com/suenot/275-bayesian-neural-network/blob/main/README.ru.md) |
| 276 | [Вариационный вывод для трейдинга](https://github.com/suenot/276-variational-inference-trading/blob/main/README.ru.md) |
| 277 | [Вероятностное прогнозирование](https://github.com/suenot/277-probabilistic-forecasting/blob/main/README.ru.md) |
| 278 | [Интервалы предсказания для трейдинга](https://github.com/suenot/278-prediction-intervals-trading/blob/main/README.ru.md) |
| 279 | [Копульные модели для финансов](https://github.com/suenot/279-copula-models-finance/blob/main/README.ru.md) |

---

### Блок 17 — Графовые нейронные сети (Главы 280–290)

| № | Глава |
|---|-------|
| 280 | [Графовые нейронные сети для трейдинга](https://github.com/suenot/280-graph-neural-networks/blob/main/README.ru.md) |
| 281 | [Graph Transformer для трейдинга](https://github.com/suenot/281-graph-transformer-trading/blob/main/README.ru.md) |
| 282 | [Эквивариантная GNN для трейдинга](https://github.com/suenot/282-equivariant-gnn-trading/blob/main/README.ru.md) |
| 283 | [Передача сообщений для трейдинга](https://github.com/suenot/283-message-passing-trading/blob/main/README.ru.md) |
| 284 | [Graph Attention для трейдинга](https://github.com/suenot/284-graph-attention-trading/blob/main/README.ru.md) |
| 285 | [Гетерогенная GNN для трейдинга](https://github.com/suenot/285-heterogeneous-gnn-trading/blob/main/README.ru.md) |
| 286 | [Временная GNN для трейдинга](https://github.com/suenot/286-temporal-gnn-trading/blob/main/README.ru.md) |
| 287 | [Динамическая GNN для трейдинга](https://github.com/suenot/287-dynamic-gnn-trading/blob/main/README.ru.md) |
| 288 | [Генерация графов для трейдинга](https://github.com/suenot/288-graph-generation-trading/blob/main/README.ru.md) |
| 289 | [Пулинг графов для трейдинга](https://github.com/suenot/289-graph-pooling-trading/blob/main/README.ru.md) |
| 290 | [Майнинг подграфов для трейдинга](https://github.com/suenot/290-subgraph-mining-trading/blob/main/README.ru.md) |

---

### Блок 18 — CNN и свёрточные модели временных рядов (Главы 291–300)

| № | Глава |
|---|-------|
| 291 | [WaveNet для трейдинга](https://github.com/suenot/291-wavenet-trading/blob/main/README.ru.md) |
| 292 | [TCN: временная свёрточная сеть](https://github.com/suenot/292-tcn-trading/blob/main/README.ru.md) |
| 293 | [Дилатированные свёртки для трейдинга](https://github.com/suenot/293-dilated-convolutions-trading/blob/main/README.ru.md) |
| 294 | [InceptionTime для трейдинга](https://github.com/suenot/294-inception-time-trading/blob/main/README.ru.md) |
| 295 | [ResNet для временных рядов](https://github.com/suenot/295-resnet-timeseries/blob/main/README.ru.md) |
| 296 | [DenseNet для трейдинга](https://github.com/suenot/296-densenet-trading/blob/main/README.ru.md) |
| 297 | [EfficientNet для трейдинга](https://github.com/suenot/297-efficientnet-trading/blob/main/README.ru.md) |
| 298 | [ConvNeXt для трейдинга](https://github.com/suenot/298-convnext-trading/blob/main/README.ru.md) |
| 299 | [Поканальные разделимые свёртки](https://github.com/suenot/299-depthwise-separable-trading/blob/main/README.ru.md) |
| 300 | [Squeeze-and-Excitation сети](https://github.com/suenot/300-squeeze-excitation-trading/blob/main/README.ru.md) |

---

### Блок 19 — Федеративное обучение (Главы 301–315)

| № | Глава |
|---|-------|
| 301 | [FedAvg для трейдинга](https://github.com/suenot/301-fedavg-trading/blob/main/README.ru.md) |
| 302 | [FedProx для финансов](https://github.com/suenot/302-fedprox-finance/blob/main/README.ru.md) |
| 303 | [Безопасная агрегация для трейдинга](https://github.com/suenot/303-secure-aggregation-trading/blob/main/README.ru.md) |
| 304 | [Дифференциальная приватность](https://github.com/suenot/304-differential-privacy-trading/blob/main/README.ru.md) |
| 305 | [Блокчейн-FL для трейдинга](https://github.com/suenot/305-blockchain-fl-trading/blob/main/README.ru.md) |
| 306 | [Персонализированный FL](https://github.com/suenot/306-personalized-fl-trading/blob/main/README.ru.md) |
| 307 | [Иерархический FL для трейдинга](https://github.com/suenot/307-hierarchical-fl-trading/blob/main/README.ru.md) |
| 308 | [Асинхронный FL для трейдинга](https://github.com/suenot/308-asynchronous-fl-trading/blob/main/README.ru.md) |
| 309 | [Коммуникационно-эффективный FL](https://github.com/suenot/309-communication-efficient-fl/blob/main/README.ru.md) |
| 310 | [Компрессия градиентов в FL](https://github.com/suenot/310-fl-gradient-compression/blob/main/README.ru.md) |
| 311 | [Византийски-устойчивый FL](https://github.com/suenot/311-byzantine-robust-fl/blob/main/README.ru.md) |
| 312 | [Честный FL для трейдинга](https://github.com/suenot/312-fair-fl-trading/blob/main/README.ru.md) |
| 313 | [Дистилляция знаний в FL](https://github.com/suenot/313-knowledge-distillation-fl/blob/main/README.ru.md) |
| 314 | [FL через сайлосы в трейдинге](https://github.com/suenot/314-fl-cross-silo-trading/blob/main/README.ru.md) |
| 315 | [FL на граничных устройствах](https://github.com/suenot/315-fl-edge-trading/blob/main/README.ru.md) |

---

### Блок 20 — Квантовые вычисления (Главы 316–330)

| № | Глава |
|---|-------|
| 316 | [VQE для оптимизации портфеля](https://github.com/suenot/316-vqe-portfolio-optimization/blob/main/README.ru.md) |
| 317 | [QAOA для трейдинга](https://github.com/suenot/317-qaoa-trading/blob/main/README.ru.md) |
| 318 | [Квантовый GAN для финансов](https://github.com/suenot/318-quantum-gan-finance/blob/main/README.ru.md) |
| 319 | [Квантовое ядро для трейдинга](https://github.com/suenot/319-quantum-kernel-trading/blob/main/README.ru.md) |
| 320 | [Квантовая SVM для трейдинга](https://github.com/suenot/320-quantum-svm-trading/blob/main/README.ru.md) |
| 321 | [Вариационный квантовый классификатор](https://github.com/suenot/321-variational-quantum-classifier/blob/main/README.ru.md) |
| 322 | [Квантовая машина Больцмана](https://github.com/suenot/322-quantum-boltzmann-trading/blob/main/README.ru.md) |
| 323 | [Алгоритм Гровера для трейдинга](https://github.com/suenot/323-grover-search-trading/blob/main/README.ru.md) |
| 324 | [Алгоритм HHL для финансов](https://github.com/suenot/324-hhl-algorithm-finance/blob/main/README.ru.md) |
| 325 | [Квантовая карта признаков](https://github.com/suenot/325-quantum-feature-map/blob/main/README.ru.md) |
| 326 | [Квантовая коррекция ошибок](https://github.com/suenot/326-quantum-error-correction/blob/main/README.ru.md) |
| 327 | [Гибридные квантово-классические системы](https://github.com/suenot/327-hybrid-quantum-classical/blob/main/README.ru.md) |
| 328 | [NISQ-алгоритмы для трейдинга](https://github.com/suenot/328-nisq-trading-algorithms/blob/main/README.ru.md) |
| 329 | [Квантовый отжиг для трейдинга](https://github.com/suenot/329-quantum-annealing-trading/blob/main/README.ru.md) |
| 330 | [Тензорные сети для трейдинга](https://github.com/suenot/330-tensor-network-trading/blob/main/README.ru.md) |

---

### Блок 21 — Эффективность моделей: дистилляция и NAS (Главы 331–350)

| № | Глава |
|---|-------|
| 331 | [Дистилляция знаний для трейдинга](https://github.com/suenot/331-knowledge-distillation-trading/blob/main/README.ru.md) |
| 332 | [Компрессия моделей для финансов](https://github.com/suenot/332-model-compression-finance/blob/main/README.ru.md) |
| 333 | [Прунинг торговых моделей](https://github.com/suenot/333-pruning-trading-models/blob/main/README.ru.md) |
| 334 | [Квантизация торговых моделей](https://github.com/suenot/334-quantization-trading-models/blob/main/README.ru.md) |
| 335 | [Гипотеза лотерейного билета](https://github.com/suenot/335-lottery-ticket-trading/blob/main/README.ru.md) |
| 336 | [Самодистилляция для трейдинга](https://github.com/suenot/336-self-distillation-trading/blob/main/README.ru.md) |
| 337 | [Учитель-ученик для трейдинга](https://github.com/suenot/337-teacher-student-trading/blob/main/README.ru.md) |
| 338 | [Прогрессивная дистилляция](https://github.com/suenot/338-progressive-distillation/blob/main/README.ru.md) |
| 339 | [Дистилляция данных для трейдинга](https://github.com/suenot/339-data-distillation-trading/blob/main/README.ru.md) |
| 340 | [Дистилляция признаков](https://github.com/suenot/340-feature-distillation/blob/main/README.ru.md) |
| 341 | [NAS для трейдинга](https://github.com/suenot/341-nas-for-trading/blob/main/README.ru.md) |
| 342 | [AutoML для финансов](https://github.com/suenot/342-automl-finance/blob/main/README.ru.md) |
| 343 | [Оптимизация гиперпараметров](https://github.com/suenot/343-hyperparameter-optimization/blob/main/README.ru.md) |
| 344 | [Эволюционный NAS для трейдинга](https://github.com/suenot/344-evolutionary-nas-trading/blob/main/README.ru.md) |
| 345 | [Дифференцируемый NAS](https://github.com/suenot/345-differentiable-nas/blob/main/README.ru.md) |
| 346 | [One-Shot NAS](https://github.com/suenot/346-one-shot-nas/blob/main/README.ru.md) |
| 347 | [Аппаратно-ориентированный NAS](https://github.com/suenot/347-hardware-aware-nas/blob/main/README.ru.md) |
| 348 | [Многоцелевой NAS](https://github.com/suenot/348-multi-objective-nas/blob/main/README.ru.md) |
| 349 | [DARTS для трейдинга](https://github.com/suenot/349-darts-trading/blob/main/README.ru.md) |
| 350 | [EXAMM для трейдинга](https://github.com/suenot/350-examm-trading/blob/main/README.ru.md) |

---

### Блок 22 — Устойчивость к атакам (Главы 351–360)

| № | Глава |
|---|-------|
| 351 | [Состязательное обучение для трейдинга](https://github.com/suenot/351-adversarial-training-trading/blob/main/README.ru.md) |
| 352 | [Обнаружение состязательных атак](https://github.com/suenot/352-adversarial-attack-detection/blob/main/README.ru.md) |
| 353 | [Устойчивые торговые модели](https://github.com/suenot/353-robust-trading-models/blob/main/README.ru.md) |
| 354 | [Защита от возмущений входа](https://github.com/suenot/354-input-perturbation-defense/blob/main/README.ru.md) |
| 355 | [Сертифицированная устойчивость](https://github.com/suenot/355-certified-robustness/blob/main/README.ru.md) |
| 356 | [Состязательные примеры в финансах](https://github.com/suenot/356-adversarial-examples-finance/blob/main/README.ru.md) |
| 357 | [Атаки уклонения для трейдинга](https://github.com/suenot/357-evasion-attacks-trading/blob/main/README.ru.md) |
| 358 | [Атаки отравления для трейдинга](https://github.com/suenot/358-poisoning-attacks-trading/blob/main/README.ru.md) |
| 359 | [Инверсия модели в финансах](https://github.com/suenot/359-model-inversion-finance/blob/main/README.ru.md) |
| 360 | [Атаки принадлежности](https://github.com/suenot/360-membership-inference/blob/main/README.ru.md) |

---

### Блок 23 — Передовые методы (Главы 361–365)

| № | Глава |
|---|-------|
| 361 | [Оператор Купмана для трейдинга](https://github.com/suenot/361-koopman-operator-trading/blob/main/README.ru.md) |
| 362 | [Резервуарные вычисления для трейдинга](https://github.com/suenot/362-reservoir-computing-trading/blob/main/README.ru.md) |
| 363 | [Жидкие нейронные сети для трейдинга](https://github.com/suenot/363-liquid-neural-networks-trading/blob/main/README.ru.md) |
| 364 | [Нейроморфный трейдинг](https://github.com/suenot/364-neuromorphic-trading/blob/main/README.ru.md) |
| 365 | [Фундаментальные модели для трейдинга: следующий рубеж](https://github.com/suenot/365-foundation-models-trading/blob/main/README.ru.md) |

---

## Быстрый навигатор

| Блок | Главы | Тема |
|------|-------|------|
| 1 | 1–24 | Основы и крипторынок |
| 2 | 25–38 | Прикладные торговые стратегии |
| 3 | 39–58 | Attention и Transformers |
| 4 | 59–78 | Большие языковые модели |
| 5 | 79–101 | NLP, BERT и предобучение |
| 6 | 102–111 | Мета-обучение |
| 7 | 112–116 | Трансферное обучение |
| 8 | 117–131 | Причинный вывод |
| 9 | 132–146 | Интерпретируемость |
| 10 | 147–161 | Модели пространства состояний (Mamba) |
| 11 | 162–176 | Физически информированные НС |
| 12 | 177–196 | Генеративные модели |
| 13 | 197–218 | Контрастное и самообучение |
| 14 | 219–238 | Микроструктура рынка и LOB |
| 15 | 239–268 | Обучение с подкреплением |
| 16 | 269–279 | Неопределённость и байесовские методы |
| 17 | 280–290 | Графовые нейронные сети |
| 18 | 291–300 | CNN для временных рядов |
| 19 | 301–315 | Федеративное обучение |
| 20 | 316–330 | Квантовые вычисления |
| 21 | 331–350 | Эффективность моделей |
| 22 | 351–360 | Устойчивость к атакам |
| 23 | 361–365 | Передовые методы |

---

## Технологический стек

- **Биржа**: Bybit API v5 (REST + WebSocket)
- **Python**: PyTorch, scikit-learn, pandas, numpy
- **Rust**: tokio, reqwest, serde
- **Данные**: OHLCV, снимки стакана заявок, поток сделок, ставки финансирования

---

*365 глав · 1 год · Машинное обучение для крипторынков*
