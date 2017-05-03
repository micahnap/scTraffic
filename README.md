# Traffic Light Coding Challenge
The Traffic lights are represented by a custom image view subclass. The subclass minimal state to control which images to show. State is updated via computed properties. 
The traffic lights are controlled by a custom sequencing object that is responsible for managing the time and the light sequence of the lights. The view controller uses this sequencer to control it's lights. This facade-like pattern allows for flexibility to change time and light sequences with little effort.
