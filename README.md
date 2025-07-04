# Generative AI Course

## General Course Information

Generative AI explores the creation of models capable of generating new content, spanning images, text, music, and beyond. This course delves into the core concepts, methods, and applications of generative deep learning, offering both theoretical foundations and practical skills.

## Course Objectives

- Understand the foundational concepts and methods in generative deep learning.
- Implement and train various generative models, including VAEs, autoregressive models, and graph neural networks.
- Apply generative models to diverse domains, such as music generation, world modeling, and multimodal data synthesis.
- Gain practical experience in generative AI through hands-on projects and exercises.

## Learning Outcomes

By the end of this course, students should be able to:

- Explain the principles and algorithms of generative deep learning models.
- Implement and train generative models using PyTorch.
- Apply generative models to create novel content across different domains.
- Analyze and evaluate the performance of generative models for specific tasks and datasets.


## Course Content (Subject to Change)

- Introduction to Generative Modeling
- Variational Autoencoders (VAEs)
- Autoregressive Models
- Energy-Based Models
- Diffusion Models
- Graph Generative Models
- Music Generation
- Image Generation
- World Models
- Multimodal Models

## Lecture Breakdown


0. **Random Variable Generation**.
   * Random Variable Generation (and how to generate samples from known distributions) [notebook](https://github.com/USFCA-MSDS/MSDS-631/blob/main/RandomVariableGeneration.ipynb)
   * Quiz questions [file](https://github.com/USFCA-MSDS/MSDS-631/blob/main/interview/exam_questions.txt)
1. **Variational Autoencoders (VAEs)**. [Code](https://github.com/USFCA-MSDS/MSDS-631-GenAI/blob/main/CVAE.ipynb) [Notes]()
  - [Variant versions of VAR](https://github.com/AntixK/PyTorch-VAE)
  -  AutoEncoders [notebook](https://github.com/USFCA-MSDS/MSDS-631/blob/main/AutoEncoders.ipynb)   
   * Variational AutoEncoders [notebook](https://github.com/USFCA-MSDS/MSDS-631/blob/main/VAE.ipynb)
   * AE and VAE [lecture note](https://github.com/USFCA-MSDS/MSDS-631/blob/main/AE.pdf)      

2. **Normalization Flow and Gans**
   * NF [blog](https://lilianweng.github.io/posts/2018-10-13-flow-models/)
   * NF [blog2](https://gebob19.github.io/normalizing-flows/)
   * NF [notebook](https://github.com/USFCA-MSDS/MSDS-631/blob/main/Introduction_to_NF.ipynb) 
   * NF Lecture [PDF](https://github.com/USFCA-MSDS/MSDS-631/blob/main/NF.pdf)
   * GANS [notebook](https://github.com/USFCA-MSDS/MSDS-631/blob/main/GANS%20(2).ipynb)  
   * GANS Lecture [PDF](https://github.com/USFCA-MSDS/MSDS-631/blob/main/GANs.pdf)
   * GANS [blog](https://gwern.net/gan)
3. **Autoregressive Models**
   * [Intro to AR models](https://github.com/USFCA-MSDS/MSDS-631-GenAI/blob/main/auto_regressive_models.pdf)
   * [simple_autoregressive](https://github.com/USFCA-MSDS/MSDS-631-GenAI/blob/main/Simple_autoregressive_gen_model.ipynb) [SimplePixelCNN](https://github.com/USFCA-MSDS/MSDS-631-GenAI/blob/main/PixelCNN.ipynb) [PixelCNN full implementation](https://github.com/davidADSP/Generative_Deep_Learning_2nd_Edition/blob/main/notebooks/05_autoregressive/02_pixelcnn/pixelcnn.ipynb) [PixelCNN Mixture head](https://github.com/USFCA-MSDS/MSDS-631-GenAI/blob/main/pixel_cnn_with_mixture_head.ipynb)
   * [char rnn](https://github.com/karpathy/char-rnn) [rnn-effectiveness](https://karpathy.github.io/2015/05/21/rnn-effectiveness/) 
5. **Diffusion Models** -(Part I)
    * [Lecture](https://github.com/USFCA-MSDS/MSDS-631-GenAI/blob/main/diffusion_models_.pdf)
    * [The Diffusion Model's Unsung Sidekick: A Science of Solving (Almost) Any Problem using Probability](https://www.youtube.com/watch?v=Fk2I6pa6UeA&t=1105s)
    * [Diffusors tutorial on huggingface](https://huggingface.co/learn/diffusion-course/en/unit1/1) [Diffusion 1d example from sctrach](https://github.com/USFCA-MSDS/MSDS-631-GenAI/blob/main/1d_Diffusion_Model_from_scratch.ipynb)
    * [Tutorial  on diffusion models](https://arxiv.org/pdf/2403.18103)
    * [CVPR tutorial on diffusion models](https://cvpr2022-tutorial-diffusion-models.github.io/)
    * [Video Tutorial on diffuion models](https://www.youtube.com/watch?v=a4Yfz2FxXiY) [Code](https://github.com/dome272/Diffusion-Models-pytorch/blob/main/ddpm.py) 
    * Recall : [U-Nets](https://github.com/USFCA-MSDS/MSDS-631-GenAI/blob/main/U_net_explained.ipynb) [U-net lecture](https://github.com/USFCA-MSDS/MSDS-631-GenAI/blob/main/U-nets.pdf)
    * [Topological Explaination of Diffusion Models, Homotopy](https://mathematica.stackexchange.com/questions/59463/homotopy-visualization)
7. **Diffusion Models** - (Part II)
    * [Lecture](https://github.com/USFCA-MSDS/MSDS-631-GenAI/blob/main/diffusion_models_2_.pdf)
    * [Score Matching](https://colab.research.google.com/drive/1dol5AXz_oNkFZMrwpDyK6MYnOB4ayEQU?usp=sharing#scrollTo=rU0m57SJfXqb)
    * [Conditional diffusion model introduction](https://colab.research.google.com/github/huggingface/diffusion-models-class/blob/main/unit2/02_class_conditioned_diffusion_model_example.ipynb)
    * [Fine Tuning diffusors](https://colab.research.google.com/github/huggingface/diffusion-models-class/blob/main/unit2/01_finetuning_and_guidance.ipynb#scrollTo=2n9AmuTZlWLI)
    * [Training Diffusors](https://colab.research.google.com/github/huggingface/notebooks/blob/main/diffusers/training_example.ipynb#scrollTo=67640279-979b-490d-80fe-65673b94ae00)
    * [Stable diffusion introduction](https://colab.research.google.com/github/huggingface/diffusion-models-class/blob/main/unit3/01_stable_diffusion_introduction.ipynb#scrollTo=fx6whXJmsNG9),     [Stable diffusion](https://colab.research.google.com/github/huggingface/notebooks/blob/main/diffusers/stable_diffusion.ipynb#scrollTo=YE7hhg5ArUu4)
    * [Stable Diffusion in pytorch](https://github.com/hkproj/pytorch-stable-diffusion/tree/main)
    * [Grokking Stable Diffusion : self-contained stable diffusion tutorial](https://colab.research.google.com/drive/1dlgggNa5Mz8sEAGU0wFCHhGLFooW_pf1?usp=sharing)
    * [Stable Diffusion Video](https://www.youtube.com/watch?v=J87hffSMB60&t=615s)
    * [Modern image generation, excellent intuitive overview of image generation with diffusion models](https://www.youtube.com/watch?v=1pgiu--4W3I)
    * [Diffusors course](https://huggingface.co/learn/audio-course/chapter0/introduction)  
8. **Multimodal Models (Part I)** - Fusion of Text, Image, and Audio Data
      * [Lecture](https://github.com/USFCA-MSDS/MSDS-631-GenAI/blob/main/Intro_to_MDM.pdf)

      *Clip related topics*  
      * [A template notebook for building a multimodal](https://github.com/USFCA-MSDS/MSDS-631-GenAI/blob/main/multimodal_model_template.ipynb)
      * [Embedding Alignment](https://github.com/USFCA-MSDS/MSDS-631-GenAI/blob/main/Embedding_Alignment_updated.ipynb)
      * [Introduction to clip](https://github.com/USFCA-MSDS/MSDS-631-GenAI/blob/main/Introduction_to_clip.ipynb)
      * [Building clip](https://github.com/USFCA-MSDS/MSDS-631-GenAI/blob/main/building_clip.ipynb)
      * [Introduction to zero shot classification with clip](https://github.com/USFCA-MSDS/MSDS-631-GenAI/blob/main/zero_shot_classification_with_clip.ipynb)
      * [zero shot classification with clip, MNIST example](https://github.com/USFCA-MSDS/MSDS-631-GenAI/blob/main/zero_shot_classification_mnist.ipynb)
      * [image caption with clip](https://github.com/USFCA-MSDS/MSDS-631-GenAI/blob/main/image_caption_with_clip.ipynb)
      * [Using clip in search](https://blog.lancedb.com/multi-modal-ai-made-easy-with-lancedb-clip-5aaf8801c939/)
      * [Training Clip in practice](https://github.com/USFCA-MSDS/MSDS-631-GenAI/blob/main/Training_clip_in_practice.ipynb) [Clip-X](https://github.com/lucidrains/x-clip) [openClip](https://github.com/mlfoundations/open_clip/tree/main) [Hugging face clip model](https://huggingface.co/docs/transformers/en/model_doc/clip)
        

        

9. **Multimodal Models (Part II)** - Advanced Techniques and Case Studies
      * [Lecture DALLE2](https://github.com/USFCA-MSDS/MSDS-631-GenAI/blob/main/DALLE_2_MSDS_2025.pdf) [Lecture IMAGEN](https://github.com/USFCA-MSDS/MSDS-631-GenAI/blob/main/Imagen_MSDS_2025.pdf)
      * [DALLE2 Code](https://github.com/lucidrains/DALLE2-pytorch?tab=readme-ov-file) [IMAGEN Code](https://github.com/lucidrains/imagen-pytorch)

      * *DALLE and DALLE2*
      * [Simplified DALLE from scratch](https://github.com/USFCA-MSDS/MSDS-631-GenAI/blob/main/Simplified_DALLE.ipynb)
      * [Training Imagen in practice](https://github.com/lucidrains/imagen-pytorch)
      * [How Dall-e 2 works](https://www.assemblyai.com/blog/how-dall-e-2-actually-works/) [Video](https://www.youtube.com/watch?v=Z8E3LxqE49M)
      * [Training Dall-e 2](https://github.com/lucidrains/DALLE2-pytorch?tab=readme-ov-file)
        
      * *Imagen generative model*
      * [Simplified Imagen](https://github.com/USFCA-MSDS/MSDS-631-GenAI/blob/main/Simplified_Imagen.ipynb) [Imagen Blog](https://imagen.research.google/)

      * *Recall materials*  
      * [Recall Super res NN](https://github.com/USFCA-MSDS/MSDS-631-GenAI/blob/main/super_res_nn%20(2).pdf)
      * [Vision Transformer main popular github library](https://github.com/lucidrains/vit-pytorch)
      * [Simplified Super res NN implementation](https://github.com/USFCA-MSDS/MSDS-631-GenAI/blob/main/super_res_NN_simplified.ipynb)

10. **Energy-based models** -
      * [Energy-based model tutorial](https://uvadlc-notebooks.readthedocs.io/en/latest/tutorial_notebooks/tutorial8/Deep_Energy_Models.html)
      * [Lecture](https://github.com/USFCA-MSDS/MSDS-631-GenAI/blob/main/energy_models.pdf)
      * [Impainting crop](https://github.com/USTC-JialunPeng/Diverse-Structure-Inpainting)
      * Impainting [notebook](https://github.com/USFCA-MSDS/MSDS-631-GenAI/blob/main/inpainting_noise.ipynb)
      * [simple MCMC](https://github.com/USFCA-MSDS/MSDS-631-GenAI/blob/main/Simple_MCMC.ipynb) [MCMC good introduction video](https://www.youtube.com/watch?v=yApmR-c_hKU)
      * [Metropolis-adjusted_Langevin_algorithm](https://en.wikipedia.org/wiki/Metropolis-adjusted_Langevin_algorithm)
      * [Phyics of energy based models](https://physicsofebm.github.io/)
     
11. **Generative 3D Models** -
      * [Lecture](https://github.com/USFCA-MSDS/MSDS-631-GenAI/blob/main/mesh_generation.pdf) [reference](https://arxiv.org/pdf/2301.11445), [github repo ref](https://github.com/1zb/3DShape2VecSet)
      * [Code](https://github.com/USFCA-MSDS/MSDS-631-GenAI/blob/main/MeshAutoEncoder.ipynb)
        
           
12. **Graph Generative Models**
      * [Graph Variational AutoEncoders Lecture](https://github.com/USFCA-MSDS/MSDS-631-GenAI/blob/main/GVAE.pdf) [Code](https://github.com/zfjsail/gae-pytorch/tree/master)
      * [Great intro to graph rep learning](https://www-cs.stanford.edu/people/jure/pubs/graphrepresentation-ieee17.pdf)
      * [Graph RNN](https://github.com/USFCA-MSDS/MSDS-631-GenAI/blob/main/deep_graph_generation_.pdf)

## Grading
This course will involve several homework assignments and a final project focused on generative AI. Attendance and participation, homework assignments, and the final project will be graded as follows:

- Quizes: 5%
- Homework Assignments: 45%
- Final Project: 50%

# Homeworks

Only work on the homeworks posted here. Do not work on the homeworks before they are posted here.

- [HW1](https://github.com/USFCA-MSDS/MSDS-631-GenAI/blob/main/HW1.md)
- [HW2](https://github.com/USFCA-MSDS/MSDS-631-GenAI/blob/main/HW2.md)
- [HW3](https://github.com/USFCA-MSDS/MSDS-631-GenAI/blob/main/HW3.md)


# Course Project:

## Overview

This course will involve a final project focused on generative AI. Your final project will account for 50% of your total grade and will be completed in three tasks: the project proposal, a Jupyter notebook documenting your work, and a recorded presentation.

## Final Project

### Task 1: Project Proposal, Data Selection, and Data Description (5%) (due check Canvas)

In this task, you will submit a project proposal that includes the following components:

- **Project Proposal**: Outline the objectives and goals of your project. Describe the problem you intend to address using generative AI techniques and your overall approach.
- **Data Selection**: Detail the sources of your data and explain why these sources are suitable. Discuss any preprocessing steps required.
- **Data Description**: Provide a comprehensive description of the data, including format, size, attributes, and any inherent challenges or limitations.

### Task 2: Jupyter Notebook and medium post (35%) ( due check Canvas )

You will create a comprehensive Jupyter notebook that documents your project, including the following components:

1. **Data Preprocessing (5%)**: Describe the methods and steps used to preprocess and prepare the data.
2. **Model Implementation (10%)**: Detail the architecture and implementation of your generative AI model. Include code snippets and explanations of your model choices and any modifications.
3. **Methods (5%)**: Explain the algorithms, techniques, or frameworks used in your project.
4. **Experiments and Results (10%)**: Present your experiments and results using performance metrics, visualizations, and analyses.

### Task 3: Recorded Presentation (10%) ( due check Canvas )

You will deliver a recorded presentation explaining your project, including its objectives, methodology, results, and conclusions. This presentation should not exceed 10 minutes and should involve all team members.

## Generative AI Project Ideas

Here are 20 project ideas for your generative AI project:

1. **Image Generation**: Train a Generative Adversarial Network (GAN) to generate realistic images from random noise.
2. **Text-to-Image Synthesis**: Develop a model that generates images based on textual descriptions.
3. **Image-to-Image Translation**: Use a model like CycleGAN to translate images from one domain to another (e.g., transforming summer landscapes to winter landscapes).
4. **Style Transfer**: Create a model that transfers the artistic style of one image onto another while preserving the original content.
5. **Music Generation**: Train a model to compose original music pieces.
6. **Text Generation**: Develop a model to generate coherent and contextually relevant text, such as poetry, stories, or news articles.
7. **Speech Synthesis**: Build a model to generate human-like speech from text input.
8. **3D Object Generation**: Use a generative model to create 3D objects or shapes.
9. **Face Generation**: Train a model to generate realistic human faces.
10. **Super-Resolution**: Develop a model to enhance the resolution and quality of low-resolution images.
11. **Video Generation**: Create a model that generates short video clips based on given inputs.
12. **Handwriting Generation**: Train a model to produce realistic handwritten text in various styles.
13. **Chatbot Creation**: Develop a conversational AI that generates human-like responses.
14. **Fashion Design**: Use generative models to create new clothing designs.
15. **Image Inpainting**: Build a model that can fill in missing parts of an image seamlessly.
16. **Data Augmentation**: Generate synthetic data to augment a dataset for training other machine learning models.
17. **Recipe Generation**: Develop a model that creates new recipes based on ingredient lists.
18. **Game Level Generation**: Use a generative model to design new levels for video games.
19. **Code Generation**: Train a model to generate code snippets based on natural language descriptions.
20. **Art Creation**: Use generative models to create new pieces of digital art.



## Important Information

- Ensure your project is well-documented and reproducible.
- Your Jupyter notebook should be well-organized and easy to follow.
- Your recorded presentation should effectively communicate your project's objectives, methods, and results.

Good luck with your final project!

## Textbook

- "Generative Deep Learning, 2nd Edition" by David Foster. [Pytorch repo](https://github.com/davidADSP/Generative_Deep_Learning_2nd_Edition/tree/main)
## other resources
- [GenAI tutorials](https://github.com/microsoft/generative-ai-for-beginners)
