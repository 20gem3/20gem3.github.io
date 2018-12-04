# Some Mistakes I Made, and How I Learned to Design Ethically, Accessibly, and Effectively

At this point in my very short user-centered design career, I still would definitely not call myself an HCI expert. 
However, in the process of designing InterprArt, alongside Abby Miller and Maria Mejia, I have learned a lot about how to 
effectively design a product, and I have reshaped my mental model of what design actually is. At the beginning of this semester, I had absolutely no formal experience with design, in practice or in research. Through the process of designing an digital, auditory discussion board for use in a museum setting ( [InterprArt](https://mc-mejia.github.io/HCIGroupProject/) ) in Professor Iris Howley’s Human Computer Interaction class at Williams College, I’ve been able to identify 5 key things to consider while designing.

## Five Principles That Define My Design Process

### 1. Ethics (Butterflies and Possible Uses)

As is the case for many ethical codes, including that of the Association for Computing Machinery, Do No Harm is the central tenet that guides my design process. I think about achieving this goal in two principle ways. The first, is to consider the “butterfly effect.”  In a world that has become increasingly interconnected due to technology and communication, it’s much easier for actions in one location to affect multiple groups that are seemingly separate (because of geographical distance, role in the community, ideology, etc.). Therefore, when considering whether to create a new technology, it’s important to wonder not only how it will affect the community that it is specifically designed for, but also groups of unexpected stakeholders. For example, while we did not implement our design in this class, and therefore did not spend a significant amount of time thinking about the specifics of hardware, there are serious ethical questions to raise in regard to the manufacturing practices of large tech companies. I was led to this concern after reading about the desperate and poorly paid [Mechanical Turk workers](https://www.theatlantic.com/business/archive/2018/01/amazon-mechanical-turk/551192/), as I started thinking about fair compensation and work conditions. While both Apple and Microsoft have aesthetically pleasing and reassuring pages about responsible sourcing on their respective websites, ( [Apple](https://www.apple.com/supplier-responsibility/) and [Microsoft](https://www.microsoft.com/en-us/corporate-responsibility/responsible-sourcing)) both have been under scrutiny for the terrible work conditions in their manufacturing plants in China ([Apple Conditions](https://www.chicagotribune.com/bluesky/technology/ct-apple-china-workers-20180116-story.html) and [Microsoft Conditions](https://www.businessinsider.com/microsoft-slammed-over-child-labor-accusations-2010-4) ). I realized that I need to think globally when I wonder about the ethical ramifications of my design. Is it unethical to design an app for use on a piece of hardware that is manufactured in an unethical way? This is a large question that affects almost all computer scientists. 

Next, I try to remind myself that I cannot control the users who will interact with a potential technology. As quoted from Jurassic Park in class, “Your scientists were so preoccupied with whether they could that they didn’t stop to think if they should.” No matter how I intend my project to be used, ultimately, the users are in control of what they do with it. Therefore, thinking of all potential uses is key to ethical design. As part of our class work, we read about artificial intelligence research being applied to [drone strikes](https://glow.williams.edu/files/133121246/download?download_frd=1). AI is a perfect example of a technology that could be used to do a lot of good, but also has tremendous capacity to do great harm. Once a technology leaves the hands of the designer, the designer loses control over how it is used.
Even when designing a product as seemingly innocuous as InterprArt, considering these heavy ethical principles is important. A question that came up for us in the design process was, “What if users post profane or offensive comments?” Realistically this is a very real possibility, and it is our responsibility as the designers to put measures in place to prevent the harm that could be caused by posts like these. In our case, we decided that either human or AI moderators should screen the submitted posts before they are made public.

### 2. Accessibility (Inclusivity, Inspiration, and Logistics)

InterprArt’s audio-based design is inherently inclusive of vision impaired users. This idea was inspired by Lester Lee, Karl Bocker, and Alyssa Wang’s design for their app, [Pin](http://www.lester-lee.com/curious-places/). 

![pin earbud use](/img/karl_1.jpg)

*An image taken from the Pin website*

![interprart earbud use](/img/watch_task2.png) 

*An illustration of an InterprArt task using earbuds*

To be perfectly candid, we did not make this design decision due to accessibility concerns, but rather due to the logistics of a museum environment. It was only after learning more about accessibility that we made the connection that an auditory experience makes a museum visit more inclusive of vision impaired users. With accessibility on the forefront of our mind, we started wondering how we could intentionally increase the inclusivity of our design. After reading a 2014 paper by Chen, Grossman, Wigdor, and Fitzmaurice, I was intrigued by the possibility of phone and smartwatch integration. 

![smartwatch and phone integration](/img/integration.png)

*An image taken from Chen et al.'s paper(1) illustrating the smartwatch and phone integration*

With the larger screen of the phone, we could more easily add a more traditional written discussion board in compliment to our auditory design and increase accessibility beyond vision impaired users to deaf users and users with low mobility, for whom interacting with the small buttons on a smartwatch poses a challenge. Ultimately, my group did not make these changes because were at a relatively late stage in the design process. Adding a smartphone feature would mean completely overhauling certain aspects of our design, and we did not have user data to back up this choice. From these experiences, I learned two main things regarding accessibility. First, that it’s extremely important to keep up to date on the literature and what other designers are doing. Inspiration can come from anywhere, and if I had simply relied on my own thinking process, without consulting research and past designs, these ideas may never have occurred to me. And second, that accessibility concerns need to be integrated into the design process from the very beginning. If we had set out to create an accessible design from the outset, rather than contemplating how to make a design more accessible after the fact, we would have been much more successful.

### 3. Data, Data, Data (Build from the ground up.)

In this class, we had many opportunities to collect data to inform our design: a fly-on-the-wall observation, a contextual inquiry, and multiple rounds of usability testing. In the initial stages of research, I found myself falling into the trap of looking for data points that affirmed what I already expected, rather than taking in the information objectively. For example, in my fly on the wall observation, I looked for signs that the museum goers might feel uncomfortable in the stuffy environment, because I have experienced that myself. This is clearly a breach of the key to user-centered design: **THE USER IS NOT LIKE US**. Going back, I would have jotted down notes in a more objective way, and considered multiple interpretations after the fact. Starting from unbiased data and building up helps ensure that the design is evidence based, rather than coming from a predetermined idea of the designer.

### 4. Design and REdesign  (The best version of a bad design is still bad.)
	
Throughout much of our User Experience Research phase, my group imagine InterprArt as a mobile phone app. We put a lot of time and effort into imagining how users would interact with the app, what it would accomplish in the museum setting, how we could make the app more fun for users, and how to improve our design overall. 

![phone task](/img/phone_task2.png)

*An illustration of a task using a mobile phone, created as part of our [Design 3x4](http://mc-mejia.github.io/HCIGroupProject/Design3x4/)*

In our initial thoughts, it did not occur naturally to us that maybe a mobile phone app is not the best implementation for a museum setting. A phone puts a screen in between the user and the art, could be distracting, and is more cumbersome to carry around than wearing a smartwatch. Had it not been for the guidance of Iris, we very well may have carried on with a design for a mobile app. We would have refined and improved this design iteratively throughout the class, but the innate nature of a smartphone mobile app would have limited the effectiveness of our product. We may have reached the very best version of a museum discussion board mobile phone app, and still had a poor design. After sketching some preliminary ideas, and considering Iris’s feedback, and as well as developing [tasks](http://mc-mejia.github.io/HCIGroupProject/Design3x4/) and [storyboards](http://mc-mejia.github.io/HCIGroupProject/Design1x2/) we were able to see these advantages and disadvantages, and ultimately chose a smartwatch as the platform for our app.

![sketches](/img/GM_sketches.jpg)

*Some preliminary sketches of various designs*

### 5. Multiple Perspectives (The user is not like... the user?)

I conducted a contextual inquiry with a sophomore club athlete who had never been in WCMA before. Therefore, much of the data that I collected from him was colored by his general lack of experience with WCMA, his high energy, his dislike of quiet spaces, and his uncertainty of how to proceed. After this experience, I thought I had an idea of how the “typical” Williams student would feel in WCMA, and what purpose my design should serve. One of my group members, on the other  hand, interviewed a junior WCMA student employee, who loved art and spent countless hours in the museum. When we combined data, I realized I had to adjust my mental model. Through the process of creating an affinity diagram, we were able to zoom in on the common needs and problems faced by each of our participants. This experience drove home for me the importance of multiple data points. There is not one, real representative user, which is why companies like Microsoft create user personas and mood boards(2), as a way to encompass common traits of many users. 

![a persona mood board](/img/moodboard.png)

*An image of a mood board, taken from Pruitt and Grodin's 2003 paper on user personas*

While our group did not create a similar persona, we did refer back to each of our participants throughout the design process, saying things like, “I bet X would like that, but I don’t think Y really needs that feature…” or “That could be good for Z, but Y doesn’t use the museum that way….”  Thinking of multiple types of users helped us in our goal to make our design usable for as many people as possible.

![affinity diagram](/img/affinity_design.jpg)
*Our final affinity diagram*


(1)Chen, X., Grossman, T., Wigdor, D.,  & Fitzmaurice, G. (2014). Duet: Exploring joint 
interactions on a smart phone and a smart watch. CHI ‘14 Proceedings of the SIGCHI 
Conference, 159-168. https://doi.org/10.1145/2556288.2556955

(2)John Pruitt and Jonathan Grudin. 2003. “Personas: practice and theory.” In Proceedings of the 2003 conference on Designing for user experiences. ACM, New York, NY, USA, 1-15.
