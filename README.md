# Awesome Quran AI

> A curated collection of APIs, datasets, models, tools, papers, and open-source projects for developers building Quran AI applications.

Quran AI work touches sacred text, language, speech, search, education, and scholarship. This repository aims to make the technical ecosystem easier to discover while keeping source provenance, licensing, and religious sensitivity visible.

Maintained by [Mhammed Talhaouy](https://github.com/tal7aouy).

## Contents

- [APIs](#apis)
- [Datasets](#datasets)
- [Models](#models)
- [Tools](#tools)
- [Papers](#papers)
- [Open-source Projects](#open-source-projects)
- [Contribution Criteria](#contribution-criteria)

## APIs

- [Quran.com API](https://api-docs.quran.com/) - Public API for Quran.com content, including verses, chapters, translations, tafsir metadata, audio, and related Quran resources.
- [Al Quran Cloud API](https://alquran.cloud/api) - REST API for Quran text, editions, translations, audio, juz, surah, ayah, and search endpoints.
- [QuranEnc API](https://quranenc.com/en/home/api/) - API for Quran translations and meanings published by the Quran Encyclopedia project.
- [EveryAyah](https://everyayah.com/) - Quran audio archive and recitation file endpoints commonly used by Quran applications.
- [Tanzil Quran Text](https://tanzil.net/download/) - Downloadable verified Quran text data with multiple text formats and metadata.
- [Quran Foundation API Docs](https://github.com/quran/qf-api-docs) - Documentation portal for Quran Foundation API resources.
- [Quran Foundation JS SDK](https://github.com/quran/api-js) - Official TypeScript/JavaScript SDK for Quran Foundation APIs.
- [fawazahmed0/quran-api](https://github.com/fawazahmed0/quran-api) - Free Quran API with many translations and language editions.
- [The Quran Project API](https://github.com/The-Quran-Project/Quran-API) - Open Quran API with no advertised rate limit.
- [Tafsir API](https://github.com/spa5k/tafsir_api) - API service for tafsir resources in multiple languages.
- [Alfanous](https://github.com/Alfanous-team/alfanous) - Arabic Quran search engine and API with simple and advanced search.
- [gadingnst/quran-api](https://github.com/gadingnst/quran-api) - Quran API and database with Indonesian tafsir and recitation audio.
- [renomureza/quran-api-id](https://github.com/renomureza/quran-api-id) - Indonesian Quran REST API with translations, tafsir, and audio.
- [bachors/Al-Quran-ID-API](https://github.com/bachors/Al-Quran-ID-API) - Indonesian Quran API with translation and audio.
- [GlobalQuran](https://github.com/GlobalQuran/site) - GlobalQuran API-driven Quran site code and data access patterns.

## Datasets

- [Quranic Arabic Corpus](https://corpus.quran.com/) - Morphological, syntactic, and semantic annotation for Quranic Arabic.
- [Tanzil Quran Text](https://tanzil.net/download/) - Verified Uthmani and simple Quran text files with verse numbering and metadata.
- [QuranMorph](https://sina.birzeit.edu/quran) - Open Quranic morphology corpus from SinaLab with lemma and part-of-speech annotations.
- [Quran-MD](https://huggingface.co/datasets/Buraaq/quran-audio-text-dataset) - Multilingual multimodal Quran dataset with text, transliteration, translations, and verse/word-level audio.
- [Tadabur Quran Audio Dataset](https://arxiv.org/abs/2604.18932) - Large-scale Quran recitation audio dataset paper describing 1400+ hours from 600+ reciters.
- [Quranic Audio Dataset](https://arxiv.org/abs/2405.02675) - Crowdsourced and labeled Quran recitation dataset focused on non-Arabic speakers.
- [Corpus Coranicum](https://corpuscoranicum.de/) - Research databases for Quran manuscripts, variant readings, and historical context.
- [Tarteel Quranic Universal Library](https://github.com/TarteelAI/quranic-universal-library) - Comprehensive Quran resource collection from Tarteel AI.
- [AbdullahGhanem/quran-database](https://github.com/AbdullahGhanem/quran-database) - Quran MySQL database repository.
- [semarketir/quranjson](https://github.com/semarketir/quranjson) - Quran JSON dataset with 6236 verses, 114 surahs, and 30 juz.
- [risan/quran-json](https://github.com/risan/quran-json) - Quran text and translations in JSON format.
- [rioastamal/quran-json](https://github.com/rioastamal/quran-json) - Quran, translation, and Indonesian tafsir in JSON format.
- [rn0x/Quran-Data](https://github.com/rn0x/Quran-Data) - Quran databases in JSON, CSV, SQLite, and API formats.
- [aliftype/quran-data](https://github.com/aliftype/quran-data) - Unicode-encoded Quran data.
- [quran/quran.com-images](https://github.com/quran/quran.com-images) - Quran page image generation using King Fahd Complex fonts.
- [batoulapps/quran-svg](https://github.com/batoulapps/quran-svg) - SVG files for Quran pages.
- [NoorBayan/Quranic](https://github.com/NoorBayan/Quranic) - Quran text processing dataset and Quranic treebank work.
- [islamAndAi/QURAN-NLP](https://github.com/islamAndAi/QURAN-NLP) - Quran, hadith, translations, tafsir, and corpus linguistics resources for NLP.
- [tarteel-ai/quranqa](https://huggingface.co/datasets/tarteel-ai/quranqa) - Expert-generated Quran question answering dataset.
- [tarteel-ai/quran-tafsir](https://huggingface.co/datasets/tarteel-ai/quran-tafsir) - Tafsir dataset hosted by Tarteel AI.
- [hetchyy/quranic-universal-ayahs](https://huggingface.co/datasets/hetchyy/quranic-universal-ayahs) - Quranic ayah dataset for speech and text tasks.
- [ashraf-ali/quran-data](https://huggingface.co/datasets/ashraf-ali/quran-data) - Quran audio/text dataset sourced from Tarteel.io.
- [riotu-lab/Quran-Tafseers](https://huggingface.co/datasets/riotu-lab/Quran-Tafseers) - Arabic Quran tafsir dataset.
- [nazimali/quran-question-answer-context](https://huggingface.co/datasets/nazimali/quran-question-answer-context) - Arabic/English Quran question-answer-context dataset.
- [ImruQays/Quran-Classical-Arabic-English-Parallel-texts](https://huggingface.co/datasets/ImruQays/Quran-Classical-Arabic-English-Parallel-texts) - Classical Arabic and English Quran parallel texts.
- [ahishamm/QURANICWhisperDataset](https://huggingface.co/datasets/ahishamm/QURANICWhisperDataset) - Audio/text dataset for Quran ASR experiments.
- [sobolev210/quran-recitation-errors](https://huggingface.co/datasets/sobolev210/quran-recitation-errors) - Quran recitation error audio dataset.
- [RetaSy/quranic_audio_dataset](https://huggingface.co/datasets/RetaSy/quranic_audio_dataset) - Quranic audio dataset for ASR and audio classification.

## Models

- [Jais](https://huggingface.co/core42) - Open Arabic-English language models useful for Arabic NLP and Quran-adjacent experimentation.
- [AraBERT](https://github.com/aub-mind/arabert) - Arabic BERT models and preprocessing tools for Arabic NLP tasks.
- [CAMeLBERT](https://github.com/CAMeL-Lab/CAMeLBERT) - Arabic pretrained language models from CAMeL Lab.
- [AraBART](https://huggingface.co/moussaKam/AraBART) - Arabic sequence-to-sequence model for generation and summarization tasks.
- [Whisper](https://github.com/openai/whisper) - Open-source speech recognition models often used as a baseline for Quran recitation transcription experiments.
- [tarteel-ai/whisper-base-ar-quran](https://huggingface.co/tarteel-ai/whisper-base-ar-quran) - Whisper model fine-tuned for Arabic Quran recitation ASR.
- [tarteel-ai/whisper-tiny-ar-quran](https://huggingface.co/tarteel-ai/whisper-tiny-ar-quran) - Smaller Whisper model fine-tuned for Quran recitation ASR.
- [mohammed/fastconformer-quran-ar](https://huggingface.co/mohammed/fastconformer-quran-ar) - FastConformer Quran Arabic ASR model.
- [Muno459/fastconformer-quran](https://huggingface.co/Muno459/fastconformer-quran) - ONNX-oriented FastConformer model for Quranic recitation.
- [Muno459/fastconformer-quran-streaming](https://huggingface.co/Muno459/fastconformer-quran-streaming) - Streaming FastConformer Quran ASR model.
- [Nuwaisir/Quran_speech_recognizer](https://huggingface.co/Nuwaisir/Quran_speech_recognizer) - Wav2Vec2 Quran speech recognition model.
- [mustapha/QuranExe-bert](https://huggingface.co/mustapha/QuranExe-bert) - BERT model trained for Quran-related masked language modeling.
- [mustapha/e5-small-Quran](https://huggingface.co/mustapha/e5-small-Quran) - Quran-focused E5 embedding model.
- [Damith/AraELECTRA-discriminator-QuranQA](https://huggingface.co/Damith/AraELECTRA-discriminator-QuranQA) - AraELECTRA model for Quran question answering.
- [hemagamal/mdeberta_quran_qa_model](https://huggingface.co/hemagamal/mdeberta_quran_qa_model) - mDeBERTa Quran question-answering model.

## Tools

- [Quranic Arabic Corpus Search](https://corpus.quran.com/search.jsp) - Morphology-aware search over Quranic Arabic.
- [Tanzil Quran Navigator](https://tanzil.net/) - Web Quran browser with translations, recitations, and downloadable text resources.
- [Quran.com](https://quran.com/) - Quran reading, translation, tafsir, audio, and search platform.
- [Zekr](https://sourceforge.net/projects/zekr/) - Open-source desktop Quran study application.
- [quran.com-frontend-next](https://github.com/quran/quran.com-frontend-next) - Quran.com frontend codebase for studying production Quran UX patterns.
- [PyQuran](https://github.com/hci-lab/PyQuran) - Python package for Quranic text analysis.
- [CAMeL Tools](https://github.com/CAMeL-Lab/camel_tools) - Arabic NLP toolkit for preprocessing, morphology, dialect identification, and NER.
- [quran-validator](https://github.com/yazinsai/quran-validator) - Tool for validating Quranic verses in LLM-generated text.
- [offline-tarteel](https://github.com/yazinsai/offline-tarteel) - Offline Quran verse recognition from recitation audio.
- [quran-align](https://github.com/cpfair/quran-align) - Word-accurate timestamps for Quranic audio.
- [quran-tajweed](https://github.com/cpfair/quran-tajweed) - Tajweed annotation tooling for the Quran.
- [QuranCaption](https://github.com/zonetecde/QuranCaption) - Tool for generating captioned videos from Quranic recitation.
- [quran-cli](https://github.com/sarfraznawaz2005/quran-cli) - Command-line Quran reader and reciter with English translation.
- [Quran-cli](https://github.com/Mostafa-wael/Quran-cli) - Command-line interface for listening to Quran.
- [quran-mcp](https://github.com/quran/quran-mcp) - Quran.com MCP server for connecting Quran resources to AI agents.
- [open-hikmah](https://github.com/Nazm-AI/open-hikmah) - AI-powered Quran knowledge graph and thematic exploration project.
- [qurananalysis](https://github.com/karimouda/qurananalysis) - Quran search, exploration, analysis, and question-answering system.

## Papers

- [QuranMorph: Morphologically Annotated Quranic Corpus](https://arxiv.org/abs/2506.18148) - Corpus paper describing manually verified lemmas and part-of-speech tags for Quranic Arabic.
- [Quran-MD: A Fine-Grained Multilingual Multimodal Dataset of the Quran](https://arxiv.org/abs/2601.17880) - Dataset paper for verse- and word-level Quran text/audio resources.
- [Tadabur: A Large-Scale Quran Audio Dataset](https://arxiv.org/abs/2604.18932) - Quran audio dataset paper covering scale, reciter diversity, and speech research use cases.
- [Quranic Audio Dataset: Crowdsourced and Labeled Recitation from Non-Arabic Speakers](https://arxiv.org/abs/2405.02675) - Paper on crowdsourcing and annotating Quran recitation data.
- [Quranic Conversations: Developing a Semantic Search tool for the Quran using Arabic NLP Techniques](https://arxiv.org/abs/2311.05120) - Semantic Quran search paper using tafsir embeddings and Arabic NLP models.
- [Supervised Collaboration for Syntactic Annotation of Quranic Arabic](https://link.springer.com/article/10.1007/s10579-011-9167-7) - Foundational paper related to the Quranic Arabic Corpus.
- [Smartajweed Automatic Recognition of Arabic Quranic Recitation Rules](https://arxiv.org/abs/2101.04200) - Tajweed rule recognition system using classical machine learning techniques.
- [A computational system to handle the orthographic layer of tajwid in contemporary Quranic Orthography](https://arxiv.org/abs/2505.11379) - Python-module-based work on adding and removing tajwid orthographic layers.
- [A Critical Review of the Need for Knowledge-Centric Evaluation of Quranic Recitation](https://arxiv.org/abs/2510.12858) - Review of automated Quranic recitation evaluation and knowledge-centric approaches.

## Open-source Projects

- [quran.com-frontend-next](https://github.com/quran/quran.com-frontend-next) - Next.js frontend for Quran.com.
- [qf-api-docs](https://github.com/quran/qf-api-docs) - Quran Foundation API documentation repository.
- [AraBERT](https://github.com/aub-mind/arabert) - Arabic pretrained transformer models and utilities.
- [CAMeL Tools](https://github.com/CAMeL-Lab/camel_tools) - Arabic NLP toolkit for preprocessing, morphology, dialect identification, named entity recognition, and more.
- [Zekr](https://sourceforge.net/projects/zekr/) - Open-source Quran study desktop application.
- [Quran Android](https://github.com/quran/quran_android) - Open-source Quran app for Android.
- [quran-ios](https://github.com/quran/quran-ios) - QuranEngine and iOS code powering Quran.com mobile experiences.
- [audio.quran.com](https://github.com/quran/audio.quran.com) - QuranicAudio.com web application.
- [quranicaudio-app](https://github.com/quran/quranicaudio-app) - Mobile application for QuranicAudio.com.
- [baca-quran.id](https://github.com/mazipan/baca-quran.id) - Ad-free Quran reading web app.
- [the-holy-quran-app](https://github.com/mhmzdev/the-holy-quran-app) - Flutter Quran application.
- [QuranApp](https://github.com/AlfaazPlus/QuranApp) - Privacy-focused Android Quran app.
- [Quran-Flutter](https://github.com/SadaqaWorks/Quran-Flutter) - Flutter Quran app for multiple platforms.
- [QuranyApp](https://github.com/MahmoudMabrok/QuranyApp) - Android Quran app with reading, listening, tafsir, and tests.
- [quran-companion](https://github.com/0xzer0x/quran-companion) - Desktop Quran reader and player.
- [Qawl](https://github.com/sufone/qawl) - Quran reader for Linux, Windows, and macOS.
- [NoorUlHuda](https://github.com/mirfatif/NoorUlHuda) - Open-source Quran reader app.
- [Word-By-Word-Quran-Android](https://github.com/SadaqaWorks/Word-By-Word-Quran-Android) - Android app with word-by-word Quran support.
- [QuranOnAndroid](https://github.com/hussien89aa/QuranOnAndroid) - Open-source Android Quran listening app.
- [quran-web](https://github.com/rioastamal/quran-web) - Mobile web Quran built on quran-json.
- [quranwbw](https://github.com/marwan/quranwbw) - Word-by-word Quran reading and learning app.
- [Real-Time Quran recitation tracker System](https://github.com/yayaiu6/Real-Time-Quran-recitation-tracker-System) - Real-time Quran recitation tracking, alignment, and error-detection project.
- [quran-muaalem](https://github.com/obadx/quran-muaalem) - AI teacher for Quran learning.
- [Mishkat](https://github.com/NoorBayan/Mishkat) - AI-driven multilingual Quran audio translation and explanation project.

## Contribution Criteria

Additions should be useful for Quran AI developers, researchers, or builders. Please include:

- A stable project, paper, dataset, or documentation link.
- License or terms of use when available.
- Data provenance for Quran text, translations, tafsir, or audio.
- A short neutral description.
- A note when the resource is Quran-specific versus generally Arabic/Islamic NLP.

Avoid adding unverified generated religious content, scraped private datasets, unclear Quran text variants, or resources without usable access information.

See [CONTRIBUTING.md](CONTRIBUTING.md) for the full submission format.

## Data File

The structured catalog lives in [data/resources.yml](data/resources.yml). The README is the human-facing view; the YAML file is intended for future automation such as website generation, link checks, or category pages.

## License

The curated list metadata is released under [CC0-1.0](LICENSE). Individual resources keep their own licenses and terms.
