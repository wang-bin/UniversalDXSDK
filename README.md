# Universal DirectX SDK
Starting with Windows 8, the DirectX SDK is included as part of the Windows SDK. The June 2010 is the last release. It's convenient for most cases. However, sometimes it's not suitable for using DirectX SDK in this way.
* Normally, developers use the Windows SDK accompanied with Visual Studio. When a new Windows SDK comes out, people doesn't upgrade it separately. So new features in DirectX can't be utilized.
* W32api in MinGW are not updated frequently. Using official DirectX SDK in MinGW causes many compiling errors and warnings.

The goal of this open source project is build an universal DirectX SDK. It can work with multiple versions of Visual Studio, MinGW, and other compilers.

# Contribute
As an open source project, Universal DX SDK benefits greatly from both the volunteer work of helpful developers and good bug reports made by users. 

# Links
Project page: https://github.com/gongminmin/UniversalDXSDK