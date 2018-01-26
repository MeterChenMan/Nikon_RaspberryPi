Nikon Type0016 Module SDK Revision.5 summary


Usage
 Control the camera.


Supported camera
 D5500, D5600


Environment of operation
 [Windows]
    Windows 7 (SP1) 32bit/64bit edition
    (Home Basic / Home Premium / Professional / Enterprise / Ultimate)
    Windows 8.1 32bit/64bit edition
    (Windows 8.1 / Pro / Enterprise) 
    Windows 10 32bit/64bit edition

 [Macintosh]
    Mac OS X 10.9.5 (Mavericks)
    Mac OS X 10.10.5 (Yosemite)
    Mac OS X 10.11.6 (El Capitan)
    Mac OS X 10.12.1 (Sierra)
    * 64bit mode only (32bit mode is not supported)


Contents
 [Windows]
    Documents
      MAID3(E).pdf : Basic interface specification
      MAID3Type0016(E).pdf : Extended interface specification used 
                                                              by Type0016 Module
      Usage of Type0016 Module(E).pdf : Notes for using Type0016 Module
      Type0016 Sample Guide(E).pdf : The usage of a sample program

    Binary Files
      Type0016.md3 : Type0016 Module for Win
      NkdPTP.dll : Driver for PTP mode used by Win

    Header Files
      Maid3.h : Basic header file of MAID interface
      Maid3d1.h : Extended header file for Type0016 Module
      NkTypes.h : Definitions of the types used in this program.
      NkEndian.h : Definitions of the types used in this program.
      Nkstdint.h : Definitions of the types used in this program.

    Sample Program
      Type0016CtrlSample(Win) : Project for Microsoft Visual Studio 2013

 [Macintosh]
    Documents
      MAID3(E).pdf : Basic interface specification
      MAID3Type0016(E).pdf : Extended interface specification used
                                                             by Type0016 Module
      Usage of Type0016 Module(E).pdf : Notes for using Type0016 Module
      Type0016 Sample Guide(E).pdf : The usage of a sample program
      [Mac OS] Notice about using Module SDK(E).txt : Notes for using SDK
                                                                on Mac OS

    Binary Files
      Type0016 Module.bundle : Type0016 Module for Mac
      libNkPTPDriver2.dylib : PTP driver for Mac 
 
    Header Files
      Maid3.h : Basic header file of MAID interface
      Maid3d1.h : Extended header file for Type0016 Module
      NkTypes.h : Definitions of the types used in this program.
      NkEndian.h : Definitions of the types used in this program.
      Nkstdint.h : Definitions of the types used in this program.

    Sample Program
      Type0016CtrlSample(Mac) : Sample program project for Xcode 6.2.


Limitations
 This module cannot control two or more cameras.
