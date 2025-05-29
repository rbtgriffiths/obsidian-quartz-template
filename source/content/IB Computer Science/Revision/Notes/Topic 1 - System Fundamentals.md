
### 1.1 Systems in organizations

##### Planning and system installation

- 1.1.1 Identify the context for which a new system is planned
    
    Before a system is designed, it needs to be identified as to what the system should do. This is the job of the systems analyst. A systems analyst looks at the existing system and tries to observe how it works. This can be done by surveying the workforce, interviewing staff, observing how the current systems works, and by looking into the documentation used and produced by the system.
    
    Once the current system and been evaluated and understood, the systems analysts will propose a new system to be created and implemented based on the needs of the company. This new system will be presented to the company in the form of a feasibility report, which they will then consider before moving ahead.
    
    The feasibility report will include: what existing infrastructure from the existing system can be used? What requirements on hardware and software will the new system have? What training would need to be in place in order to ensure the existing staff can adapt to the new system. Are there any ethical issues resulting, for example, will the new system make people unnecessary, leading unemployment?
    
- 1.1.2 Describe need for change management
    
    Without a proper plan on how the new system will successfully replace the old system, many factors will need to be considered:
    
    - Employer/employee training
    - How will the system be implemented?
    - Direct changeover? Parallel running? Pilot projects? Phased implementation?
