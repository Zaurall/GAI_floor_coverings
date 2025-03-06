# GAI_floor_coverings

## Project Description

Our project is an AI-driven solution designed to generate realistic and visually coherent parquet floor patterns using Img2Img techniques. The goal of this project is to create customizable floor textures that seamlessly extend from an original sample, maintaining stylistic consistency while allowing for various customizations such as grain, grout color, chamfer, and mounting type.

The generated patterns could be used for both small-scale and large-scale flooring applications, with options for post-processing techniques like super-resolution to enhance the final output quality.

## Project Plan

1. **Dataset Preparation** - In progress:
   - Collect high-quality parquet images.
   - Preprocess the images to ensure consistency and quality.

2. **Model Selection and Fine-Tuning** - In progress:
   - Choose an appropriate Img2Img model (e.g., SD, Flux, GAN, Encoder-Decoder).
   - Fine-tune the selected model using the prepared dataset.

3. **Pattern Generation**:
   - Implement one of the two methods for pattern generation:
     - **Method 1**: Generate and assemble similar parquet patterns.
     - **Method 2**: Generate ready-to-use puzzle pieces with edge docking considerations.
   - Address the challenges of large-scale pattern generation.

4. **Customization**:
   - Add parameters for grain, grout color or type, chamfer, and mounting type.
   - Allow users to customize the generated patterns according to their preferences.

5. **Post-Processing**:
   - Apply refinement techniques like super-resolution to enhance the final output quality.