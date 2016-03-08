# rpi-aspnetcore
Raspberry PI docker image for ASP.Net Core

This allows you to run ASP.NET Core web applications on your Raspberry Pi with Docker.

## Setup Docker with ASP.NET Core on your Raspberry Pi

1. Download the latest Hypriot image at http://blog.hypriot.com/downloads/
2. Write this image to your SD card
3. Login to your pi with default pi credentials
4. Clone your ASP.NET core web application to any directory
5. Edit your Dockerfile to use rootdevelop/rpi-aspnetcore:1.0 as FROM image
6. Build your docker file ("docker build -t myrepo/myappname:0.1 .")
7. Run your ASP.NET application in Docker & Enjoy!

Thanks. Any questions. Let me know!
