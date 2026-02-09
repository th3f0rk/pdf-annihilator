# PDF Annihilator Architecture

FEB 8 2026

---

## What?

The design of PDF Annihilator is for it to be a modular framework of various computer vision models 
that allow it to systematically break down documents into their simplest form and deterministically reconstruct the documents in structured JSON.

I chose this design framework because I believe that the hard task is going from documents to strucutred data. I call this `Document Transpilation`. 
It is the practice of transpiling the visual data represented in documents into a strucutred data that can be used in data pipelines or product integrations.

---

## How?

The main vision models are trained from the Donut base model. When I first explored PDF Annihilator I was able to briefly get the model to ouput some JSON but I made a lot of mistakes on the way.

Steps:
1. First we need to write spec sheets and plan this thing out properly instead of just getting after it and training models.
The training of models will be handled passively and is only effective if we know what we are training for and how we need to train the models

2. Once we have a clear design path to follow to make an MVP we will first finish Data Annihilator V2 and ensure we can reliably create documents and ground truth alongside those documents

3. Once our training data pipeline is solved we will create a systematic bootstrap plan that will be used to bootstrap each model we train. This allows us to systematically train models
to the same specifications and expectations. This will help down the line and ensure all models have the same base performance.

4. Before we start training models we have to harden the pipeline from document to strucutred output. The primary questions are with the PaddleOCR models that handle the bounding boxes and labeling.
We have to not only make those first but ensure they do their job correctly. We should also experiment with the depth of these models and see how accurately we can break things up into. 
If we can accurately go word by word we do that because it could be an enterprise feature.

5. We will go doctype by doctype starting with the most common (paragraph and general text). For the MVP we should start with paragraphs and have that fully implemented as the initial mvp. 
This will help prove the product if we need funding and ensure we get more money without giving up a lot of equity. Tables are the next thing to happen since it will be an abstraction upon 
the general text model (as will most of our models).

6. Once we have a model pipeline that works we have to string it together into an mvp. Once I am happy with how this pipeline performs on consumer hardware we can start designing the GUI. 
At this point we shift from model training to product design and implmentation. This process should be executed perfectly and to the fullest extent so we do not have to chase our tail. 
Models will be trained passively alongside the design process.

7. Once we have a GUI we give it to Blue Cedar Financial as our first beta tester as they will have a free perpetual license. We also start a general beta test program among trusted users and developers.
During this time we fine tune models but more importantly we design product implementations such as a Simple CRM so we are consumer facing from launch. Once this is done we launch.

8. On launch we target SMB and consumer markets with agressive pricing or bundles to get users in the door. This is a naturally sticky product with a magical feeling UX. 
These customers will likely stick around and upgrade plans down the lines. Our goal is not so much ARR or MRR as it is pure user base. 
The value of this product is in its strategic aquisition value not necessarily the product performance.

9. Post launch we prioritize user growth over all else and take enterprise opportunities as they come. We are preparing for an aquisition not a fight. We want to get as many contracts in the door as possible.

10. Let them come to us, not the other way around. Companies should try to aquire us because they are scared. This maximizes the return on our investment in terms of time and effort. 
We build the framework, scare all the incumbents then steal their money and go make more money in stable industries like Real Estate.

---

## Why?

Document transpilation has the potential to become the future of how we work with documents. This is because the current system is deeply flawed and the trajectory it is headed is sub optimal,
as there is no evidence of heading towards document transpilation. PDF Annihilator is meant to introduce this to the world and make a lot of money on it now. 
I believe that it is a framework that would push many people and SMBs into the modern age. It will open new doors and new product opportunities. It could change the world of documents.
I will not be there for the whole journey. I plan on selling out because I want to take that money and build other ventures and have security. To me what PDF Annihilator will end up as if 
I sell doesn't matter much because I will have the financial foundation to do anything and be free. I don't need to eek out everything out of PDF Annihilator. The legacy and financial base alone are enough.
