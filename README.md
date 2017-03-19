# pi-camera

- Followed tutorial on http://www.techradar.com/how-to/computing/how-to-build-a-raspberry-pi-security-camera-1321441

- Uses Dropbox-Uploader (https://github.com/andreafabrizi/Dropbox-Uploader) to upload every picture after motion is detected into Dropbox.
- Run: v4l2-ctl --list-formats-ext (sudo apt-get install v4l-utils) to know your supported Web Cam resolutions.
- Run: v4l2-ctl -D to get camera information
- Run: sudo systemctl enable motion to enable motion daemon to run when pi starts
- Run: sudo service motion restart/status/start/stop
- Run lsusb
