-----------------------------------------------------------------
     NITGEN eNBSP SDK Professional (eNSearch Engine) README
-----------------------------------------------------------------
            Copyright (C) 1998-2013 NITGEN&COMPANY Co., Ltd.


============
Introduction
============
NITGEN eNBSP SDK Professional is intended to provide the high-level fingerprint authentication functionality for developing any kinds of fingerprint authentication software applicationsintegration with any application that requires fingerprint authentication. 
NITGEN eNBSP is based built on the NITGEN Fingerprint API specifications designed by NITGEN.
This SDK included eNSearch Engine.
	

============
Installation 
============
Only administrator can install/uninstall NITGEN eNBSP SDK Professional.

1. Insert the "NITGEN eNBSP SDK Professional" installation disk.
2. Execute setup.exe in root directory in installation disk.
3. Click NEXT button on WELCOME dialog.
4. Click YES if you agree with Software License Agreement.
5. If you do not agree, click NO and exit the installation.
6. On the CHOOSE DESTINATION LOCATION dialog, enter a destination folder and click NEXT.
7. Click NEXT button on the SELECT PROGRAM FOLDER dialog.
8. Then, it starts copying files.

* You must receive license of eNSearch from company before using SDK.
* The eNSearch SDK supported only WindowsNT/2000.

===============
installed Files
===============
Then, the following files are copied.

Window System directory(x86)
- NBioBSP.dll
- NBioBSPCOM.dll
- NBioNFIQ.dll
- NSearch.dll
- NImgConv.dll

Window System directory(x64)
- NBioBSP.dll
- NBioBSPCOM.dll
- NBioBSPCOMLib.dll
- NBioNFIQ.dll

SDK Bin directory(x86)
- NBioBSP.dll
- NBioBSPCOM.dll
- NBioBSPCOM.cab
- NBioNFIQ.dll
- RegNBioBSP.exe
- NBioBSPDemo.exe
- NBioBSP_UITest.exe
- NBioBSP_IndexSearchTest.exe
- NBioBSP_DataExporter.exe
- NBioBSP_DataImporter.exe
- NImgConverter_Test.exe

SDK Bin directory(x64)
- NBioBSP.dll
- NBioBSPCOM.dll
- NBioBSPCOMLib.dll
- NBioNFIQ.dll
- RegNBioBSP.exe
- NBioBSP_DataConvert.exe
- NBioBSP_Demo.exe
- NBioBSP_IndexSearchTest.exe
- NBioBSP_RollTest.exe
- NBioBSP_UITest.exe

SDK dotNET directory
- NITGEN.SDK.NBioBSP.dll

SDK Skins directory
- NBSP2Kor.dll
- NBSP2Eng.dll
- NBSP2Jpn.dll

SDK Inc directory
- NBioAPI.h
- NBioAPI_Basic.h
- NBioAPI_CheckValidity.h
- NBioAPI_Error.h
- NBioAPI_Type.h
- NBioAPI_Export.h
- NBioAPI_ExportType.h
- NBioAPI_IndexSearch.h
- NBioAPI_IndexSearchType.h
- NBioAPI_ImgConv.h(x86 only)
- NBioAPI.bas(x86 only)

SDK Lib directory
- NBioBSP.lib
- NBioAPI_CheckValidity.lib
- NBioNFIQ.lib
- NImgConv.lib(x86 only)

SDK Samples directory(x86)
* Library
- DLL           : Sample program source code using NBioBSP.dll
- COM           : Sample program source code using NBioBSPCOM.dll
- dotNET        : Sample program source code using NITGEN.SDK.NBioBSP.dll
- NImgConv      : Sample program source code using NImgConv.dll
- Export        : Sample program source code for data conversion using NBioBSP.dll
* Language
- VC6           : Sample program source code using MS Visual C++ 6.0
- VB6           : Sample program source code using MS VisualBasic 6.0
- Delphi        : Sample program source code using Delphi 5.0
- ASP           : Sample web program source code using ASP
- C#            : Sample program source code using MS Visual Studio.NET 2003, C#

SDK Samples directory(x64)
*Library
- DLL		: Sample program source code using NBioBSP.dll
- COM		: sample program source code using NBioBSPCOM.dll
- dotNET	: sample program source code using NITGEN.SDK.NBioBSP.dll
*Language
- Sample_COM_CSharp.sln		: Sample program source code using MS C# (Using COM)
- Sample_DLL_VC2008.sln		: Sample program source code using MS C++ (Using DLL)
- Sample_dotNET_CSharp.sln	: Sample program source code using MS C# (Using dotNET)
- Sample_dotNET_VB.sln		: Sample program source code using MS VB.NET (Using dotNET)

eNSearch Bin directory(x86 only)
- NSearch.dll
- NSearchTest.exe
- VolNoReader.exe

eNSearch Inc directory(x86 only)
- NBioAPI_NSearch.h
- NBioAPI_NSearchType.h

eNSearch Samples directory(x86 only)
* Library
- DLL           : Sample program source code using NBioBSP.dll
- COM           : Sample program source code using NBioBSPCOM.dll
- dotNET        : Sample program source code using NITGEN.SDK.NBioBSP.dll
* Language
- VC6           : Sample program source code using MS Visual C++ 6.0
- VB6           : Sample program source code using MS VisualBasic 6.0
- Delphi        : Sample program source code using Delphi 5.0
- C#            : Sample program source code using MS Visual Studio.NET 2003, C#
