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
| 1 | [Алгоритмический интеллект: введение в ML для крипто](chapters/001_algorithmic_intelligence_intro/) |
| 2 | [Конвейер данных крипторынка](chapters/002_crypto_market_data_pipeline/) |
| 3 | [Нестандартные крипто-сигналы](chapters/003_unconventional_crypto_signals/) |
| 4 | [Инженерия признаков для крипто](chapters/004_crypto_feature_engineering/) |
| 5 | [Риск криптопортфеля](chapters/005_crypto_portfolio_risk/) |
| 6 | [Обучение ML на финансовых данных](chapters/006_ml_training_financial_data/) |
| 7 | [Линейные методы для крипто](chapters/007_linear_methods_crypto/) |
| 8 | [Конвейер симуляции стратегий](chapters/008_strategy_simulation_pipeline/) |
| 9 | [Временная динамика в крипто](chapters/009_temporal_dynamics_crypto/) |
| 10 | [Байесовские крипто-стратегии](chapters/010_bayesian_crypto_strategies/) |
| 11 | [Древесные модели для крипто](chapters/011_tree_models_crypto/) |
| 12 | [Градиентный бустинг для крипто](chapters/012_gradient_boosting_crypto/) |
| 13 | [Обнаружение структуры без учителя](chapters/013_unsupervised_crypto_structure/) |
| 14 | [Обработка текстов крипторынка](chapters/014_crypto_text_processing/) |
| 15 | [Тематическое моделирование для крипто](chapters/015_crypto_topic_modeling/) |
| 16 | [Эмбеддинги для крипто](chapters/016_crypto_embeddings/) |
| 17 | [Основы нейронных сетей для крипто](chapters/017_neural_net_foundations_crypto/) |
| 18 | [CNN для паттернов крипто](chapters/018_cnn_crypto_patterns/) |
| 19 | [RNN для последовательностей крипто](chapters/019_rnn_sequential_crypto/) |
| 20 | [Автоэнкодеры для структуры крипто](chapters/020_autoencoders_crypto_structure/) |
| 21 | [GAN для синтетических крипто-данных](chapters/021_gans_synthetic_crypto/) |
| 22 | [RL агент для торговли крипто](chapters/022_rl_crypto_trading_agent/) |
| 23 | [Производственное развёртывание на Bybit](chapters/023_production_deployment_bybit/) |
| 24 | [Сборник крипто-сигналов](chapters/024_crypto_signal_compendium/) |

---

### Блок 2 — Прикладные торговые стратегии (Главы 25–38)

| № | Глава |
|---|-------|
| 25 | [Обнаружение режимов рынка с HMM](chapters/025_regime_detection_hmm/) |
| 26 | [Прогнозирование сюрпризов прибыли](chapters/026_earnings_surprise_prediction/) |
| 27 | [Дисбаланс потока ордеров](chapters/027_order_flow_imbalance/) |
| 28 | [Оптимальное исполнение с RL](chapters/028_optimal_execution_rl/) |
| 29 | [Межрыночный моментум](chapters/029_cross_asset_momentum/) |
| 30 | [Обнаружение аномалий](chapters/030_anomaly_detection/) |
| 31 | [Онлайн-обучение и адаптивные стратегии](chapters/031_online_learning_adaptive/) |
| 32 | [Мультиагентное обучение с подкреплением](chapters/032_multi_agent_rl/) |
| 33 | [Арбитраж на крипто-DEX](chapters/033_crypto_dex_arbitrage/) |
| 34 | [Слияние сентимента и моментума](chapters/034_sentiment_momentum_fusion/) |
| 35 | [Статистический арбитраж и парная торговля](chapters/035_statistical_arbitrage_pairs/) |
| 36 | [Конформное предсказание для трейдинга](chapters/036_conformal_prediction_trading/) |
| 37 | [ML для греков опционов](chapters/037_options_ml_greeks/) |
| 38 | [Реконструкция LOB с помощью ML](chapters/038_lob_reconstruction_ml/) |

---

### Блок 3 — Механизмы внимания и трансформеры (Главы 39–58)

