# Simple DJ Simulator (Pure Data)

This is a generative music work made with [Pure Data](https://puredata.info/).

*Good headphones or speakers may help you enjoy the music more*

## Demo
- [Recorded Example Video](https://youtu.be/2SF8U9_Soc8)
- [Simplified version with VJ](https://bwyanyuuu.github.io/aesthetics/main/), visualization made by [@bwyanyuuu](https://github.com/bwyanyuuu)

## Usage
The main operations can be done with the panel below:

![image](https://github.com/chenyutpe/Pd-Simple-DJ-Simulator/blob/main/demo_img/demo_panel.png)

- Main Panel Functions:
    - Start All: Start/Stop the music
    - BPM: Set the BPM
    - 8 Buttons: Mute/Unmute each mixer channel
        - Drums, Chords, Bass, Sub Melody, Lead Melody, and 3 just for decoration from left to right, up to down.
    - LP Slider: Low pass filter on the master
        - And a switch to open/close the filter on the right.

Of course, there're many else you can play around.

For example, you can adjust the volume of each mixer channel easily with the sliders or set the number directly:

![image](https://github.com/chenyutpe/Pd-Simple-DJ-Simulator/blob/main/demo_img/demo_mixer.png)

## More Details

### Design Ideas
The motivation of this work is to make a nice interactive generative music with traditional music structure.

The "realtime" feature of generative music makes me think of DJ, so I decided to use a control panel inspired by DJ panel, or more specifially lauch pad, as the interacting method.

To make it easy enough for anyone to play with, I chose muting/unmuting each components in the music, BPM of the music, and a filter to the while music.

To be nice to hear with randomness, the notes uses equal temperament played, the melodies uses Euclidean rhythm, and the drums choose from certain patterns.

### Visualization
Since a goal of the work is to visualize with p5.js and WebPd, the work send out some signals such as the melody notes, and use only one file to connect comfortably.

To echo with the idea of DJ, the visualization idea comes from VJ.

Unfortunately, WebPd has many limitations on patches, complexity, and so on. It's hard to overcome the problems completely, so the version with visualizations is much simplified.

The great visual design is made by [@bwyanyuuu](https://github.com/bwyanyuuu).

## Special Thanks
Much appreciation to [QCGInteractiveMusic](https://www.youtube.com/@QCGInteractiveMusic)'s videos, which helped me a lot with my Pure Data knowledge and the design of patches.