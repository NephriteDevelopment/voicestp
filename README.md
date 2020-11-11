# voicestp
A standard audio transfer procedure made by Nephrite for Nephrite

# How it works
VoiceSTP converts your microphone input into a raw Opus stream using https://github.com/hraban/opus and http://www.portaudio.com/

Portaudio is a cross platform audio input/output manager that allows us to take in microphone data as a stream which we can feed into opus. After converting the audio stream to Opus it is then ready to be manipulated as a Stream. We can include functions to remove specific wavelengths for more audio manipulation and noise cancellation/leveling. This is handled at a client level which is then ready to be passed through any network protocol you desire!
