On November 19th 2018, I co-hosted my first NYC PyLadies event alongside Antonia Blair, which was also the first of a monthly Ladies Study Group series. The event was hosted by Equinox and was a great success with 20 attendees, many attending their first PyLadies event ever! 

![Study Group](/nyc-pyladies-study-group/photos/20181119_studygroup.jpg)

> "I love that overall, Pyladies provides a safe and welcoming environment for women of such diverse backgrounds!"


### What is the purpose of the study group?
It is a regular gathering for PyLadies of all levels to work on solo projects or in collaboration with one another. It is a welcoming space where any Python related question is fair game, beginner or advanced, or in-between. The overarching goal is to foster a community where attendees can share coding tips, cool python finds, or short tutorials, set realistic goals, and encourage one another.

### How does this series differ from past NYC PyLadies study groups? 
PyLadies has hosted study group events in the past and they have been a great success because the community is made up of individuals who are eager to collaborate and support one another. Attendee feedback from the past events has suggested that the lack of structure essential for any study group event have made it difficult for members who are just starting out and/or those looking for new collaboration opportunities. Futhermore, if study groups aren't offered regularly, it is difficult to establish continuity and foster growth.

With this study group series we hope to provide the right balance between structured networking and free-form coding time. We take feedback seriously and are open to adapting the structure of the evening to the needs and wants of the community.

### A summary of the evening. 

#### SHOW AND TELL
We hope to encourage attendees to share something that interests them: a Python coding tip, interesting article, short tutorial, etc. Whether a beginner or expert we hope that everyone feels comfortable contributing. Being the first event of the series, Antonia and I prepared things to share in hopes to demonstrate the broadness of what attendees are encouraged to share. 

> 1. **Open source discussion**, led by me, Melissa Ferrari <br> 
> I shared my first accepted pull request to an open source for Project Jupyter from the Open Data Science Inclusion Sprint, an full day event hosted by NumFOCUS DISC Program and Two Sigma ([EVENT LINK](https://blog.jupyter.org/disc-sprint-nyc-2018-548780d0f40)). <br><br><div class="center"> <blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">EVENT NEWS: Still some spots left in the NYC DISC Sprint for making your first-time <a href="https://twitter.com/hashtag/OpenSource?src=hash&amp;ref_src=twsrc%5Etfw">#OpenSource</a> contribution on October 26! Join <a href="https://twitter.com/micronova?ref_src=twsrc%5Etfw">@micronova</a> and <a href="https://twitter.com/steve_silvester?ref_src=twsrc%5Etfw">@steve_silvester</a> for a day of fun and learning with <a href="https://twitter.com/hashtag/JupyterLab?src=hash&amp;ref_src=twsrc%5Etfw">#JupyterLab</a>! <a href="https://twitter.com/hashtag/discsprint?src=hash&amp;ref_src=twsrc%5Etfw">#discsprint</a> <a href="https://t.co/cT0k8kmABY">https://t.co/cT0k8kmABY</a></p>&mdash; Project Jupyter (@ProjectJupyter) <a href="https://twitter.com/ProjectJupyter/status/1054439711362637826?ref_src=twsrc%5Etfw">October 22, 2018</a></blockquote></div> 
> I spent the beginning of the day getting familiar with the current issues in the JupyterLab project and deciding which issues would be realistic to tackle in one day. To solve the [issue](https://github.com/jupyterlab/jupyterlab/issues/5271) I chose, I needed to familiarize myself with the [Typescript](https://www.typescriptlang.org) language. By the end of the day I only changed two lines in the codebase ([check out my changes](https://github.com/jupyterlab/jupyterlab/pull/5542/files)) but it felt good to make my first contribution to Jupyter, a tool that I have been using for 5+ years. Overall, making my first contribution took a long time, was more difficult than I had expected, and I was lucky to have assistance from Project Jupyter contributers at the event. Going forward, now that I understand the workflow better, I think I will be able to tackle more challegning problems. <br><br> 
> More takeaways from the conversation:
> - Some PyLadies use contributing to open source as a tool for understanding practical code designs within larger projects
> - **Contributing to open source documentation is an important and often overlooked task.** We all use softwarre documentation and well written documentation can make all the difference when using an open source library.
>  
> 2. **Customize your command prompt**, led by Antonia Blair <br> 
> Antonia shared a series of articles and resources she found for personalizing your terminal on a Mac with colors, fonts, and emojis:hatched_chick:! She shared a [blog post](https://medium.com/@joshuaxavier/how-to-customise-your-command-prompt-to-include-an-emoji-647e1f3e4027) on how to customize your command line prompt with an emoji and a [website](https://misc.flogisoft.com/bash/tip_colors_and_formatting) with the list of colors you can use to customize. <br><br>
>In her own `bash_profile (~/.bash_profile)` she included a unicorn emoji, pink heart, and regular dollar sign with the following code. <br>
> ```bash
> export PS1='🦄 \e[95m❤\e[0m $'
> ```

The SHOW AND TELL ran overtime, which ultimately cut into the hacking/coding portion of the event. For the next event I will be sure to keep better track of the timing!

#### INTROS AND NETWORKING TIME 

[Felice](https://www.linkedin.com/in/feliceho/) and [Sanchita](https://www.linkedin.com/in/sanchitamajumdar/) shared some of the interesting engineering and data science projects from the Equinox tech team and emphasized their teams' focus on creating a member experience that is as seamless and pleasant as possible. We learned about the work culture at Equinox, including the group fitness classes (:muscle: are you surprised?), and some of the amazing contributions that both Felice and Sanchita have made in their positions as engineers at Equinox.

In addition to the functional space, the event sponsor Equinox was kind enough to provide pizza and soft beverages for the event, and Felice brought a homemade pumpkin pie.

>To learn about job opportunities at Equinox, follow [THIS LINK](http://tech.equinox.com/careers/digital/) or you can reach out to the technical recruiter [Hannah Schreck](hannah.schreck@equinox.com).

We went around the room to give attendees the opportunity to introduce themselves, share a little about their experiences with Python, and finally what they hoped to accomplish for the evening. There were some interesting trends amongst attendees:
- Many people had never coded in Python and hoped to learn from some starter materials
- There were a few journalists in the room
- A significant number of attendees were interested in chatbots
- Some wanted to learn or improve their proficiency in a specific visualization libraries
- Someone brought a regular expressions textbook to practice 

#### HACK/CODING
Based on our goals set for the evening, people separated into pairs and groups with similar interests or worked on solo projects. We also included a list with some [inspiration for things to work on](https://github.com/mferrari3/nyc-pyladies-study-group/blob/master/inspiration.md) if attendees hadn't come with any prior tasks or ideas. The purpose for the list is to have an dynamic repository that members can use to share their favorite resources. 

A piece of feedback we received was that the list contains too many buzzwords and does not include clarifying desriptions.

#### WRAP UP
We lost track of time and forgot to do the ten minute wrap up at the end of the event. We would like to try to incorporate this into the next study group because it could be helpful for community members to share their accomplishments with the group and take note of whether their own expectations were realistic. 