| № | Глава |
|---|-------|
| 39 | [Temporal Fusion Transformers](chapters/039_temporal_fusion_transformers/) |
| 40 | [Трансформеры высшего порядка](chapters/040_higher_order_transformers/) |
| 41 | [Stockformer: многомерное прогнозирование](chapters/041_stockformer_multivariate/) |
| 42 | [Разреженное внимание Probsparse](chapters/042_probsparse_attention/) |
| 43 | [Глубокий свёрточный трансформер](chapters/043_deep_convolutional_transformer/) |
| 44 | [Сети временного внимания](chapters/044_temporal_attention_networks/) |
| 45 | [Перекрёстное внимание для мультиактивов](chapters/045_cross_attention_multi_asset/) |
| 46 | [Позиционное кодирование для временных рядов](chapters/046_positional_encoding_timeseries/) |
| 47 | [Многомасштабное внимание](chapters/047_multi_scale_attention/) |
| 48 | [Трансформеры с дополненной памятью](chapters/048_memory_augmented_transformers/) |
| 49 | [Linformer для длинных последовательностей](chapters/049_linformer_long_sequences/) |
| 50 | [Performer: эффективное внимание](chapters/050_performer_efficient_attention/) |
| 51 | [BigBird: разреженное внимание](chapters/051_bigbird_sparse_attention/) |
| 52 | [Reformer: LSH-внимание](chapters/052_reformer_lsh_attention/) |
| 53 | [FNet: внимание через Фурье](chapters/053_fnet_fourier_transform/) |
| 54 | [Nyströmformer для трейдинга](chapters/054_nystromformer_trading/) |
| 55 | [Longformer для финансовых текстов](chapters/055_longformer_financial/) |
| 56 | [Flash Attention для трейдинга](chapters/056_flash_attention_trading/) |
| 57 | [Grouped Query Attention](chapters/057_grouped_query_attention/) |
| 58 | [Оптимизация KV-кэша](chapters/058_kv_cache_optimization/) |

---

### Блок 4 — Большие языковые модели (Главы 59–78)

| № | Глава |
|---|-------|
| 59 | [FinGPT: финансовая LLM](chapters/059_fingpt_financial_llm/) |
| 60 | [BloombergGPT для трейдинга](chapters/060_bloomberggpt_trading/) |
| 61 | [LLM для поиска альфы](chapters/061_llm_alpha_mining/) |
| 62 | [Мультиагентная LLM-торговля](chapters/062_multi_agent_llm_trading/) |
| 63 | [RAG для трейдинга](chapters/063_rag_for_trading/) |
| 64 | [Цепочка рассуждений в трейдинге](chapters/064_chain_of_thought_trading/) |
| 65 | [Анализ сентимента с LLM](chapters/065_llm_sentiment_analysis/) |
| 66 | [LLM для интерпретации новостей](chapters/066_llm_news_interpretation/) |
| 67 | [LLM для анализа звонков о прибыли](chapters/067_llm_earnings_call_analysis/) |
| 68 | [Тонкая настройка LLM для финансов](chapters/068_fine_tuning_llm_finance/) |
| 69 | [Инжиниринг промптов для трейдинга](chapters/069_prompt_engineering_trading/) |
| 70 | [LLM для симуляции рынка](chapters/070_llm_market_simulation/) |
| 71 | [LLM для оценки рисков](chapters/071_llm_risk_assessment/) |
| 72 | [LLM для построения портфеля](chapters/072_llm_portfolio_construction/) |
| 73 | [LLM для поиска факторов](chapters/073_llm_factor_discovery/) |
| 74 | [LLM для обнаружения аномалий](chapters/074_llm_anomaly_detection/) |
| 75 | [LLM для классификации режимов](chapters/075_llm_regime_classification/) |
| 76 | [LLM для исполнения сделок](chapters/076_llm_trade_execution/) |
| 77 | [LLM-ассистент бэктестинга](chapters/077_llm_backtesting_assistant/) |
| 78 | [LLM для проверки соответствия](chapters/078_llm_compliance_check/) |

---

### Блок 5 — NLP, BERT и предобучение (Главы 79–101)

| № | Глава |
|---|-------|
| 79 | [FinBERT для сентимента](chapters/079_finbert_sentiment/) |
| 80 | [BERT для финансового NLP](chapters/080_bert_financial_nlp/) |
| 81 | [RoBERTa для трейдинга](chapters/081_roberta_trading/) |
| 82 | [XLNet для финансов](chapters/082_xlnet_finance/) |
| 83 | [ALBERT для трейдинга](chapters/083_albert_trading/) |
| 84 | [ELECTRA для финансов](chapters/084_electra_finance/) |
| 85 | [DeBERTa для трейдинга](chapters/085_deberta_trading/) |
| 86 | [Реферирование финансовых документов](chapters/086_financial_document_summarization/) |
| 87 | [Кросс-языковой NLP для финансов](chapters/087_cross_lingual_finance_nlp/) |
| 88 | [GPT для финансового анализа](chapters/088_gpt_financial_analysis/) |
| 89 | [Распознавание именованных сущностей](chapters/089_named_entity_recognition_finance/) |
| 90 | [Извлечение отношений для финансов](chapters/090_relation_extraction_finance/) |
| 91 | [Классификация документов в финансах](chapters/091_document_classification_finance/) |
| 92 | [Реферирование текстов в финансах](chapters/092_text_summarization_finance/) |
| 93 | [Ответы на вопросы в финансах](chapters/093_question_answering_finance/) |
| 94 | [Аспектный сентимент в финансах](chapters/094_aspect_sentiment_finance/) |
| 95 | [Извлечение событий для трейдинга](chapters/095_event_extraction_trading/) |
| 96 | [Временные рассуждения в финансах](chapters/096_temporal_reasoning_finance/) |
| 97 | [Мультимодальный NLP для трейдинга](chapters/097_multimodal_nlp_trading/) |
| 98 | [Граф знаний для трейдинга](chapters/098_knowledge_graph_trading/) |
| 99 | [Доменно-адаптивное предобучение](chapters/099_domain_adaptive_pretraining/) |
| 100 | [Инструкционная настройка для финансов](chapters/100_instruction_tuning_finance/) |
| 101 | [T5 предобучение для финансов](chapters/101_t5_pretraining_finance/) |

