Stable Diffusion is an AI model that can create highly realistic images based on written descriptions. It works by gradually refining abstract representations into detailed visuals that match the provided text input.

The Stable-Diffusion-v1-5 model builds upon its predecessor, version 1.2. It underwent additional training using a dataset of 595,000 high-quality images from "laion-aesthetics v2 5+". This training occurred at a 512x512 pixel resolution. To enhance the model's performance with classifier-free guidance sampling, the text prompts were occasionally omitted during 10% of the training process.

Instructions:
conda env create -f environment.yaml
conda activate ldm

conda install pytorch torchvision -c pytorch
pip install transformers==4.19.2 diffusers invisible-watermark
pip install -e .

The further insturctions can be followed from https://huggingface.co/runwayml/stable-diffusion-v1-5 and  https://github.com/runwayml/stable-diffusion.

Best outputs with the below prompts:
![image](https://github.com/user-attachments/assets/e95e7915-5a0a-4c68-8d82-b3653930adb2)

1. Australian Currency With Coala
2. Russia Ukraine War
3. Teddy Bear on bike
4. Coffee in mountains

Average outputs with the below prompts: 
![image](https://github.com/user-attachments/assets/d9242fa6-876b-4e44-8228-36bef4407a0c)
1. flying beer
2. Indian flag on moon
3. flying cars
4. dairy milk tea flavour
