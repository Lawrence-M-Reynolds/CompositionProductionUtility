

D Check if replacing the midi items is viable.
D Test headless production

- Prepare TDD harness
    D Create multi-voice midi file from sibelius
    D Process into separate midi items in reaper test project.
    - Create git repo with midi items and push
    - Create a library to translate the multi-voice file to the separate midi items automatically.
    - Create a test harness that will use the files for TDD with module.
    - Implement the library

- Create a spring boot application with a restful component.
- Implement the restful end-point that uses the library

- Prepare reaper template projects for different versions
- Implement the application to create based on the separate templates.

- set up raspbery pi to act as a separate server

- Create a local script to run from windows to invoke the application and generate the produced music.