---

### Блок 6 — Мета-обучение (Главы 102–111)

| № | Глава |
|---|-------|
| 102 | [MAML для трейдинга](chapters/102_maml_for_trading/) |
| 103 | [Алгоритм Reptile для трейдинга](chapters/103_reptile_algorithm_trading/) |
| 104 | [Прототипные сети для финансов](chapters/104_prototypical_networks_finance/) |
| 105 | [Сети сопоставления для финансов](chapters/105_matching_networks_finance/) |
| 106 | [Zero-Shot трейдинг](chapters/106_zero_shot_trading/) |
| 107 | [Few-Shot прогнозирование рынка](chapters/107_few_shot_market_prediction/) |
| 108 | [Задачно-агностический трейдинг](chapters/108_task_agnostic_trading/) |
| 109 | [Мета-RL для трейдинга](chapters/109_meta_rl_trading/) |
| 110 | [Непрерывное мета-обучение](chapters/110_continual_meta_learning/) |
| 111 | [Оптимизация мета-градиентов](chapters/111_meta_gradient_optimization/) |

---

### Блок 7 — Трансферное обучение (Главы 112–116)

| № | Глава |
|---|-------|
| 112 | [Трансферное обучение для трейдинга](chapters/112_transfer_learning_trading/) |
| 113 | [Доменная адаптация для финансов](chapters/113_domain_adaptation_finance/) |
| 114 | [Многозадачное обучение для трейдинга](chapters/114_multi_task_learning_trading/) |
| 115 | [QuantNet: трансфер для квантов](chapters/115_quantnet_transfer_trading/) |
| 116 | [Мета-прогнозирование волатильности](chapters/116_meta_volatility_prediction/) |

---

### Блок 8 — Причинный вывод (Главы 117–131)

| № | Глава |
|---|-------|
| 117 | [Причинность по Грэнджеру](chapters/117_granger_causality_trading/) |
| 118 | [PCMCI: обнаружение причин](chapters/118_pcmci_causal_discovery/) |
| 119 | [Трансферная энтропия для трейдинга](chapters/119_transfer_entropy_trading/) |
| 120 | [VAR-LiNGAM для рынков](chapters/120_varlingam_markets/) |
| 121 | [Обучение DAG для финансов](chapters/121_dag_learning_finance/) |
| 122 | [Инструментальные переменные](chapters/122_instrumental_variables_trading/) |
| 123 | [Double ML для трейдинга](chapters/123_double_ml_trading/) |
| 124 | [Причинные леса для финансов](chapters/124_causal_forests_finance/) |
| 125 | [Синтетический контроль](chapters/125_synthetic_control_trading/) |
| 126 | [Разность разностей в трейдинге](chapters/126_diff_in_diff_trading/) |
| 127 | [Регрессионный разрыв](chapters/127_regression_discontinuity/) |
| 128 | [Оценка склонности в трейдинге](chapters/128_propensity_score_trading/) |
| 129 | [Анализ медиации в финансах](chapters/129_mediation_analysis_finance/) |
| 130 | [Обнаружение причинных факторов](chapters/130_causal_factor_discovery/) |
| 131 | [Контрфактический трейдинг](chapters/131_counterfactual_trading/) |

---

### Блок 9 — Интерпретируемость и объяснимость (Главы 132–146)

