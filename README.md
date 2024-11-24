# Week 1 lab
## Task 1._"Live Music Archive"_😃

Almostly, I don't have a specific song or artist that I want to study, but I hope to find the answer in my upcoming music analysis experiments.
## Task 2.
**Challenges working with music data:**
+ Data fragmentation: Music data is distributed on various platforms, and copyright also restricts data access. (If you ask me to recreate a live music form the 19th century, the difficulty should not be easier than writing a 5k words essay!😂)
+ Curation difficulties: Music type, emotion, and style are difficult to record in astandardlized manner. The track list, stadium info, and audience response are all the more so.
+ Inefficiencies: Is the interoperability between platforms sufficient? So that the efficient distribution of live music is a question. Does it rely on special technologies or intermediary agencies?
  
**How live music exemplifies?**

Live music is usually brief and not repeated, making it difficult to continuously record and analyze a single performance. Moreover, there are a large number of participants in live music activities, including musicians, stage managers, ticketing platforms, audiences, etc. If there is a lack of standardlized recording methods, tremendous live music archives will be difficult to preserve, which is a cultural loss.

![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown](https://www.visitglasgow.com/imager/general/495489/Bars-with-free-live-music-stravaigin-content-block_8dc3bdbc8660ad389ec95cdf9b15d797.jpg)

**How it is presented in three types of data?**
+ Descriptive data: These data can come from event websites, social media, fan comments, etc. It includes the band members, time and location, performance theme. It describes objective background and qualitative information about live music.
+ Notated data: This can be the score or MIDI data of the performance piece. We can analyze the music structure through these and modify it. However, recording of live music is not easy and requires questioning of accuracy.
+ Acoustic data: Including on-site audio recordings, audio analysis tables, and so on. It may come from some official websites or products. Due to the particularity of live music, there may be noise and sound quality issues.
# Week 2 lab
**The difference between PDF score and converted score by Musescore**

I randomly selected a live music with red rose as the music theme on imslp as the transcription target. After transcribing, I was surprised to find some very obvious errors in the OMR engine's results! It seems that the pitch and rhythm of the entire score are consistent, but this does not hide the error. For instance: 
+ time signature: AT the beginning, 6/8 converted to 2/4.
+ G clef: A line of G clef with no meaning appeared out of nowhere, without any notes.
+ Rest note: Many sections are followed by unnecessary rests.

More errors have been shown in the images below. The first before transcription and the second after transcription. You don't realize how much you can change without comparing!

![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown](https://i.postimg.cc/63qNLr55/redrosepdf.png)
![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown](https://i.postimg.cc/WpDdsr6v/redrosemusescore.png)

**Score Editing**

I selected a page with relatively simple errors and made changes, which were basically changes in rhythm and pitch. HERE IS MY WORK!😉

![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown](https://i.postimg.cc/GpZZYZNz/redrosechange.png)
# Week 3 lab
## Task1:Export score to musicXML and MEI

The files I exported were still from the score I found in the week 2.

[Here](https://drive.google.com/file/d/1qsSnKlHmVYgaRaOJtjpepFHgSP6A47Mj/view?usp=drive_link) is my musicXML file.

[Here](https://drive.google.com/file/d/16_oeGidz8AHG0YyBEXUHQjOphFmpvyoD/view?usp=drive_link) is my MEI file.
