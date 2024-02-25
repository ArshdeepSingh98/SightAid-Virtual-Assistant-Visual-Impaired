This project is associated with Arizona State University, released under CSE 535: Mobile Computing course. For access to the complete source code, please contact me at my [email](mailto:asroideva@gmail.com) address.

# SightAid: Virtual Assistant for Visually Impaired
Duration: Sept 2023 - Nov 2023

SightAid is a mobile application designed to address the unique challenges faced by the visually impaired community. The application integrates a Braille keyboard and an Object Detection module to enhance daily experiences and promote inclusivity.

## Project Details:
1. **Braille Keyboard Subsystem**:

Architecture:
- Input Processing: Integrates physical buttons and gestures for user inputs.
- Braille Intermediate: Processes user inputs to generate Braille intermediate.
- Database Query: Queries a Braille-to-English database for translation.
- Translation: Converts Braille intermediate into natural language text.
- Communication: Provides a versatile and accessible means of communication.

Objective: Effortless text generation through a user-friendly interface, catering to the communication needs of visually impaired users.

2. **Object Detection Subsystem**:

Architecture:
- Image Capture: Utilizes the device's camera to capture images.
- Frame Processing: Sends captured images in frames to a Convolutional Neural Network (CNN) module.
- CNN Module: Employs advanced computer vision techniques for object detection.
- Label Generation: Generates labels for detected objects.
- Audio Feedback: Converts object information into real-time audio feedback using Mutex to access shared resource and provide audio feedback in a cooldown period

Objective: Empowers users with real-time awareness of their surroundings through audio feedback, addressing challenges in object recognition.

# Skills
- Mobile App Development in Android Studio Giraffe using Kotlin and Java
- Sensor Integration and Understanding
- Convolutional Neural Networks (CNN)
- Database Management for Braille Keywords
- Real Time Processing of images and audio feedback

# References
- Šepić, Barbara, Abdurrahman Ghanem, and Stephan Vogel. "BrailleEasy: one-handed braille keyboard for smartphones." Assistive Technology. IOS Press, 2015. 1030-1035.
- Church, Alex, et al. "Deep reinforcement learning for tactile robotics: Learning to type on a braille keyboard." IEEE Robotics and Automation Letters 5.4 (2020): 6145-6152.
- Alnfiai, Mrim, and Srini Sampali. "An evaluation of the brailleenter keyboard: An input method based on braille patterns for touchscreen devices." 2017 international conference on computer and applications (ICCA). IEEE, 2017.
- Eom, Tae-Jung, Jung-Bae Lee, and Byung-Gyu Kim. "Design of Smart Phone-Based Braille Keyboard System for Visually Impaired People." Convergence Security Journal 12.1 (2012): 63-70.
