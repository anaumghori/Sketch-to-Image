# Sketch to image
Welcome to the Sketch to Image Application! This innovative tool transforms your hand-drawn sketches, doodles, or input images into beautifully styled images. Whether you prefer a realistic rendering or an artistic interpretation, this application brings your ideas to life effortlessly.


## Key Features
- **Variety of Art Styles**  
    Choose from an extensive selection of artistic styles including Anime, Neon and Manga each tailored to produce unique and visually captivating results. Each style comes with predefined prompts that can be further personalized.  
  
- **Edge Detection & Processing**  
    Preprocesses images with HED edge detection and non-maximum suppression for improved sketch-like outputs. Images undergo Gaussian blur to smooth out sharp transitions, making them more suitable for processing into art.
  
- **Custom Prompts**  
    Users can input simple text prompts to guide the generation process, tailoring the output to specific creative ideas. Along with the custom user prompt, style-specific negative prompts are used to avoid common image generation pitfalls, ensuring the output meets high-quality standards
  
- **Seed Control & Randomization**  
    Provides options for adjusting random seeds, enabling reproducible results or diverse variations.
  
- **Interactive Interface**  
    Built with Gradio, allowing for a seamless and intuitive user experience with real-time image generation.
  
- **Advanced Options**  
    Allows users to fine-tune generation parameters such as steps, guidance scale, and conditioning scale for more precise control over the output. These options empower users to produce more detailed results according to their preferences.

## Example 



## Acknowledgments

>**Model used:** [xinsir/controlnet-scribble-sdxl-1.0](https://huggingface.co/xinsir/controlnet-scribble-sdxl-1.0) from Hugging Face  
>**Developed by:** xinsir  
>**Model type:** ControlNet_SDXL  
>**License:** Apache-2.0   
A copy of the Apache-2.0 license is included in this repository to comply with the licensing terms of the model.

---

>**Additional Model Used:** [Stable-Diffusion-XL-Base-1.0](https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0) from Stability AI  
>**License:** OpenRAIL++  
>The model is developed and maintained by **Stability AI**.  
>See the full OpenRAIL++ License terms [HERE](https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0/blob/main/LICENSE.md)).