- 1.1.3 Outline compatibility issues resulting from situations including legacy systems or business mergers
    
    Rarely any two businesses in the world use the exact same systems. So, when two businesses merge, it is a major issue to get their systems to work together. Some issues are listed below:
    
    - Language differences
    - Part of business operating in a different country than host using an older version of a system
    - If workers delegate, will their laptops work in other departments?
    - If an american and an european businesses merge, their unit systems need to be merged (one uses SI units, one doesn't)
    - Businesses not using same software environment (Microsoft Exchange vs. IBM Lotus Notes)
- 1.1.4 Compare the implementation of systems using a client's hardware with hosting remotely
    
    **Software as a Service (SaaS):** The client does not run its own computer system to handle operations, but lends servers from the software manufacturer that are managed and maintained by the software manufacturer. A great example is SAP.
    
    Advantages:
    
    - No cost in employing personnel to maintain system
    - Software manufacturer can provide help in cases of malfunction
    - Maintenance and updating managed by software manufacturer → they have staff that fully understand the system
    - Client enjoys the professional know-how of the software manufacturer
    
    Disadvantages:
    
    - Data security issues resulting from trusting your information to someone else (loss of control)
    - Host may be in a different time zone, so maintenance can happen at uncomfortable times
    - Because host is not the user itself, user feedback is harder to get
- 1.1.5 Evaluate alternative installation processes
    
    **Parallel running:** run both the new and the old system at the same time.
    
    Advantages:
    
    - No data loss if new system fails → old system is there as backup
    - Staff can be trained in running the new system
    - Outputs of system can easily be compared with existing system → testing
    
    Disadvantages:
    
    - Costly running both systems
    - Time consuming to operate both systems
    - Pilot running: run the system in only one part of business only (like in one supermarket of an entire chain)
    
    Advantages:
    
    - If system fails, only one department affected
    - Cheaper than parallel running
    - Staff can be trained in pilot facility
    
    Disadvantages:
    
    - If system fails, work at pilot facility is affected
    - Data loss can occur when pilot system fails
    
    **Phased implementation:** the old system is being replaced part by part by the new system
    
    Advantages:
    
    - Each component of the new system can be tested before installing a new part
    - Staff can be trained in stages/ does not have to learn using the new system all at once
    
    Disadvantages:
    
    - If the implemented part of the new system fails, there is no backup
    - If the new system is very complex, introducing it in parts may be difficult
    
    **Direct changeover:** the new system replaces the old one “over night”
    
    Advantages:
    
    - Least costly
    - Does not need to run two systems parallel
    - New system is ready to run
    
    Disadvantages:
    
    - No back up if new system fails
- 1.1.6 Discuss problems that may arise as a part of data migration
    
    - Incompatible file formats
    - Incompatible or obsolete data structures Validation rules may have changed with new system, making old data unusable
    - Errors while transferring data
    - Changed character sets leading to misinterpretation
    - Changed units leading to misinterpretation (new system interprets temperature in °C instead of °F)
    - New system does not support old data storage techniques, like floppy drives
- 1.1.7 Suggest various types of testing
    
    Testing is very important in developing a computerized system, as it tries to ensure that the system works as expected. A system that does not work as expected (it is buggy) greatly reduces productivity and end user satisfaction.
    
    Testing is usually done in two stages: before the system is delivered and after it has been set up. Testing in the first stage is often referred to as **Alpha testing**, while testing in the second stage is often referred to as **Beta testing**.
    
    Alpha testing involves the engineers who develop the system testing it with data similar to real data while beta testing involves testing by real users with real data.
    
    Different types of testing can be:
    
    - Alpha testing
    - Beta testing
    - White box testing (Internal structure or algorithm is tested and known)
    - Black box testing. (Internal structure or algorithm is tested but not known)
    - Debugging (The use of manual/automatic tool to check for bugs)

##### User focus

- 1.1.8 Describe importance of user documentation
    
    User documentation is a crucial part of a system as it is the document that explains the working of the system to the user. A well-made user documentation guides the user through using the system and thus increases productivity. If the user documentation is simple, system implementation can happen faster because users require less training to learn how to use the new system.
    
    Users are non-technical people, they only need to know how to use the system. Therefore, the user documentation does not involve detailed explanations of how the system works.
    
    A user documentation usually involves:
    
    - Minimum hardware and software requirements
    - Installation guide
    - How to start the system
    - How to use different features of the system
    - Screenshots explaining main features of the system
    - Example inputs and outputs
    - Explanations of error messages and troubleshooting guides
    - Information to contact the developer of the system if an undocumented question arises
- 1.1.9 Evaluate different methods of user documentation
    
    There are different ways to provide user documentation:
    
    **Help files:** Files supplied together with the system. They can usually be called up with a button in the system.
    
    Advantages:
    
    - Accessible at any time when using the program
    - Give general instructions on how to use the system
    - Give general instructions on how to solve some major errors
    
    Disadvantages:
    
    - They can only be used after system has been installed. They don't give any help when installing the solution
    - They often only deal with very general errors
    
    **Online support:** Special web service hosted by the system's developer to provide user documentation.
    
    Advantages:
    
    - They are often extensive compared to help files
    - They get continuously revised by the systems developer to deal with the problems occuring most often (FAQs)
    - They often provide an option for live support, talking to a real human operator if a problem arises which the user documentation has no answer to
    - They often have search capabilities built-in so that users can easily search through them
    
    Disadvantages:
    
    - They are useless if users have no internet connection
    - Live support does not work quite well with users unfamiliar with computers when they have to explain their problem (“I clicked 'that' button and then something happened!”)
    
    **Printed manuals:** manuals printed on paper and supplied together with the system.
    
    Advantages:
    
    - They can be read through by users before starting to work with the new system
    - Always available
    - Give help installing the system
    
    Disadvantages:
    
    - Can be lost
    - Often limited to a little booklet supplying little information apart from how to install the system
    - May not be updated every time the system is updated
- 1.1.10 Evaluate different methods of delivering user training
    
    Training staff in using a new system is very important as productivity greatly depends on how familiar users are with a system. Therefore, good user training is an essential part of introducing a new system.
    
    **Self-instruction:** users reading a manual or watching a tutorial, or randomly doing something in the system to figure out how it works. This type of training is usually accessed by more experienced users who may have more confidence.
    
    **Formal classes:** users sitting in a classroom listening to an instructor who demonstrates how to use the system. This type of training is useful to train large amounts of staff as it is effective and relatively cheap, but if the size of the classes is too big, there is little time to deal with individual problems and questions.
    
    **Remote/online/personal training:** an instructor training a single user either by being in the same room or by some kind of remote connection (Skype, chat). This is the most effective way of training as training can be suited to user's needs and abilities but is very expensive compared to other types of training.
    

##### System backup

- 1.1.11 Identify a range of causes of data loss
    
    - Power out during storm
    - Defect hard-drives
    - System crashes
    - Malicious acitivities by employees or outsiders/intruders
- 1.1.12 Outline the consequence of data loss in a specified situation
    
    Example: Example: A hotel recently implemented a computerized system to manage room reservations. Reservations can be made through the web-page of the hotel or via phone. All the reservations with customer, room and reservation details are stored in a database. After a while one of the hard disks fails.
    
    Had the hotel relied on storing reservation details only on that hard disk, all the reservations would be gone now, and the hotel would have no way of knowing who had a reservation or how much each of their customers owed. They would also be unable to make more reservations until a new hard drive is acquired.
    
- 1.1.13 Describe a range of methods that can be used to prevent data loss
    
    **Regular back ups:** By copying all sensitive information on to a different medium than the one used in the system, like a second hard disk or CDs, the risk of data loss can be reduced significantly. By storing data in a variety of way and at various locations, data loss due hardware failure or malicious activity can be prevented. In the case of very sensitive information of large companies like Google, information is often duplicated on servers separated by large distances and in different climates to reduce the chance of data loss due to environmental causes such as tornados or earthquakes.
    
    **Making hard copies:** In some cases, information such as books, texts, important contracts and papers can also be printed out and archived. However, creating hard copies can be expensive and take up a large amounts space. Hard copies are also vulnerable to data loss, such as in the case of fire, flooding or natural disasters.
    

##### Software deployment

- 1.1.14 Describe strategies for managing releases and updates
    
    **Automatic updates:** the system checks automaticall for updates over the internet from time to time. If updates are available, they are downloaded and installed automatically.
    
    Advantages:
    
    - Updates get installed automatically. Inexperienced users have an easy chance to get the updates.
    - No need for software manufacturer to contact every user about the new update
    - Security patches are installed, and the system is kept more secure
    
    Disadvangates:
    
    - Users miss updates if they are not connected to the internet.
    - If updates cause a major change in the system, it may catch users off guard and reduce productivity until further training has been carried out
    - Unless updates are scheduled outside of working ours, systems can easily be put offline until the updates have been completed
    - If automatic updated or turn off, security patches may be missed and cause the system to be vulnerable
    
    **Manual updates:** the software manufacturer contacts every user about the new update and supplies the installation package to him to be installed.
    
    Advantages:
    
    - Users have more control what updates they want to install
    - Users get to know if an update brings major changes to how the system works
    
    Disadvantages:
    
    - Users might miss an update fixing security issues
    - Users might not know how to install the update
    - Users might harm system by wrongly installing update
    - Users might lose medium containing the update

### 1.2 System design basics

##### Components of a computer system

- 1.2.1 Define the terms: hardware, software, peripheral, network, human resources
    
    **Hardware:** anything within a computer you can physically touch.
    
    **Software:** the collection of programs and instructions that control the computer. Things within the computer you cannot touch.
    
    **Peripheral:** the input and output devices attached to the computer that allow it to interact with its environment and exchange information.
    
    Input peripherals:
    
    - Keyboard
    - Mouse
    - Microphone
    - Webcam
    - Scanner
    
    Output peripherals:
    
    - Screen
    - Speakers
    - Printer
    
    **Network:** two or more computers connected together in some way to share resources, such as documents or files and printers.
    
    **Human resources:** the humans operating the computers
    
- 1.2.2 Describe the roles that a computer can take in a networked world
    
    **Client:** a computer accessing resources hosted by an other computer, the server. Resources could be documents, printers, scanners etc.
    
    **Server:** a computer hosting resources to be shared across the network, like documents, printers etc.
    
    _**A computer can be both client and server in a network at the same time!**_
    
    **DNS Server:** a special type of server mapping web addresses to IP addresses allowing us to surf the web without having to look up the IP address of every website they want to visit.
    
    **Router:** a computer routing network packages between two networks usually using a different medium for information transfer, like phone cables or glass fibre connections.
    
    **Firewall:** a computer or software package monitoring and protecting the network traffic of a computer or computer network. It decides which computers get access to the network or computer based on a set of rules. It can be looked at as an analogy to the bouncer in a disco.
    
- 1.2.3 Discuss the social and ethical issues associated with a networked world
    
    - Loss of jobs
    - Through extensive networking many business activities can be outsourced to cheaper locations, like call centers in India, leading to jobs losses in home country.
    - Is it ethical to fire workers from a company because a computer system has been implemented that does the same job cheaper?
    - Digital divide: The wealth gap and lack of access to technological education may hinder many people when looking for employment
    - Reduced social interaction due to technology. Fabric of society being eroded due to less social interaction. Decline in health due to technology producing a less active society

##### System design and analysis

- 1.2.4 Identify the relevant stakeholders when planning a new system
    
    Who will be involved in the system?
    
    - Systems analyst
    - End users
    - Software manufacturer
    - Client company
- 1.2.5 Describe methods of obtaining requirements from stakeholders
    
    **Observation:** involves systems analyst walking around the organisation watching how things are done with his/her own eyes. Advantages:
    
    - Possibility of gathering first-hand, unbiased information
    
    Disadvantage:
    
    - Often people don't work the way they normally do when being observed
    
    **Interviews:** Involves the systems analyst interviewing key people within the system to find out how it works.
    
    Advantages:
    
    - Allows a lot of very detailed information to be gathered
    - People can be asked about what they don't like on the system
    - Questions can be tailored and adapted
    
    Disadvantages:
    
    - Time consuming
    
    **Questionnaries:** involves the systems analysts handing out questionnnaries for people to fill out.
    
    Advantages:
    
    - Large amount of data from a large group can be gathered
    - Quick and simple
    
    Disadvantage:
    
    - It is hard to ask the 'right question'
    - Information gathered is limited by questionnaire
    - It may not be taken seriously
    
    **Collecting documents:** involves the systems analysts looking in the documents in the archive to try to find out how the present system works
    
    Advantage:
    
    - Detailed informations about the present system can be gathered
    - Vulnerabilities can be flagged
    
    Disadvantage:
    
    - Time consuming
    - An unorganized system may be hard to understand
- 1.2.6 Describe appropriate techniques for gathering the information needed to arrive at a workable solution
    
    To be completed
    
- 1.2.7 Construct suitable representations to illustrate system requirements
    
    **System flow chart:** diagram representing how different parts of the system are linked together and how the system should work in general.
    
    ![Stockbridge_system_flowchart_example.jpeg](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/a347a706-c166-4b60-9133-b422d1ae329e/Stockbridge_system_flowchart_example.jpeg)
    
    Source: [https://commons.wikimedia.org/wiki/File:Stockbridge_system_flowchart_example.jpg](https://commons.wikimedia.org/wiki/File:Stockbridge_system_flowchart_example.jpg)
    
    **Data flow diagram:** diagram representing how information moves through the system together with identifying all relevant inputs and outputs to the system.
    
    ![page1-800px-NCRAS_data_flow_diagram.pdf.jpg](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/02b0884e-87aa-4740-8ab8-3ecb40014dc9/page1-800px-NCRAS_data_flow_diagram.pdf.jpg)
    
    Source: [https://commons.wikimedia.org/wiki/File:Stockbridge_system_flowchart_example.jpg](https://commons.wikimedia.org/wiki/File:Stockbridge_system_flowchart_example.jpg)
    
    **Structure chart:** diagram representing the organization of a system, usually in hierarchical order.
    
    ![1280px-CPT-Structured_Chart_Example.svg.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/66ee66c8-b4d7-4967-97f8-5c252667fd7d/1280px-CPT-Structured_Chart_Example.svg.png)
    
    Source: [https://en.wikipedia.org/wiki/Structure_chart#/media/File:CPT-Structured_Chart_Example.svg](https://en.wikipedia.org/wiki/Structure_chart#/media/File:CPT-Structured_Chart_Example.svg)
    
    _**UML is NOT required**_
    
- 1.2.8 Describe the purpose of prototypes to demonstrate the proposed system to the client
    
    Prototypes are abstract representations of the system, often focusing on only one or two key aspects. They are important in testing as each component of the system can be tested before implementing, and to illustrate the working of the future system to the client. An example of prototyping is a shipyard building a prototype of an icebreaker ship to test out different bow designs without having to spend large amounts of money building a ship with an eventual unworkable design. Prototypes in systems development are usually 'ghost' user interfaces illustrating the position of control elements to the user, or small programs developed to explore the working of a key algorithm in the system.
    
- 1.2.9 Discuss the importance of iteration during the design process
    
    Designing and creating the system usually happens in 5 stages: Planning, analysis, design, implementation, maintenance. This iterative process happens during the entire product life cycle.
    
    ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/559c0db7-2994-4188-b440-a5c1fd923112/Untitled.png)
    

Source: [https://sachidisanayaka98.medium.com/sdlc-methods-6b149f79d0f0](https://sachidisanayaka98.medium.com/sdlc-methods-6b149f79d0f0)

- 1.2.10 Explain the possible consequences of failing to involve the end-user in the design process
    - User may be unsatisfied with system
    - System may be unsuited to the initial expectations of the user
    - Financial loss if final system doesn’t represent the initial expectations of the user
    - Off-the-shelf software / tailored software
- 1.2.11 Discuss the social and ethical issues associated with the introduction of new IT systems
    - Digital divide
    - Firing workers because computer system can do the same job cheaper
    - Through mobile phones with access to business IT-systems, workers can be reached even out of work
    - Less social interaction due to home offices

##### Human interaction with the system

- 1.2.12 Define the term usability
    
    Usability is the property of a system that determines how easy and self-explanatory the use of the system is for unexperienced end-users. It usually measures ergonomics and accessibility of the system.
    
    Usability depends on:
    
    - Consistency of user interfaces (Windows 8 vs. 7)
    - Keeping to conventions users are accustomed to (a button with a floppy image stands for saving)
    - Keeping conventions of key combinations (CTRL+S stands for saving a document)
    - Structuring controls in a logical way
    - Include any special functions and buttons into user documentation
    - Do not include any major design changes between different versions of a system. Try introducing them bit by bit to let users get accustomed
    - A design award is not necessarily a usability award
    - Put all controls having similar functions in a group ('save' and 'save as…' buttons or the 'close, minimize and maximize window' controls)
- 1.2.13 Identify a range of usability problems with commonly used digital devices
    
    - Microsoft drastically changed user interface of Windows 8 compared to Windows 7. This confused many users.
    - Settings menus in early versions of Android were confusing and expressions were sometimes meaningless
    - Android operating system exists with many different user interfaces designed by manufacturers
    - Who knows instantly how to close an app in Windows 8?
    - Confusing design of switches on household devices
    - Buttons on a compact camera designed too small making it hard to use them correctly
- 1.2.14 Identify methods that can be used to improve the accessibility of systems
    
    **Accessibility** defines how the system can be accesses for information exchange and operation. This usually involves a keyboard, mouse and a screen. However, for some people using these methods to access the system is difficult or impossible.
    
    Ways to improve accessibility of a system:
    
    - Touch screens
    - Voice recognition
    - Text-to-speech
    - Braille keyboards
    - Braille printers
- 1.2.15 Identify a range of usability problems that can occur in a system
    
    - Slow response in a ticketing system
    - Irresponsible touch screens in ticketing systems (constantly hitting the wrong buttons)
    - Voice recognition being the only way to interact with system misinterpreting commands
- 1.2.16 Discuss the moral, ethical, social, economic and environmental implications of the interaction between humans and machines
    
    - There used to be a lot of secretarians but now computers do most of the work.
    - Many factory jobs lost to automatization.
    - A robot can even wash your car today…
    - Today, huge supercomputers are burning energy to handle the interpretation of voice commands on speech recognition systems like Siri
    - Consumerism has lead us to change our electronic devices almost every 2 years when new editions are released. This creates huge amounts of toxic electronic waste.

_Content originally created by [Matyas Mehn](https://dokuwiki.matyas.rocks/doku.php?id=start) and adapted/updated with permission under the Attribution-Share Alike licence._