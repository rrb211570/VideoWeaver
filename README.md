# VideoWeaver [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

VideoWeaver is a React component that allows you to do video editing. I personally wanted to make this software so that it would be easier to make tech demos and record my LeetCode sessions for VOD review. Rather than work through one software to record videos and another to edit them, this component will handle everything for you in one place, and is completely free!

## Features
* MomentMaker: Can record screen and capture audio input to produce a video
* Content editing stage: Edit individual video, picture, and audio files
* Video editing stage: Combine different media sources into an output video
* API's to download/upload content via Drive, Dropbox, and desktop
* Can upload edited videos to your YouTube channel in a single click

## Installation
You can import VideoWeaver into an existing React project, by using npm.

npm install videoweaver [features]

[features]:  
-m : MomentMaker  
-c : Content editor  
-v : Video editor  
-s : functionality to upload/download from Drive, DropBox, and desktop  
-y : functionality to upload to YouTube channel  

Note: Omitting flags will default to include all features

Ex. npm install videoweaver -mcv  
&emsp;&ensp;npm install videoweaver -s  
&emsp;&ensp;npm install videoweaver  // installs all features

We're trying to yield as many use cases for VideoWeaver as possible, so you can mix and match features to match your needs.

All that's left is to instantiate VideoWeaverPanel, host your project, and you're ready to start video editing!
    
## Contributing

We expect contributors to adhere to the [code of conduct](https://github.com/rrb211570/VideoWeaver/blob/main/CodeOfConduct.md). 

Check out our [contributing guide](https://github.com/rrb211570/VideoWeaver/blob/main/ContributingGuide.md) to learn more about our process and how you can become a contributor.

# License
VideoWeaver is [MIT licensed](https://github.com/rrb211570/VideoWeaver/blob/main/LICENSE)