| № | Глава |
|---|-------|
| 132 | [SHAP для трейдинга](chapters/132_shap_trading_interpretability/) |
| 133 | [LIME для трейдинга](chapters/133_lime_trading_explanation/) |
| 134 | [Интегрированные градиенты для финансов](chapters/134_integrated_gradients_finance/) |
| 135 | [Визуализация внимания в трейдинге](chapters/135_attention_visualization_trading/) |
| 136 | [Атрибуция признаков в трейдинге](chapters/136_feature_attribution_trading/) |
| 137 | [Контрфактические объяснения](chapters/137_counterfactual_explanations/) |
| 138 | [Концептуальное бутылочное горлышко](chapters/138_concept_bottleneck_trading/) |
| 139 | [Прототипное обучение для трейдинга](chapters/139_prototype_learning_trading/) |
| 140 | [Извлечение правил для трейдинга](chapters/140_rule_extraction_trading/) |
| 141 | [Карты значимости для трейдинга](chapters/141_saliency_maps_trading/) |
| 142 | [Послойное распространение релевантности](chapters/142_layer_wise_relevance/) |
| 143 | [DeepLIFT для трейдинга](chapters/143_deeplift_trading/) |
| 144 | [GradCAM для финансов](chapters/144_gradcam_finance/) |
| 145 | [Attention Rollout для трейдинга](chapters/145_attention_rollout_trading/) |
| 146 | [Дистилляция в деревья решений](chapters/146_decision_tree_distillation/) |

---

### Блок 10 — Модели пространства состояний и Mamba (Главы 147–161)

| № | Глава |
|---|-------|
| 147 | [Mamba для трейдинга](chapters/147_mamba_for_trading/) |
| 148 | [S4: структурированное пространство состояний](chapters/148_s4_trading/) |
| 149 | [Жидкие машины состояний](chapters/149_liquid_state_machines/) |
| 150 | [MambaTS для временных рядов](chapters/150_mambats_time_series/) |
| 151 | [Mamba4Cast: zero-shot прогнозирование](chapters/151_mamba4cast_zero_shot/) |
| 152 | [C-Mamba: канальная корреляция](chapters/152_c_mamba_channel_correlation/) |
| 153 | [TimeParticle SSM](chapters/153_timeparticle_ssm/) |
| 154 | [Фреймворк HiPPO](chapters/154_hippo_framework/) |
| 155 | [Линейное внимание SSM](chapters/155_linear_attention_ssm/) |
| 156 | [Двунаправленная Mamba](chapters/156_bidirectional_mamba/) |
| 157 | [Иерархическая SSM](chapters/157_hierarchical_ssm/) |
| 158 | [Вентильная SSM](chapters/158_gated_ssm/) |
| 159 | [Диагональная SSM](chapters/159_diagonal_ssm/) |
| 160 | [Гибрид SSM-GNN](chapters/160_ssm_gnn_hybrid/) |
| 161 | [Гибрид SSM-Transformer](chapters/161_ssm_transformer_hybrid/) |

---

### Блок 11 — Физически информированные нейронные сети (Главы 162–176)

| № | Глава |
|---|-------|
| 162 | [PINN для модели Блэка-Шоулса](chapters/162_pinn_black_scholes/) |
| 163 | [PINN для американских опционов](chapters/163_pinn_american_options/) |
| 164 | [PINN для диффузии с прыжками](chapters/164_pinn_jump_diffusion/) |
| 165 | [PINN для модели Хестона](chapters/165_pinn_heston_model/) |
| 166 | [PINN для модели Халла-Уайта](chapters/166_pinn_hull_white_rates/) |
| 167 | [PINN для модели CIR](chapters/167_pinn_cir_model/) |
| 168 | [Нейронные СДУ для трейдинга](chapters/168_neural_sde_trading/) |
| 169 | [Нейронные ОДУ для трейдинга](chapters/169_neural_ode_trading/) |
| 170 | [Гамильтоновы нейронные сети](chapters/170_hamiltonian_nn_trading/) |
| 171 | [Лагранжевы нейронные сети](chapters/171_lagrangian_nn_trading/) |
| 172 | [Физически ограниченный GAN](chapters/172_physics_constrained_gan/) |
| 173 | [Обучение операторов для финансов](chapters/173_operator_learning_finance/) |
| 174 | [DeepONet для финансов](chapters/174_deeponet_finance/) |
| 175 | [Нейронный оператор Фурье](chapters/175_fourier_neural_operator/) |
| 176 | [Нейронные неявные представления](chapters/176_neural_implicit_finance/) |

---

### Блок 12 — Генеративные модели: диффузия, VAE и потоки (Главы 177–196)

