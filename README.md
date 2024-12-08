# Sketch to image Application
Welcome to the Sketch-to-Image Application! This innovative tool transforms your hand-drawn sketches, doodles, or input images into beautifully styled creations. If your input is a realistic or non-sketched image, it’s first converted into a refined sketch or scribble before being fed to the model. Whether you prefer a realistic rendering or an artistic interpretation, this application brings your ideas to life effortlessly.


## Key Features
- **Custom Prompts Made Simple**  
    Generate stunning outputs with short and straightforward text prompts. No need for intricate details—just describe your idea, and the system brings it to life.  

- **Style-Specific Refinements**  
    Each predefined style leverages tailored negative prompts to avoid common flaws, ensuring the output is visually polished and consistent with the chosen theme.  

- **Advanced Edge Detection**  
    Input images are processed with HED edge detection, Gaussian blur, and non-maximum suppression to create clean and refined sketch-like outputs, seamlessly preparing them for image generation.  

- **Diverse Style Options**  
    Explore a variety of styles such as Anime, Neon, and Manga, each carefully designed to produce unique results. Alternatively, the "No Style" option offers flexibility for generating hyper-realistic visuals or minimalist designs.  

- **Interactive Interface**  
    Built with Gradio, the user-friendly interface ensures a smooth and intuitive experience, enabling real-time input and instant image generation.  

- **Fine-Tuned Controls**  
   Adjust parameters like steps, guidance scale, and conditioning scale to refine the output, giving you the tools to achieve precise and detailed results.  

- **Seed Control & Randomization**  
    Experiment with diverse variations by randomizing the seed or recreate specific outputs by setting a fixed seed for reproducibility.  

## Example 
#### **Input (on left) VS Generated Images (on right)**
![1](https://github.com/user-attachments/assets/d6a03150-8b60-4af4-88ce-5da84e1528aa)
![2](https://github.com/user-attachments/assets/cddaddec-cfc7-4030-94c0-6d5f1181b282)

## Acknowledgments

>**Model used:** [xinsir/controlnet-scribble-sdxl-1.0](https://huggingface.co/xinsir/controlnet-scribble-sdxl-1.0)  
>**Developed by:** xinsir  
>**Model type:** ControlNet_SDXL  
>**License:** Apache-2.0   
A copy of the Apache-2.0 license is included in this repository to comply with the licensing terms of the model.

---

>**Additional Model Used:** [Stable-Diffusion-XL-Base-1.0](https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0) from Stability AI  
>**Developed and maintained by:** Stability AI  
>**License:** OpenRAIL++    
>See the full OpenRAIL++ License terms [HERE](https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0/blob/main/LICENSE.md)).
