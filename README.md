# Video recorder 

_Currently work in progress_

An electron app to test out video and audio recording capabilities. 

Eg if you want to record an audio or video file, get an audio or video preview usin the system's input (webcam and mic). And then save/export the file when done.

The app is designed in such way that it should also work in the browser. eg github pages, to promote code portability. 


## Resouses used

Some of the most relevant resources consulted to put this together. Altho is mostly came down to get an understanding of `getUserMedia()` and `MediaRecorder()` and combine  [Treehouse project][Treehouse_getUserMedia] with [MDN web dictaphone project][Web_Dictaphone].

- [MDN `MediaDevices.getUserMedia()`](https://developer.mozilla.org/en/docs/Web/API/MediaDevices/getUserMedia)
- [tutorialspoint "Electron - Audio and Video Capturing"](https://www.tutorialspoint.com/electron/electron_audio_and_video_capturing.htm)
- [html5rocks "Capturing Audio & Video in HTML5"](https://www.html5rocks.com/en/tutorials/getusermedia/intro/)
- [Treehouse "Accessing the Device Camera with getUserMedia"][Treehouse_getUserMedia]
- [MDN Media recorder](https://developer.mozilla.org/en-US/docs/Web/API/MediaRecorder)
- [Web dictaphone][Web_Dictaphone]
- [Electrong DesktopCapturer](https://github.com/electron/electron/blob/master/docs/api/desktop-capturer.md) _altho not used_
- ["How to use the camera with Electron Framework (create a snapshot) and save the image on the system"](http://ourcodeworld.com/articles/read/134/how-to-use-the-camera-with-electron-framework-create-a-snapshot-and-save-the-image-on-the-system)

## Try it out

``` 
npm install

```

```
npm start
```


## TODO

- [x] Ad video preview
- [ ] do option for audio or video, eg check box. 
- [ ] refactor `onSuccess` fuction into smaller helper functions. 


<!-- ref -->

[Web_Dictaphone]: https://github.com/mdn/web-dictaphone)
[Treehouse_getUserMedia]: http://blog.teamtreehouse.com/accessing-the-device-camera-with-getusermedia