| № | Глава |
|---|-------|
| 177 | [Диффузионные модели для трейдинга](chapters/177_diffusion_models_for_trading/) |
| 178 | [VAE факторная модель](chapters/178_vae_factor_model/) |
| 179 | [Распутанный факторный VAE](chapters/179_disentangled_factor_vae/) |
| 180 | [RVRAE: динамическая факторная модель](chapters/180_rvrae_dynamic_factor/) |
| 181 | [Beta-VAE для трейдинга](chapters/181_beta_vae_trading/) |
| 182 | [VQ-VAE для трейдинга](chapters/182_vq_vae_trading/) |
| 183 | [Условный VAE для трейдинга](chapters/183_conditional_vae_trading/) |
| 184 | [Иерархический VAE для трейдинга](chapters/184_hierarchical_vae_trading/) |
| 185 | [Распутанный VAE для трейдинга](chapters/185_disentangled_vae_trading/) |
| 186 | [VAE для генерации портфелей](chapters/186_vae_portfolio_generation/) |
| 187 | [VAE для поверхности волатильности](chapters/187_vae_volatility_surface/) |
| 188 | [Нормализующие потоки для финансов](chapters/188_normalizing_flows_finance/) |
| 189 | [RealNVP для трейдинга](chapters/189_realnvp_trading/) |
| 190 | [Glow для трейдинга](chapters/190_glow_trading/) |
| 191 | [Нейронные сплайновые потоки](chapters/191_neural_spline_flows/) |
| 192 | [Непрерывные нормализующие потоки](chapters/192_continuous_normalizing_flows/) |
| 193 | [Согласование оценок для трейдинга](chapters/193_score_matching_trading/) |
| 194 | [Энергетические модели](chapters/194_energy_based_models/) |
| 195 | [Сети Хопфилда для трейдинга](chapters/195_hopfield_networks_trading/) |
| 196 | [Ассоциативная память для трейдинга](chapters/196_associative_memory_trading/) |

---

### Блок 13 — Контрастное и самообучение (Главы 197–218)

| № | Глава |
|---|-------|
| 197 | [SimCLR для акций](chapters/197_simclr_for_stocks/) |
| 198 | [MoCo для трейдинга](chapters/198_moco_trading/) |
| 199 | [BYOL для трейдинга](chapters/199_byol_trading/) |
| 200 | [Barlow Twins для финансов](chapters/200_barlow_twins_finance/) |
| 201 | [SwAV для трейдинга](chapters/201_swav_trading/) |
| 202 | [VICReg для трейдинга](chapters/202_vicreg_trading/) |
| 203 | [Триплетное обучение для акций](chapters/203_triplet_learning_stocks/) |
| 204 | [Временное контрастное обучение](chapters/204_temporal_contrastive/) |
| 205 | [Кросс-модальное контрастное обучение](chapters/205_cross_modal_contrastive/) |
| 206 | [Майнинг трудных негативов](chapters/206_hard_negative_mining/) |
| 207 | [Контрастное предиктивное кодирование](chapters/207_contrastive_predictive_coding/) |
| 208 | [InfoNCE для трейдинга](chapters/208_infonce_trading/) |
| 209 | [NT-Xent для трейдинга](chapters/209_nt_xent_trading/) |
| 210 | [Supervised Contrastive Learning](chapters/210_supervised_contrastive/) |
| 211 | [Proto-Contrastive Learning](chapters/211_proto_contrastive/) |
| 212 | [Самообучение для трейдинга](chapters/212_self_supervised_trading/) |
| 213 | [Masked Autoencoder для финансов](chapters/213_masked_autoencoder_finance/) |
| 214 | [Self-Supervised для финансовых рядов](chapters/214_self_supervised_ts_finance/) |
| 215 | [CLIP мультимодальный для трейдинга](chapters/215_clip_multimodal_trading/) |
| 216 | [Аугментация данных для трейдинга](chapters/216_data_augmentation_trading/) |
| 217 | [Обучение по учебной программе](chapters/217_curriculum_learning_trading/) |
| 218 | [Активное обучение для трейдинга](chapters/218_active_learning_trading/) |

---

### Блок 14 — Микроструктура рынка и стакан заявок (Главы 219–238)

