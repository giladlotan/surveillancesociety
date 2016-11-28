# Surveillance Society (ssoc)
### making sense of the data trails we leave behind

- NYU - ITP
- Fall 2016
- Gilad Lotan | danah boyd

---
### Description
Data are created and collected all around us, trails left from interactions in social media, accessible through streams, feeds, APIs, and data-stores. These data are used to power a growing number of services, modeled not only off our own interactions but also interactions of our friends and larger network of connections. Even if well intended, the growing range of uses of systems that algorithmically ingest our data means there are a growing number of unintended consequences and inherent biases. In order to untangle some of these issues, we’ll dive into the literature, while running our own data analyses on captured surveillance data, from system logs, and NYPD datasets to mobile phone logs.

This is an advanced technical class. There will be a mandatory tutorial session beforehand. You are expected to be proficient in the Python programming language before the start of the class. We will hit the ground running, and move aggressively fast. We will use the iPython notebook environment, and get to know libraries such as: Pandas for time series analysis, NLTK for Natural Language Processing, and Scikit-learn for some Machine Learning. We’ll also learn to leverage existing API’s to enhance our datasets and models. There will be both reading and coding assignments every week. Your final projects will be group based.

---
### Schedule

- [11/7] Week 1: Surveillance and Privacy
    - [Technical Setup] (https://github.com/giladlotan/surveillancesociety/blob/master/setup.md)
    - For next week:
        1. Read William Whyte’s “The City”, “Performances” in Erving Goffman’s “The Presentation of Self in Everyday Life.”
        2. Complete [Social Observation Assignment] (https://github.com/giladlotan/surveillancesociety/blob/master/observation-asgn.md)
        3. Complete technical questions from [this week's ipython notebook] (https://github.com/giladlotan/surveillancesociety/blob/master/class_1.ipynb) and prepare short responses in your group for next week (5 minutes max).
- [11/14] Week 2: Seeing Ethnographically
    - For next week:
        1. Read Bowker & Star on apartheid; Enigma’s [“Who’s Counting”] (http://blog.enigma.io/whos-counting-the-history-of-the-u-s-census/)
        2. Complete technical questions from [this week's ipython notebook] (https://github.com/giladlotan/surveillancesociety/blob/master/class_2.ipynb) and prepare short responses in your group for next week (5 minutes max).
- [11/21] Week 3: Categories and Classification
    - For next week:
        1. Read Judith Donath on identity
        2. Complete technical questions from [this week's ipython notebook] (https://github.com/giladlotan/surveillancesociety/blob/master/class_3.ipynb).
- [11/28] Week 4: Signals and Knowledge
    - For next week:
        1. Read boyd & Crawford’s questions for big data
        2. Complete technical questions from [this week's ipython notebook] (https://github.com/giladlotan/surveillancesociety/blob/master/class_4_network_analysis.ipynb).
- [12/5] Week 5: Moral Boundaries
    - For next week:
        1. Complete final project!
- [12/12] Week 6: Final Project Presentations

---
### Logistics
- Class: Mondays, 9am-12pm
- Office Hours: by request 30 minutes before or after class (or via skype)
- Assignments:
    - _Reading_:
        - Each week, there will be some form of reading. We are keeping the reading short and accessible so please do it.
        - The required readings are available via Dropbox or through an online link, as indicated in the assignment section of each week.
        - We recommend acquiring a copy of ["Data Science from Scratch"] (http://www.amazon.com/Data-Science-Scratch-Principles-Python/dp/149190142X) as a supplemental resource for all technical topics covered in class.
    - _Coding_:
        - We'll use a shared dropbox folder for submitting coding homework assignments.
- Evaluation:
  - On-time attendance and class participation: 25%
  - Assignments: 25%
  - Final Project: 50%
  - _Note: Showing up more than 10 minutes late without prior notice is an unexcused absence. More than 2 unexcused absences results in automatic failure._

---
### Final Project

This is your semester-long assignment. You should know this going into the class because you must agree to do this assignment to take the class AND you must agree to comply with the rules of engagement. This assignment is not just technically challenging - it’s socially challenging. And that’s the point of this class.  It’s one thing to talk about surveillance; it’s another thing to engage in it.

On Day #1, your group will be handed a USB drive. It will contain a zipped file of data including the following three columns: latitude, longitude, and timestamp. Those are each geographic coordinates derived from the phone of your “Target.”  Together, this file reveals where your Target’s phone has been over an extended period of time.

Your assignment in this class is two-part:

1) Identify your Target. (Goal: Dec 5)

2) Build a data portrait of your Target (to be displayed and explained on December 12).

We will help you develop the skills to do this.  Ideally, you will use your sleuthing data-oriented skills to identify the full name and identity of your Target. But even if you don’t get to that level of detail, you will develop an intimate understanding of your Target’s activities and patterns.  If you successfully identify your target, you should pull social media and web-based data about your target to help you build a portrait of your Target. You can use whatever medium makes you happy to build your portrait.

Each week, we will ask you to complete mini-assignments that show that you’re working to understand your target. This is NOT an assignment that you can do last minute at the end of the semester so don’t even try. You will be working on this assignment every week with your group, and we will discuss milestones.

*Rules of Engagement*

Your Target is a real person who has voluntarily given consent to participate in this class. We take the safety and wellbeing of the Targets seriously and you must do so as well.

The following are rules of engagement. You must agree to these Rules to participate in this class. If at any point, you violate these Rules, you will be immediately expelled from the class and given a failing grade. If your violation harms the Target in any way, you may face additional consequences.

- Rule #1. You may not under any circumstance at any point ever approach the Target, the Target’s connections, the Target’s home, the Target’s place of work. This is non-negotiable so don’t even think of violating this Rule.

- Rule #2. This is a digital-only project, focused on getting data from digital records. You may not physically approach any of the venues you find through this process. For example, you cannot visit an office to see what it is. Pretend like you live on a remote island.  Google and open data are your friend.  You may pull any digital record you can *legally* get your hands on and you should document the processes in which you’ve gotten that data.

- Rule #3. You may not share any information you find about your Target - or your Target’s data - with anyone outside of the class. You must get permission before publicizing any part of this work that might result in the Target being identified or harmed. Keep the data secure and be a responsible and ethical data scientist.

This course is going to ask you to engage with ethical thinking by the vary nature of the work we are asking you to do. Be attentive at every turn to the ethical limits of what you are doing. If at any point, you are uncomfortable with what you or your classmates are doing, please contact us immediately.  We will also provide room during the class to discuss ethical issues that emerge throughout this project.


*Group Assignments*

- Group #1: Frate, Hoff, Kagan, Ma, Mehrota
- Group #2: Abrassart, Charry, Germanidis, Parr, Ruckman
- Group #3: Bachman, Kim, Kruliasuskaite, Leopold, Quach
- Group #4: Eckert, He, Huggins, Ricks, Sehgol, Soltani
