RTC Portal X is the "Remote Desktop" part of - what should have become - RTC Portal v6.

RTC Poral X is compatible with Delphi 7 - 10.2, but requires the (full) RealThinClient SDK (version 8.0 or later) to compile.

RTC Portal X includes a "Lib" folder with all units required for "Remote Desktop" functionality, using a new platform-independent video encoder/decoder implementation and the new RTC Gateway and Gate Client components from RTC SDK v8 for communication, plus ... a "Demos" folder with a simple Gateway, a simple Client with Desktop HOST (button - used to Host your Desktop and INVITE other Clients by entering their 6-digit ID) and Desktop View/Control functionality (click in list, after receiving the invitation), and ... a Desktop Capture Test Project (for testing Screen capture and video Encoder/Decoder implementation).

RTC Portal X is NOT a replacement for RTC Portal v5! Unlike RTC Portal v5, which is a full-featured product for remote customer support, RTC Portal X only has basic Remote Desktop functionality. No chat, no file transfer, no user access control, no automatic login, no service version of Gateway or Clients. And ... there are NO packages in RTC Portal X, so you can open all Demo Projects after unpacking the files, but ... you still have to add the "Lib" folder to your Library search path if you want to compile the included Demos.
