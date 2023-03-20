# Mashup-Using-Multithreading
Mashup performs the following tasks:

1. Download N videos of X singer from “Youtube” [N can be any positive number and X can be any singer e.g. sharry maan]
2. Convert all the videos to audio
3. Cut first Y sec audios from all downloaded files [Y can be any positive number]
4. Merge all audios to make a single output file.

#### Run the program through command line as :

`Usage: python <program.py> <SingerName> <NumberOfVideos> <AudioDuration> <OutputFileName>`

`Example: python mashup.py “Sharry Maan” 20 20 audio-output.mp3`

### Multi-Threading
This project has been created using the concept of multi-threading.

Multi-threading is a programming concept that allows multiple threads of execution to run concurrently within a single process. A thread is a separate path of execution within a program that can perform a specific task independently of other threads. By using multi-threading, a program can utilize the resources of a CPU more efficiently and can perform multiple tasks simultaneously.

Multiple threads have been created to faster the process of downloading.

Multi-Treading reduced the process time significantly.
### Screenshots:

Terminal:

<img width="614" alt="image" src="https://user-images.githubusercontent.com/72342649/226313015-76f23074-8631-4693-9309-d7835979c12c.png">

Folder is created on desktop containing the final mashedup audio file:

<img width="607" alt="image" src="https://user-images.githubusercontent.com/72342649/226313114-c833d871-26da-4607-8c34-2ad492a121c7.png">

Video Folder:

<img width="609" alt="image" src="https://user-images.githubusercontent.com/72342649/226313198-a1419de1-d6d6-4d47-a1a6-24b6415cd4ea.png">

Audio Folder:

<img width="623" alt="image" src="https://user-images.githubusercontent.com/72342649/226313276-ae6024e9-54cb-4789-97f1-89ca890219b8.png">

Folder made after cutting the audios:

<img width="614" alt="image" src="https://user-images.githubusercontent.com/72342649/226313345-fd206478-af58-4ead-ab60-d59ddb7fcfb5.png">

Output file:

<img width="463" alt="image" src="https://user-images.githubusercontent.com/72342649/226313456-67a5a119-f32c-4f45-a1af-0484ddb7163d.png">

### Applications
Mashup could be used in various applications such as:

Music Production: This could be used by music producers to create new remixes or mashups of popular songs by a specific artist. They could download multiple videos of the artist from Youtube, extract the audio, and then use the cut and merge features to create a new, unique audio file.

Podcasting: Podcasters could use this to create a highlight reel of interviews or discussions they have had with a particular guest.

Entertainment Industry: This could also be used in the entertainment industry to create promotional material for upcoming concerts or events.