| № | Глава |
|---|-------|
| 219 | [Глубокое обучение для LOB](chapters/219_lob_deep_learning/) |
| 220 | [Маркет-мейкинг с ML](chapters/220_market_making_ml/) |
| 221 | [Прогнозирование потока ордеров](chapters/221_order_flow_prediction/) |
| 222 | [Моделирование ценового воздействия](chapters/222_price_impact_modeling/) |
| 223 | [Прогнозирование тиковых данных](chapters/223_tick_data_forecasting/) |
| 224 | [Классификация сделок](chapters/224_trade_classification/) |
| 225 | [Предсказание обновлений котировок](chapters/225_quote_update_prediction/) |
| 226 | [ML-моделирование спреда](chapters/226_spread_modeling_ml/) |
| 227 | [Прогнозирование ликвидности](chapters/227_liquidity_prediction/) |
| 228 | [Признаки микроструктуры](chapters/228_microstructure_features/) |
| 229 | [DeepLOB: прогнозирование](chapters/229_deeplob_forecasting/) |
| 230 | [LOBFrame: бенчмарк](chapters/230_lobframe_benchmark/) |
| 231 | [LIT Transformer для LOB](chapters/231_lit_transformer_lob/) |
| 232 | [CNN для предсказания LOB](chapters/232_cnn_lob_prediction/) |
| 233 | [LSTM для прогнозирования LOB](chapters/233_lstm_lob_forecasting/) |
| 234 | [Внимание для LOB](chapters/234_attention_lob/) |
| 235 | [GNN для LOB](chapters/235_gnn_lob/) |
| 236 | [Вариационный LOB](chapters/236_variational_lob/) |
| 237 | [Генеративный LOB](chapters/237_generative_lob/) |
| 238 | [RL для LOB](chapters/238_reinforcement_lob/) |

---

### Блок 15 — Обучение с подкреплением (Главы 239–268)

| № | Глава |
|---|-------|
| 239 | [TD3 для портфеля](chapters/239_td3_portfolio/) |
| 240 | [SAC для трейдинга](chapters/240_sac_trading/) |
| 241 | [PPO для портфеля](chapters/241_ppo_portfolio/) |
| 242 | [A2C для трейдинга](chapters/242_a2c_trading/) |
| 243 | [DDPG для трейдинга](chapters/243_ddpg_trading/) |
| 244 | [DQN для портфеля](chapters/244_dqn_portfolio/) |
| 245 | [Rainbow DQN для трейдинга](chapters/245_rainbow_dqn_trading/) |
| 246 | [C51: дистрибуционный RL](chapters/246_c51_distributional_rl/) |
| 247 | [IQN: неявные квантильные сети](chapters/247_iqn_implicit_quantile/) |
| 248 | [Иерархический RL для трейдинга](chapters/248_hierarchical_rl_trading/) |
| 249 | [Модельно-ориентированный RL](chapters/249_model_based_rl_trading/) |
| 250 | [World Models для трейдинга](chapters/250_world_models_trading/) |
| 251 | [Dreamer для трейдинга](chapters/251_dreamer_trading/) |
| 252 | [MuZero для трейдинга](chapters/252_muzero_trading/) |
| 253 | [Обратный RL для трейдинга](chapters/253_inverse_rl_trading/) |
| 254 | [Имитационное обучение](chapters/254_imitation_learning_trading/) |
| 255 | [Поведенческое клонирование](chapters/255_behavioral_cloning_trading/) |
| 256 | [GAIL для трейдинга](chapters/256_gail_trading/) |
| 257 | [Формирование вознаграждения](chapters/257_reward_shaping_trading/) |
| 258 | [Трейдинг на основе любопытства](chapters/258_curiosity_driven_trading/) |
| 259 | [Поиск Монте-Карло по дереву](chapters/259_monte_carlo_tree_search/) |
| 260 | [Планирование в RL для трейдинга](chapters/260_planning_rl_trading/) |
| 261 | [Офлайн-RL для трейдинга](chapters/261_offline_rl_trading/) |
| 262 | [Conservative Q-Learning](chapters/262_conservative_q_learning/) |
| 263 | [Decision Transformer](chapters/263_decision_transformer/) |
| 264 | [Trajectory Transformer](chapters/264_trajectory_transformer/) |
| 265 | [RL с целевым условием](chapters/265_goal_conditioned_rl/) |
| 266 | [Фреймворк опций для RL](chapters/266_option_framework_rl/) |
| 267 | [Обучение на основе популяции](chapters/267_population_based_training/) |
| 268 | [Многоцелевой RL для трейдинга](chapters/268_multi_objective_rl_trading/) |

---

### Блок 16 — Квантификация неопределённости и байесовские методы (Главы 269–279)

| № | Глава |
|---|-------|
| 269 | [Байесовская оптимизация для трейдинга](chapters/269_bayesian_optimization_trading/) |
| 270 | [Гауссовский процесс для трейдинга](chapters/270_gaussian_process_trading/) |
| 271 | [Квантификация неопределённости](chapters/271_uncertainty_quantification/) |
| 272 | [Неопределённость ансамблей](chapters/272_ensemble_uncertainty/) |
| 273 | [MC Dropout для трейдинга](chapters/273_mc_dropout_trading/) |
| 274 | [Глубокие ансамбли для трейдинга](chapters/274_deep_ensembles_trading/) |
| 275 | [Байесовские нейронные сети](chapters/275_bayesian_neural_network/) |
| 276 | [Вариационный вывод для трейдинга](chapters/276_variational_inference_trading/) |
| 277 | [Вероятностное прогнозирование](chapters/277_probabilistic_forecasting/) |
| 278 | [Интервалы предсказания для трейдинга](chapters/278_prediction_intervals_trading/) |
| 279 | [Копульные модели для финансов](chapters/279_copula_models_finance/) |

