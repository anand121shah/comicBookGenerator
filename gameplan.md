### Steps:

1. **Requirements Analysis**: 
    - Define what features your app will have.
    - Consider technical constraints like latency, storage, and API rate limits.

2. **Technology Stack**: 
    - Backend: Python frameworks like Flask or Django
    - Frontend: JavaScript frameworks like React or Angular
    - Language model: GPT-4 API or similar
    - Image generator: MidJourney API or similar

3. **Architecture Design**: 
    - Consider using microservices for modularity.
    - Use queues for asynchronous tasks like image generation.

4. **API Integration**: 
    - Integrate GPT API for text generation.
    - Integrate image generator API for illustrations.

5. **Algorithm for Comic Creation**:
    - Develop an algorithm that takes user input to guide the comic's story.
    - Use the language model to generate dialogues and narration.
    - Use the image generator to create corresponding scenes.

6. **Frontend Development**: 
    - Create an intuitive UI for users to input initial settings, view generated comics, and make adjustments.

7. **Backend Development**: 
    - Implement API calls, data storage, and the core algorithm.
  
8. **Testing**:
    - Unit tests for core components.
    - End-to-end tests for the complete flow.

9. **Deployment**:
    - Choose a cloud service to host your app.

10. **Iterate**:
    - Use analytics and user feedback to improve.

### Challenges:

1. **Cohesion**: Ensuring that the generated text and images make a coherent comic.
2. **Customization**: Providing enough options for users to customize the comic without overwhelming them.
3. **Resource Intensive**: Generating images and text in real-time can be computationally expensive.
  
### Skills Needed:

1. **Full-Stack Development**: For web app development.
2. **Machine Learning and NLP**: For working with language models.
3. **API Integration**: To connect with GPT and image generating services.
4. **DevOps**: For deployment, scaling, and monitoring.
