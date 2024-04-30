<div align="center" id="top"> 
  <img src="./.github/app.gif" alt="Motion Docker" />

  &#xa0;

  <!-- <a href="https://motiondocker.netlify.app">Demo</a> -->
</div>

<h1 align="center">Motion Docker</h1>

<p align="center">
  <img alt="Github top language" src="https://img.shields.io/github/languages/top/Leandro-Bertoluzzi/video-server-docker?color=56BEB8">

  <img alt="Github language count" src="https://img.shields.io/github/languages/count/Leandro-Bertoluzzi/video-server-docker?color=56BEB8">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/Leandro-Bertoluzzi/video-server-docker?color=56BEB8">

  <img alt="License" src="https://img.shields.io/github/license/Leandro-Bertoluzzi/video-server-docker?color=56BEB8">
</p>

<p align="center">
  <a href="#dart-about">About</a> &#xa0; | &#xa0; 
  <a href="#rocket-technologies">Technologies</a> &#xa0; | &#xa0;
  <a href="#white_check_mark-requirements">Requirements</a> &#xa0; | &#xa0;
  <a href="#checkered_flag-starting">Starting</a> &#xa0; | &#xa0;
  <a href="#gear-configuration">Configuration</a> &#xa0; | &#xa0;
  <a href="#memo-license">License</a> &#xa0; | &#xa0;
  <a href="https://github.com/Leandro-Bertoluzzi" target="_blank">Author</a>
</p>

<br>

## :dart: About ##

Simple video webserver, can be used for:
- Share a video in the local network.
- Together with Ngrok or similar, share a video with anyone outside your network.
- Emulate a camera webserver, for integration testing.

## :rocket: Technologies ##

The following tools were used in this project:

- [Motion](https://motion-project.github.io/)
- [Docker](https://www.docker.com/)

## :white_check_mark: Requirements ##

Before starting :checkered_flag:, you need to have [Docker](https://www.docker.com/) installed.

## :checkered_flag: Starting ##

```bash
# Clone this project
$ git clone https://github.com/Leandro-Bertoluzzi/video-server-docker

# Access
$ cd video-server-docker

# Run the container in detached modes
$ docker compose up -d

# The server will initialize in <http://localhost:8081>
```

## :gear: Configuration

By default, it streams the test file `/camera/video/mock.mp4` in a loop. You can change the video source by modifying the variable `netcam_url` in `motion/config/motion.conf`.

For further configuration details, please read the [Motion docs](https://motion-project.github.io/motion_config.html).

## :memo: License ##

This project is under license from MIT. For more details, see the [LICENSE](LICENSE.md) file.


Made with :heart: by <a href="https://github.com/Leandro-Bertoluzzi" target="_blank">{{YOUR_NAME}}</a>

&#xa0;

<a href="#top">Back to top</a>