---

### Блок 17 — Графовые нейронные сети (Главы 280–290)

| № | Глава |
|---|-------|
| 280 | [Графовые нейронные сети для трейдинга](chapters/280_graph_neural_networks/) |
| 281 | [Graph Transformer для трейдинга](chapters/281_graph_transformer_trading/) |
| 282 | [Эквивариантная GNN для трейдинга](chapters/282_equivariant_gnn_trading/) |
| 283 | [Передача сообщений для трейдинга](chapters/283_message_passing_trading/) |
| 284 | [Graph Attention для трейдинга](chapters/284_graph_attention_trading/) |
| 285 | [Гетерогенная GNN для трейдинга](chapters/285_heterogeneous_gnn_trading/) |
| 286 | [Временная GNN для трейдинга](chapters/286_temporal_gnn_trading/) |
| 287 | [Динамическая GNN для трейдинга](chapters/287_dynamic_gnn_trading/) |
| 288 | [Генерация графов для трейдинга](chapters/288_graph_generation_trading/) |
| 289 | [Пулинг графов для трейдинга](chapters/289_graph_pooling_trading/) |
| 290 | [Майнинг подграфов для трейдинга](chapters/290_subgraph_mining_trading/) |

---

### Блок 18 — CNN и свёрточные модели временных рядов (Главы 291–300)

| № | Глава |
|---|-------|
| 291 | [WaveNet для трейдинга](chapters/291_wavenet_trading/) |
| 292 | [TCN: временная свёрточная сеть](chapters/292_tcn_trading/) |
| 293 | [Дилатированные свёртки для трейдинга](chapters/293_dilated_convolutions_trading/) |
| 294 | [InceptionTime для трейдинга](chapters/294_inception_time_trading/) |
| 295 | [ResNet для временных рядов](chapters/295_resnet_timeseries/) |
| 296 | [DenseNet для трейдинга](chapters/296_densenet_trading/) |
| 297 | [EfficientNet для трейдинга](chapters/297_efficientnet_trading/) |
| 298 | [ConvNeXt для трейдинга](chapters/298_convnext_trading/) |
| 299 | [Поканальные разделимые свёртки](chapters/299_depthwise_separable_trading/) |
| 300 | [Squeeze-and-Excitation сети](chapters/300_squeeze_excitation_trading/) |

---

### Блок 19 — Федеративное обучение (Главы 301–315)

| № | Глава |
|---|-------|
| 301 | [FedAvg для трейдинга](chapters/301_fedavg_trading/) |
| 302 | [FedProx для финансов](chapters/302_fedprox_finance/) |
| 303 | [Безопасная агрегация для трейдинга](chapters/303_secure_aggregation_trading/) |
| 304 | [Дифференциальная приватность](chapters/304_differential_privacy_trading/) |
| 305 | [Блокчейн-FL для трейдинга](chapters/305_blockchain_fl_trading/) |
| 306 | [Персонализированный FL](chapters/306_personalized_fl_trading/) |
| 307 | [Иерархический FL для трейдинга](chapters/307_hierarchical_fl_trading/) |
| 308 | [Асинхронный FL для трейдинга](chapters/308_asynchronous_fl_trading/) |
| 309 | [Коммуникационно-эффективный FL](chapters/309_communication_efficient_fl/) |
| 310 | [Компрессия градиентов в FL](chapters/310_fl_gradient_compression/) |
| 311 | [Византийски-устойчивый FL](chapters/311_byzantine_robust_fl/) |
| 312 | [Честный FL для трейдинга](chapters/312_fair_fl_trading/) |
| 313 | [Дистилляция знаний в FL](chapters/313_knowledge_distillation_fl/) |
| 314 | [FL через сайлосы в трейдинге](chapters/314_fl_cross_silo_trading/) |
| 315 | [FL на граничных устройствах](chapters/315_fl_edge_trading/) |

---

### Блок 20 — Квантовые вычисления (Главы 316–330)

