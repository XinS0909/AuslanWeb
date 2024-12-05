# AuslanWeb

## AuslanWeb: A Scalable Web-Based System for Australian Sign Language Communication

Effective communication between the deaf community and hearing individuals facilitates social inclusion, equal opportunities, and the dignity of vulnerable populations.  However, Auslan, as the sign language specific to Australia, still lacks reliable tools to support effective interaction.  Existing region-specific sign language systems are constrained by limited training datasets and narrow topic domains, rendering them ineffective for bridging the linguistic gaps between sign languages and spoken languages.  To address these challenges, we propose AuslanWeb, a web-based system for translation of both isolated and successive sign language.
For the former, **AuslanWeb** achieves high-precision mapping between isolated signs (glosses) and spoken language words or phrases through a multimodal recognition system and a versatile sign language dictionary.
For the latter, it leverages the advanced contextual understanding and text generation capabilities of Large Language Models (LLMs) to support bidirectional translation between successive sign language videos and long-form spoken language.
By integrating linguistic structure with advanced AI capabilities, AuslanWeb overcomes the limitations of dataset dependency and enhances the scalability of sign language translation systems. 
The effectiveness of the system is further validated through user feedback, receiving consistent praise from Auslan experts, Australian deaf individuals, and volunteers.

## AuslanWeb User Interface

## User Interface of AuslanWeb

The user interface of AuslanWeb is designed for bidirectional translation of both isolated and successive sign language, as shown in Figure `system_UI_overall`.

Each functionality addresses a specific aspect of bidirectional Auslan-English translation:

- **Auslan Dictionary:**  
  Users can search for an English word or phrase, and the system retrieves the corresponding Auslan sign video. The results include multiple video perspectives (e.g., front view, side view) and fingerspelling representations to support better understanding and learning of Auslan signs.

- **Auslan Recognition:**  
  Users can upload an isolated sign video for recognition. The system identifies the sign and provides the corresponding English word or phrase. Additionally, it offers alternative meanings (related keywords), allowing for contextual exploration of the recognized sign.

- **English-to-Auslan Translation:**  
  Users can input English sentences for translation into Auslan. The system identifies the key glosses, determines their sequence based on Auslan grammar, and retrieves the corresponding sign videos to create a fluent signing output.

- **Auslan-to-English Translation:**  
  Users can input successive Auslan sign videos for translation into long-form English sentences. The system segments and recognizes the signs, maps them to glosses using the Auslan dictionary, and constructs grammatically coherent English sentences.

<img src="Demo_Image/UI_Design.jpg" alt="Alt text" title="The overall design of the proposed AuslanWeb user interface." width="500">


## User Interface Demonstration
The user interface of our system has been meticulously crafted to ensure accessibility, clarity, and functionality. 
The design enables users to seamlessly navigate through the key modules of the Auslan dictionary, recognition, and translation system. 
A detailed view of the interface is shown in following figure.
The user interface emphasizes intuitive navigation, responsive design, and a unified layout. 
Each module is developed to operate independently while maintaining consistent design principles, ensuring an inclusive experience for all users.


<img src="Demo_Image/UI_Test.jpg" alt="Alt text" title="User interface demonstration for Auslan Dictionary, Recognition, and Bidirectional Translation Modules." width="500">

### AuslanWeb Demo Video

[Download or play the demo video.](Demo_Video/Demo.mp4)


