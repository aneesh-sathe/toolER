# Detection & Localisation of Surgical Instrument Tips using Fine-tuned YOLOv5-Large Model 

## (1) ToolER 

Rigourous Surgical Training & Practice acts as a Foundation for a Surgeon. However, the access to thorough training is not equally accessible to all Medical Students & Resident Doctors across India due to disparity in patient inflows, variability in medical cases and risk of practicing on a real patient for the first time. 

ToolER aims to address these issues by providing a means of practicing medical surgeries in a simulated environment in Augmented Reality. The approach involves recording surgical procedures conducted by expert doctors, leveraging these recordings to detect and localize the tips of surgical instruments and capture the precise hand movements of the surgeon.
The recorded data becomes a valuable resource for training purposes. During a simulated surgery, a trainee doctor's performance is evaluated by comparing the instrument tips and hand movements against those recorded during an actual surgery performed by an expert. This comparative analysis provides a robust means of assessing and refining the skills of trainee doctors in a controlled and immersive AR setting, ultimately contributing to enhanced proficiency and competence in medical surgeries.

## (2) Instrument Detection and Tip Localisation

Object detection is a computer vision task that involves identifying and locating objects within images or video frames. The goal of object detection is to recognize and draw bounding boxes around the objects of interest, along with classifying each detected object into predefined categories or classes. In the specific context of laparoscopic videos capturing cholecystectomy procedures, this process is elevated. The videos are annotated with accurate bounding boxes and class labels, detailing the various surgical instruments used during the procedure. These annotations serve as the foundation for fine-tuning the YOLOv5 model

| ![Title 1](https://github.com/aneesh-sathe/toolER/assets/117112887/dea2fa94-6e0f-43c8-8dab-39553fd2423d) | ![Title 2](https://github.com/aneesh-sathe/toolER/assets/117112887/4a2cef54-6835-4955-9a8c-36e985650922) |
| --- | --- |
| INPUT VIDEO | OUTPUT VIDEO |

## (3) Future Scope 
- Develop Augmented Reality Infrastructure for simulating the complex atmosphere of an Emergency Room (ER)
- Deploy the Solution in Medical Schools with less patient inflow / lack of complex medical cases
- Implement Reinforcement Learning from Human Feedback (RLHF) by leveraging the Experience & Skill of Expert Surgeons
