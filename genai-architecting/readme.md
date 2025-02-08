# Design requirement and Considerations


## Requirements
### Business Requirements
- The language portal should provide users with easy to use interface to learn language
- the portal should provide a GenAI assistance in making it east to learn the new language
- the assistant should not be directly helping student with answer but rather focus on providing tips and help for student to find answer
- the portal should ensure that the interface allows users to select different languages or different expertise level fo student in perticular language
- the portal allows teachers to upload their ouwn language course material to create more tailered training based on teachers style and their own material
- The key to help people learn language is to make it easy to understand basic and foundation structure 
    - The interface should display vacabulary list to user after each sentence prctice request
    - the interface should also limit the response to be more concise 
    - the interface should not help with answers but rather ecorage student to provide answer and the interface can validate it while helping student to correct any mistake by giving hints and tops
- The interface should not allow users to ask any other questions than the language learning
- The request and response from LLM should be ensured to be free of any elicit language with proper guradrail around it

### Technical Consideration
- The portal should keep track of users chat and ensure there is continuation of the conversation
- The inteface should also limit calls to LLM model to recude cost of the platform
- The platform should utilize and integrate any custom data sources with ease and ensure its easy for teacher to uplaode their doucment o customize the learning approach to their student
- The system should implement necessary measure to secure the portal
- The system should adopt practices to provide consistant response time to all users

### Data requirement
- The system should ensure peoper storage of user data to ensure security and privacy
- The frequently uesd data should be stored in more accessible and performent system



## Design Consideration and Tenets
- The System should adopt the responsible AI practices
- The system will consider adoption of differnt GenAI mode or atleast allow benchmarking different model to find most suitable one
- Cloud First - To ensure the system can scale on demand and allow optimizing cost to only pay-as-you-go
- Global solution - Allow seamless experience to all user across global
- Secure - Allow secure login experience and encryption of data in transit and rest
- Personalization - Create a more personalized experienced by capturing and storing users course progresses and conversations histories
- Integration - Adopt integration best practices to optmize external integrations
