
------------


# Socket-Voice
## Python Script that allows multiple people to communicate over the internet using their microphones for voice chat
------------


Aim : Voice chat using Socket Programming (TCP) and PyAudio module

------------

# Note : requires PyAudio and Port Audio modules

------------


### Port Audio : 
- PortAudio is a portable audio I/O library designed for cross-platform support of audio.
- It uses a callback mechanism to request audio processing. 
- Audio can be generated in various formats, including 32 bit floating point, and will be converted to the native format internally.

------------


### PyAudio:
- PyAudio provides Python bindings for PortAudio, the cross-platform audio I/O library. 
- With PyAudio, we can easily use Python to play and record audio on a variety of platforms.

------------


##### Installation For Submodules (prebuilt) :

    sudo apt install -y pyaudio
    sudo apt install -y portaudio19-dev

------------


#### USED TECHNOLOGIES:
- Python 3
- PyAudio
- Socket Module (standard library)
- Threading Module (standard library)

------------

### How to operate
1. Run server.py or server.exe specifying the port number.

2. To use this program across the internet (using Cloud services such as AWS or GCloud), create an instance and make sure to keep it publically accessible. Using its external IP (using PuTTy) or using the instances SSH terminal instantiate and run the server.py file. 

3. Clients can connect across the internet by entering your public IP (external IP address of the server) and the port the machine is running on or in the same network by entering the IP displayed on the server.

4. If the client displays "Connected to Server", you can now communicate with others in the same server by speaking into a connected microphone.

------------



