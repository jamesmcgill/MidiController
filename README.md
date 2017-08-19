# midiController
Test project using the pre-release WinRTMidi library to get input from MIDI controllers (to tune game physics variables in real-time).

This project uses the Win32 wrapper of the pre-release WinRT MIDI api (via nuget package winrtmidi.0.0.2)
https://github.com/stammen/winrtmidi

It provides a very simple class which loads this DLL and hooks an event callback to any controller input events.
