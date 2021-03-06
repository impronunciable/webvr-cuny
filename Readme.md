
# VR for the rest of us

## Introduction (3:15 - 3:20)

In this workshop we are going to demonstrate how Journalists, Storytellers and non-programmers in general can enrich their stories, building VR experiences without the help of developers nor writing a single line of code.

We are going to present three tools for creating meaningful Virtual Reality experiences that work on the Google Cardboard, Oculus Rift and other headsets. This experiences are created using free, open-source software and can be embedded in your website as if it were a chart or a YouTube video.

Two of this tools does not require coding skills and the remaining is suited for JavaScript beginners.

## Requirements

- Bring a story you want to tell. It can be news, fiction, whatever you want to work with. Also have with you any assets (videos, images, audios) that can play well with the storytelling. If you don't, we'll have time to select one for you.
- A computer (we will provide the internet connection)

## The excercises

### WebVR Starter Kit - A meaningful _Hour Of Code_ (3:20 - 3:35)

The [WebVR starter kit](https://github.com/povdocs/webvr-starter-kit) is a JavaScript library aimed for JavaScript developers to create VR scenes with no effort. It's so easy that non-JavaScript developers (meaning journalists and storytellers) can use it in no time.

We are going to create our first scene using this tool.

- Go to the WebVR Starter Kit [repository](https://github.com/povdocs/webvr-starter-kit) and take a look at the documentation and the examples
- Open the [Empty JS bin](https://jsbin.com/wemipo/1/edit?js,output)
- Start playing around. You can start with:
```js
VR.floor().setMaterial('grass')
VR.sky()
```
- Try creating a scene with [this spherical video](https://povdocs.github.io/webvr-starter-kit/examples/assets/mery.mp4) and place a wooden sphere in the middle
- Play around with the tool. It's really powerful, the limit is your imagination.

### A-Frame - Mozilla's approach to VR for the web platform (3:35 - 3:45)

[A-frame](aframe.io) It's a WebVR framework by MozVR (The amazing Mozilla Virtual reality team building tools for the web) for creating VR experiences. The ecosystem is growing quickly and experiences like Washington Post [Mars](https://www.washingtonpost.com/graphics/business/mars-journey/) use it in production.

The A-frame approach is a system that creates abstraction by using entities and components in a similar fashion as HTML. In fact writing aframe code is exactly doing HTML (+JavaScript depending on the interactions).

- Go to the [A-frame](aframe.io) homepage and play with the examples. You can see the HTML code involved in each example.
- Go to the [example codepen](http://codepen.io/team/mozvr/pen/BjygdO) and play around.
- Try to replicate some of the scenes you created with the WebVR starter kit using A-frame.
- Can you spot the differences? Is this easier or harder to use than the Starter Kit?

### GuriVR - Enrich your stories with VR, not the other way around (3:45 - 4:00)

[GuriVR](https://gurivr.com) it's a tool based on the WebVR Starter Kit allowing Journalists and Storytellers to create a VR experience from a script or any text adding specific VR resource annotations.

- Go to the [GuriVR](https://gurivr.com) website.
- Go to the editor.
- Play around adding intertitles, panorama images, 360 videos and audios.

### Telling the story (4:00 - 4:30)

Content is king. We need to get the story first and then, if it makes sense, apply amazing VR resources to it. Once the story is defined we can proceed to shape our interactive version.

Let's do groups of 2 or 3, select a story you want to tell and write a sketch of the story (or the whole story if it's already written) using a Google Docs or the GuriVR editor.

After your story is done, lets add the annotations and create the experience. You can add your own assets into the editor if you need to.

We are going to use [HackDash](https://hackdash.org/dashboards/cunyvr/) for showcasing the stories created during the workshop. Once you have something working please upload it to the HackDash.

![It's alive](http://science-all.com/images/pinocchio/pinocchio-04.jpg)

## resources

- [GuriVR](https://gurivr.com)
- [A-Frame](https://aframe.io)
- [Flickr Equirectangular group](https://www.flickr.com/groups/equirectangular/)
- [WebVR starter kit](https://github.com/povdocs/webvr-starter-kit)

## Contact the author

Twitter: [@impronunciable](https://twitter.com/impronunciable)

Email: [dan.zajdband@gmail.com](mailto:dan.zajdband@gmail.com)

Website: [zajdband.com](http://zajdband.com)
