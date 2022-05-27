# VideoWeaver [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

VideoWeaver is a React component that allows you to do video editing.
* MomentMaker: Can record screen and capture audio input to produce a video (useful for making tech demos and LeetCode VOD review)
* Content editing stage: Edit individual video, picture, and audio files
* Video editing stage: Combine different media sources into an output video
* API's to download/upload content via Drive, Dropbox, and desktop
* Can upload edited videos to your YouTube channel in a single click

The goal of this project is to make it a LOT easier to create tech demos and prepare for LeetCode interviews, by having all of the work done in one place. Rather than work through separate products to record videos and edit them, this component will handle everything for you, and it's free!

## Installation
You can import VideoWeaver into an existing React project, by using npm.

npm install videoweaver [features]

[features]:  
-m : MomentMaker  
-c : Content editor  
-v : video editor  
-s : API's to upload/download from storage  
-y : API to upload to YouTube channel  

Note: No flags defaults to downloading package with all features

Ex. npm install videoweaver -mcv  
&emsp;&ensp;npm install videoweaver -s  
&emsp;&ensp;npm install videoweaver  // installs all features
    
All you need to do next is to instantiate VideoWeaverPanel, host your project, and you're ready to start video editing!

You'll notice that you can import very basic features that can be channelled towards developing a completely different product; this is to yield as many use cases from VideoWeaver as possible.
    
## Contributing

We expect contributors to adhere to the [code of conduct](https://github.com/rrb211570/VideoWeaver/blob/main/CodeOfConduct.md). 

Check out our [contributing guide](https://github.com/rrb211570/VideoWeaver/blob/main/ContributingGuide.md) to learn more about our process and how you can become a contributor.

# License
VideoWeaver is [MIT licensed](https://github.com/rrb211570/VideoWeaver/blob/main/LICENSE)
