Unity iPhone Speaker Fix
========================

When using microphone input, Unity iPhone switches audio output to the earpiece speaker, 
instead of the usual speakerphone speaker. As a result, all the audio in game suddenly 
becomes very quiet, even at max volume. In particular, this is problematic for games 
which include voice-chat. 

How-To
======

Simply install the Unity package, and add a call to `iPhoneSpeaker.ForceToSpeaker()` 
just after you call `Microphone.Start()`