| № | Глава |
|---|-------|
| 316 | [VQE для оптимизации портфеля](chapters/316_vqe_portfolio_optimization/) |
| 317 | [QAOA для трейдинга](chapters/317_qaoa_trading/) |
| 318 | [Квантовый GAN для финансов](chapters/318_quantum_gan_finance/) |
| 319 | [Квантовое ядро для трейдинга](chapters/319_quantum_kernel_trading/) |
| 320 | [Квантовая SVM для трейдинга](chapters/320_quantum_svm_trading/) |
| 321 | [Вариационный квантовый классификатор](chapters/321_variational_quantum_classifier/) |
| 322 | [Квантовая машина Больцмана](chapters/322_quantum_boltzmann_trading/) |
| 323 | [Алгоритм Гровера для трейдинга](chapters/323_grover_search_trading/) |
| 324 | [Алгоритм HHL для финансов](chapters/324_hhl_algorithm_finance/) |
| 325 | [Квантовая карта признаков](chapters/325_quantum_feature_map/) |
| 326 | [Квантовая коррекция ошибок](chapters/326_quantum_error_correction/) |
| 327 | [Гибридные квантово-классические системы](chapters/327_hybrid_quantum_classical/) |
| 328 | [NISQ-алгоритмы для трейдинга](chapters/328_nisq_trading_algorithms/) |
| 329 | [Квантовый отжиг для трейдинга](chapters/329_quantum_annealing_trading/) |
| 330 | [Тензорные сети для трейдинга](chapters/330_tensor_network_trading/) |

---

### Блок 21 — Эффективность моделей: дистилляция и NAS (Главы 331–350)

| № | Глава |
|---|-------|
| 331 | [Дистилляция знаний для трейдинга](chapters/331_knowledge_distillation_trading/) |
| 332 | [Компрессия моделей для финансов](chapters/332_model_compression_finance/) |
| 333 | [Прунинг торговых моделей](chapters/333_pruning_trading_models/) |
| 334 | [Квантизация торговых моделей](chapters/334_quantization_trading_models/) |
| 335 | [Гипотеза лотерейного билета](chapters/335_lottery_ticket_trading/) |
| 336 | [Самодистилляция для трейдинга](chapters/336_self_distillation_trading/) |
| 337 | [Учитель-ученик для трейдинга](chapters/337_teacher_student_trading/) |
| 338 | [Прогрессивная дистилляция](chapters/338_progressive_distillation/) |
| 339 | [Дистилляция данных для трейдинга](chapters/339_data_distillation_trading/) |
| 340 | [Дистилляция признаков](chapters/340_feature_distillation/) |
| 341 | [NAS для трейдинга](chapters/341_nas_for_trading/) |
| 342 | [AutoML для финансов](chapters/342_automl_finance/) |
| 343 | [Оптимизация гиперпараметров](chapters/343_hyperparameter_optimization/) |
| 344 | [Эволюционный NAS для трейдинга](chapters/344_evolutionary_nas_trading/) |
| 345 | [Дифференцируемый NAS](chapters/345_differentiable_nas/) |
| 346 | [One-Shot NAS](chapters/346_one_shot_nas/) |
| 347 | [Аппаратно-ориентированный NAS](chapters/347_hardware_aware_nas/) |
| 348 | [Многоцелевой NAS](chapters/348_multi_objective_nas/) |
| 349 | [DARTS для трейдинга](chapters/349_darts_trading/) |
| 350 | [EXAMM для трейдинга](chapters/350_examm_trading/) |

---

### Блок 22 — Устойчивость к атакам (Главы 351–360)

| № | Глава |
|---|-------|
| 351 | [Состязательное обучение для трейдинга](chapters/351_adversarial_training_trading/) |
| 352 | [Обнаружение состязательных атак](chapters/352_adversarial_attack_detection/) |
| 353 | [Устойчивые торговые модели](chapters/353_robust_trading_models/) |
| 354 | [Защита от возмущений входа](chapters/354_input_perturbation_defense/) |
| 355 | [Сертифицированная устойчивость](chapters/355_certified_robustness/) |
| 356 | [Состязательные примеры в финансах](chapters/356_adversarial_examples_finance/) |
| 357 | [Атаки уклонения для трейдинга](chapters/357_evasion_attacks_trading/) |
| 358 | [Атаки отравления для трейдинга](chapters/358_poisoning_attacks_trading/) |
| 359 | [Инверсия модели в финансах](chapters/359_model_inversion_finance/) |
| 360 | [Атаки принадлежности](chapters/360_membership_inference/) |

---

### Блок 23 — Передовые методы (Главы 361–365)

| № | Глава |
|---|-------|
| 361 | [Оператор Купмана для трейдинга](chapters/361_koopman_operator_trading/) |
| 362 | [Резервуарные вычисления для трейдинга](chapters/362_reservoir_computing_trading/) |
| 363 | [Жидкие нейронные сети для трейдинга](chapters/363_liquid_neural_networks_trading/) |
| 364 | [Нейроморфный трейдинг](chapters/364_neuromorphic_trading/) |
| 365 | [Фундаментальные модели для трейдинга: следующий рубеж](chapters/365_foundation_models_trading/) |

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
