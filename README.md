# RasPi-Cam-Record-Stream
This package can be used to split stdin data stream to be written to a file (for storage) and also be output to stdout as well. It's used to get video data input from the Raspberry Pi NOIR camera and redirect the video data to a recorded data file and also STDOUT for online streaming using VLC.

## Setup
Install VLC
~~~~
sudo apt-get install -y vlc
~~~~
Clone Repo
~~~~
git clone <repo>
~~~~
Build
~~~~
cd <repo dir>
make
~~~~
Run
~~~~
cd  <repo dir>
./cam-stream.sh
~~~~
