## Hi there 👋

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->

## Using repos

the repositories are structured so that they share a set of core modules, while decoupling between each other. To avoid overcluttering the workspace, task-related notebooks should go into their specific task-named repo.

<br>

**core repos:**

| repo                                                        | description                                                  |
| ----------------------------------------------------------- | ------------------------------------------------------------ |
| [arot-devs/procslib](https://github.com/arot-devs/procslib) | Core repository for all kinds of metrics related to generative traing: aesthetic scores, taggers, cv2 metrics, vlms (if applicable) |
| [trojblue/unibox](https://github.com/trojblue/unibox)       | Core file provider module for different storage interfaces; handles file operations on local, http, s3 or huggingface. Also provides useful utility functions for notebook devs |

<br>

**data processing repos:**

| repo                                              | description                                                  |
| ------------------------------------------------- | ------------------------------------------------------------ |
| [aeslib](https://github.com/arot-devs/aeslib)     | Aesthetics score related notebooks and code; could be either numerical (regressions) or categorical (classifier). Includes data collection, iteration, cleaning, quality assurance and model eval code. does not include training logic. |
| [videolib](https://github.com/arot-devs/videolib) | Video data related processings, currently for HunyuanVideo and LTXV. Includes video sectioning, optical flow / aesthetic filtering, VLM tagging and dataset preparation code. does not include training logic. |
| [imagelib](https://github.com/arot-devs/imagelib) | Image data related processing codes used during SD / SDXL trainings: contains distributed metadata collection, kedro workflow orchestrator, dataset creation pipelines and filtering configs. does not include training or metrics calculation logic. |

<br>

**training repos:**

| repo                                              | description                                                  |
| ------------------------------------------------- | ------------------------------------------------------------ |
| [trainlib](https://github.com/arot-devs/trainlib) | Trainer and training configs for models that can fit within a few python files; including classifiers such as convnext, dino v2 and clip / siglip mlp. larger trainings such as SDXL or Flux are in corresponding trainer forks |











