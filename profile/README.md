## Hi there 👋

## Using Repositories

The repositories are structured to share a set of core modules while remaining decoupled. Task-related notebooks should be placed in their respective task-specific repositories to maintain clarity.



**Data Ingestion:**

| Repository                                          | Description                                                  |
| --------------------------------------------------- | ------------------------------------------------------------ |
| [scrapelib](https://github.com/arot-devs/scrapelib) | Utilities for large-scale data scraping and extraction, enabling dataset collection and preprocessing. |
| [unibox](https://github.com/trojblue/unibox)        | Unified data access layer for seamless intake and export across various file formats (e.g., Parquet, PNG) and storage backends (e.g., local, S3, Hugging Face). |
| [dataproc5](https://github.com/arot-devs/dataproc5) | Orchestrates data processing pipelines with Kedro, aggregating silver and gold-tier data from scrapes. |



**Model Training & Inference:**

| Repository                                        | Description                                                  |
| ------------------------------------------------- | ------------------------------------------------------------ |
| [trainlib](https://github.com/arot-devs/trainlib) | Framework for training and experiment logging, supporting classifiers, SDXL, VLM, and other models. |
| [procslib](https://github.com/arot-devs/procslib) | Inference framework for trained models, supporting aesthetics scoring, taggers, CV2 metrics, and VLM-based evaluations. |



**Data Processing & Experimentation:**

| Repository                                        | Description                                                  |
| ------------------------------------------------- | ------------------------------------------------------------ |
| [aeslib](https://github.com/arot-devs/aeslib)     | Aesthetic score processing, including data collection, cleaning, quality assurance, and model evaluation. Excludes training logic. |
| [audiolib](https://github.com/arot-devs/audiolib) | Handles audio-related data processing, including segmentation, tagging, and dataset preparation. |
| [imagelib](https://github.com/arot-devs/imagelib) | Image data processing for SD/SDXL training, encompassing metadata collection, dataset pipelines, and filtering configurations. Excludes training logic. |
| [videolib](https://github.com/arot-devs/videolib) | Video data processing for sources like HunyuanVideo and LTXV, featuring video sectioning, optical flow filtering, VLM tagging, and dataset preparation. |

