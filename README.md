# Welcome to my portfolio! Some of images are uploaded by postimage!
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
## Task 1:Export score to musicXML and MEI

The files I exported were still from the score I found in the week 2.

[Here](https://gdx5249.github.io/MCA-2024/scoreweek2.musicxml) is my musicXML file.

[Here](https://gdx5249.github.io/MCA-2024/scoreweek2.mei) is my MEI file.
# Week 4 lab
## Task 1.
I selected the elements from Tuesday's group activity and analyzed them using jsymbolic, obtaning the following data. (The music piece was from week 2)
+ Pitch class histogram: 0.2456
+ Number of pitches: 40
+ Number of pitches class: 10
+ Range: 60
+ Strong tonal centres: 2
+ Mean pitch: 60.26
+ Mean pitch calss: 5.672
+ Most common pitch: 62
+ Most common pitch class: 2
+ Interval between most prevalent pitches: 5
+ Pitch variability: 10.89
+ Most common melodic interval: 2

## Task 2.
![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown](https://gdx5249.github.io/MCA-2024/IMG_20241206_174013.jpg)
# Week 5 lab
## Task 1: Create a Metadata "Warehouse"

Based on Music Scholarship Online metadata standards & MEI documentation standards, I created my own list. The list is organized according to the characteristics of live music and is divided into two main sections. Here's my list.
### 1.Basic information about music content
+ Title: The name of the performance or event.
+ Date: The date of the performance to help the audience understand the time context of the event.
+ Artist/Band: The musician or group involved in the performance.
+ Venue: The name of the performance venue, which may include the city and country. (The same show at a different venue can be quite different!）
+ Performance Duration: The total duration of a live performance.
+ Genre: The musical style involved in the performance to help the audience filter the performance of interest.
+ Ticket Info: Ticket price range and links to purchase tickets (if applicable).
+ Publisher: The name of the organization responsible for the publication.
### 2.Transcription process
+ Unique Identifier: Assign a unique ID to each show the identity of the described material and for easy database management.
+ Copyright Information: Ensure that content is used in accordance with copyright regulations.
+ Pubplace: The name of the place where a bibliographic item was published.
+ Narrative: Describe the use of transcription.
+ Accessbility: Describe the commonality of the data and possible difficulties.

If I really want to manage a large number of MEI files, such a list obviously has room for improvement.

![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown](https://i.postimg.cc/9FxYNc3B/female-analyst-listening-music-enjoying-late-work-planning-financial-report-with-diagrams-analytics.avif)

### Audience analysis
+ Music fans: Find details about a specific artist or shows.
+ Researchers and scholars: study concert history, cultural impact, etc.
+ Live show organizer: Learn the details of other shows for future planning.
+ Music analyst: Obviously! An excellent tool for expert research and exchange.

## Task 2.
I changed the original MEI document, including adding publisher, composer, and arranger (i.e., myself) and annotating the date. Download it [HERE.](https://gdx5249.github.io/MCA-2024/scoreweek5.mei)
# Week 7 lab
## Task 1.
I updated the last week metadata file "scoreweek5.mei", [HERE](https://gdx5249.github.io/MCA-2024/scoreweek7.mei.txt) is my week 7 MEI file. And I add classification, genre, seriesStmt.

## Task 2.
<div class="copyright-container">
    <h2>Ah! May the Red Rose Live Always!</h2>
    <p><strong>Composer:</strong> Foster, Stephen</p>
    <p><strong>Year/Date of Composition:</strong> 1850 - Baltimore: F.D. Benteen</p>
    <p><strong>Dedication:</strong> Miss Mary M. Dallas</p>
    <p><strong>Editor:</strong> Robert A. Hudson</p>
    <p><strong>Publisher Info.:</strong> Robert A. Hudson</p>
    <p><strong>Copyright:</strong> Creative Commons Attribution 3.0</p>
    <p><strong>Composer Time Period:</strong> Romantic</p>
    <p><strong>Instrumentation:</strong> voice, piano</p>
    <p><strong>Encoded by:</strong> Dongxuan Gao, Glasgow, 2024</p>
</div>

# Week 8 lab
## Task 1.
| Title              | Artist              | Composer     | Identifier    | Genre           | Source           | File format   | Number of channel| Sample rate   | Bits per sec   | Duration    | Date                
|:-------------------|--------------------:|-------------:|--------------:|----------------:|-----------------:|--------------:|-----------------:|--------------:|---------------:|------------:|--------------:|
| One more saturday night| Grateful Dead | Matthew Vernon | gd1977-10-07.sbd-set2.miller.79020.sbeok.flac16              | Rural pop                |Live Music Archive|.mp3           |2                 | 44100hz              | 32000               |  5:45           |1977.10.07
| Don't let me aside | tedeschi trunks band |Bob Hundertmark | ttb2024-10-04    | Blues                |Live Music Archive|.mp3           |2                 | 44100hz              | 32000               |  5:03           |2024.10.05
| Wild blue | John mayer | laststopsc |  jm2023-10-21.nak.crown.mix.flac16            | Pop                |Live Music Archive|.mp3           |2                 | 48000hz              | 32000               |  3:51           |2023.10.21

## Task.2
### One more saturday night
![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown](https://i.postimg.cc/hG86k4Hf/grateful-dead-part.png)
![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown](https://i.postimg.cc/zBJ68Zrp/grateful-dead-img-part.png)

### Don't let me side
![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown](https://i.postimg.cc/4y0S6YhF/tedeschi-trunks-part.png)
![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown](https://i.postimg.cc/W3WWVdSb/tedeschi-trucks-band-img-part.png)

### Wild blue
![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown](https://i.postimg.cc/4x6WdLw0/wild-blue-part.png)
![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown](https://i.postimg.cc/tgrwqv4j/john-mayer-img-part.png)

### Advantage of time-frequency analysis
I think waveform analysis can not fully reflect the characteristics of a signal. When we look at a waveform analysis diagram, we can clearly see the amplitude change over time, but it seems that the frequency is ignored and not so easy for us to read. Time-frequency analysis can locate the specific time when the frequency change occurs and reveal the change law of the signal in the local area. In the case of wild blue (only part of the picture is shown), when moving the middle area, we can see that there are new hot spots on the high frequency part, which means that there may be new sounds or signal instability. When you listen to the [MP4](https://gdx5249.github.io/MCA-2024/wild_blue.flac) file of this music, you will find that the original vocals appear because he is a solo track. This shows that through time-frequency analysis, complex signals can be visually represented as two-dimensional images, which makes it easier for people to understand the nature of signals.
# Week 9 lab
## Task 1.
This week, I load three new pieces of music, here are transformations by sonicvisualiser. (From left to right is: Spectrogram, Mel Frequency Cepstral Coefficients, Chromagram) 
+ Music Alone Shall Live (Spectrogram)

![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown](https://gdx5249.github.io/MCA-2024/IMG_20241206_170224.jpg)
+ Cantonese Traditional Music (Mel Frequency Cepstral Coefficients)

![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown](https://gdx5249.github.io/MCA-2024/IMG_20241206_170550.jpg)
+ Turn up the Music (Live at AS220) (Chromagram)

![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown](https://gdx5249.github.io/MCA-2024/IMG_20241206_170836.jpg)
## Task 2.

# Week 10 lab
