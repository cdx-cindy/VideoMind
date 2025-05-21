# VideoMind: An Omni-Modal Video Dataset with Intent Grounding for Deep-Cognitive Video Understanding \[[Paper]()\]

# :fire: News

# :book: Introduction
VideoMind is a large-scale video-centric multimodal dataset that can be used to learn powerful and transferable text-video representations for video understanding tasks such as video question answering and video retrieval. The VideoMind dataset contains more than _____ videos with a total duration of nearly _____ hours, consisting of _____ video clips, accompanied by detailed descriptions of a total of ____ words. The corresponding description of each video corresponds to four layers, namely factual layer, abstract layer, intentional layer and metaphor layer. Among them, the factual layer includes visual description, OCR of video frames, ASR of videos, description of audio, and the title of the original video. The intentional layer consists of two parts: the intent of the video uploader and the intent of the video main character. Our core contribution lies in developing an automated dataset generation method, autonomously constructing high-quality video-text datasets using large models, and demonstrating its effectiveness in large-scale learning of video-text representations. Specifically, we first use Qwen-omni to extract the OCR, ASR and Audio of the video. Then, prompts and the extracted OCR, ASR and Audio are adopted to guide the Qwen-VL large model to generate descriptions related to the video, automatically infer the intentions of the video publisher and the main character of the video content, as well as the metaphor of the video. Our dataset can be applied not only to scenarios that require fine-grained alignment, such as video retrieval, but also to fields that need in-depth understanding of videos, such as video question answering.

![b469e00b43d4]()

### Data

### Model Performance

# :arrow_down: Data & Model Zoo
\[[OpenDataLab](https://opendatalab.com/Dixin/VideoMind) \| [HuggingFace](https://opendatalab.com/Dixin/VideoMind) \]
