## Hi there 👋

## Using Repositories

The repositories are structured to share a set of core modules while remaining decoupled. Task-related notebooks should be placed in their respective task-specific repositories to maintain clarity.

| Repository | Description |
|------------|------------|
| [trainlib](https://github.com/arot-devs/trainlib) | Training framework / experiment logs for classifiers, SDXL, VLM and others. |
| [procslib](https://github.com/arot-devs/procslib) | Core repository for generative training metrics, including aesthetics scoring, taggers, CV2 metrics, and VLM-related evaluations. |
| [aeslib](https://github.com/arot-devs/aeslib) | Aesthetic score processing, including data collection, cleaning, quality assurance, and model evaluation. Excludes training logic. |
| [videolib](https://github.com/arot-devs/videolib) | Video data processing for sources like HunyuanVideo and LTXV. Includes video sectioning, optical flow filtering, VLM tagging, and dataset preparation. |
| [imagelib](https://github.com/arot-devs/imagelib) | Image data processing for SD/SDXL training, with metadata collection, Kedro workflow orchestration, dataset pipelines, and filtering configs. Excludes training logic. |
| [scrapelib](https://github.com/arot-devs/scrapelib) | Data scraping and extraction utilities for datasets. Handles large-scale collection and preprocessing. |
| [audiolib](https://github.com/arot-devs/audiolib) | Audio-related data processing, including segmentation, tagging, and dataset preparation for training. |

