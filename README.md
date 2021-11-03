# javascript30-drumkit
The first day of the Javascript30 challenge, creating a keyboard drumkit. 

Objective 
- To create a mapping between the computer keyboard and drumkit audio files
- Embed audio content in a single page HTML application

Questions
- How to link external audio files in HTML?
- How to play a sound on a keypress?


Reflection
- I was able to link audio file to a keypress event! 
- I had an issue with my stylesheet not being linked correctly, but not really sure where the issue is yet (Open problem)
- My implementation was clunky, as I needed to rely on indexing through the keycodes. A better approach would be to use the keycodes and define them as custom data properties on the HTML elements. Then I could reference both the sounds and audiofiles from the keycode directly. 
- Not sure what the difference between document vs window is when referring to eventListeners
- 
Outcomes
- Completed project but without CSS styling as there was an unresolved issue to do with browser-sync (I think), the stylesheet wouldn't link for unknown reason(s)
