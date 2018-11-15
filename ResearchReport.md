# Research Report

##  Duet: Exploring joint interactions on a smart phone and a smart watch

### Main Points
This paper explored a way to seamlessly integrate the use of smart phones and smart watches. Chen, Grossman, Wigdor, and  Fitzmaurice identified four main areas of cross-over between the two devices: use with both devices in the background, use with the phone in the background and the watch in the foreground, use with the phone in the foreground and the watch in the background, and use with both devices in the foreground. The former two areas represent the primary ways that smart watches are already used: as an activity sensor and as a proxy for the phone, while the phone is inactive. The authors focused on ways to incorporate the smart watch while the phone remains in the foreground. They created a set of gestures relying on dual motion and orientation detection of both the watch and the phone that allow the user to use the watch as an auxiliary tool. For example, while reading and annotating text on the phone screen, the user can seamlessly switch between writing with the pad of their finger, scrolling with the side of their finger, and highlighting text with their knuckle because the orientation of the watch is distinct with each of these motions. The watch can also serve as a way to save screen space (holding a “toolbox” while the user performs a function on the screen) or provide quick access to important information while the user is on a phone call. Chen et al. implemented and tested these gestures, finding a recognition accuracy of over 97% for all gestures except for one. They also collected user feedback on specific tasks that incorporate the gestures. Users appreciated saving screen space and using their watch as a toolbox, but were less positive about features that did not add functionality to the phone, but replaced an existing task (e.g. unlocking the phone using a synchronized hand gesture while wearing the watch and holding the phone).


### My reaction
In reading the results, I was surprised to see that the gestures had such high recognition accuracy, and I am skeptical of their transference from a contrived lab setting to the real world, due to the individual differences of users. Chen et. al acknowledge this point as well, and propose using “online learning mechanisms that dynamically incorporate a new user’s data into the existing model” (Chet et al. 2014). I would be interested to see usability data incorporating these measures. Additionally, I think the goals of this project should be focused more narrowly. Because this research focuses on instances when the phone remains in the foreground, the tasks supported by this design should also focus on instances when the watch adds to, not replaces, a function of the phone. I agree wholeheartedly with the feedback of the users, and I would most likely not use the watch to replace phone-tasks (such as unlocking the screen), but would very likely use the watch as supplemental screen space or a tool box for my phone screen.

### Our design
After reading this paper, I do wish we had considered incorporating multiple pieces of hardware into our design. One of the primary limitations of a smart watch is its small screen size. My group initially envisioned users reading interpretations, but adjusted to a listening implementation due to the screen size. This is advantageous because it allows the user to engage visually with the art, but it is not an accessible design to hearing-impaired users, and if a user wishes to save an interpretation, a written copy would be more convenient. Choosing a dual phone-watch design would have allowed InterprArt to take advantage of the positive aspects of both designs and increase accessibility.

Our design does not address synchronous use of smart watches and phones, so I do not think it directly improves upon the topic of this paper. However, I do think it would be interesting for the authors to consider how wireless headphones or speech commands could play a role in their design. This would be a step away from the “duet” of the watch and phone, and toward the wireless “symphony,” as the authors mention in their discussion.


Chen, X., Grossman, T., Wigdor, D.,  & Fitzmaurice, G. (2014). Duet: Exploring joint 
  interactions on a smart phone and a smart watch. CHI ‘14 Proceedings of the SIGCHI 
  Conference, 159-168. https://doi.org/10.1145/2556288.2556955