# medvill-custom

In this Repository, I have referred to author J.H. Moon's [MedVill](https://github.com/SuperSupermoon/MedViLL) .

This is a Vision Language Model, built on the Transformer architecture, specifically BERT.

I have fine-tuned the model on the MIMIC-CXR dataset, with the aim of using it to classify diseases into multimodal data: X-ray images and text describing that x-ray.

In addition, I also apply QLoRA to use a large language model to be able to generate treatment methods suitable for the disease predicted above.