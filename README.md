"# alcinoe-delphi11-patched" 

1) just extract alexandria_delphi11_orig_and_patched.zip into Alcinoe-master\ebbarcadero
  example:
  [c:\Your_DELPHI11_DIR\Your_Components_Dir\alcinoe-master\embarcadero\alex\11\]
  
2) add to Delphi11 SEARCH PATH options this path:
  example:
  
    c:\d11\c\alcinoe-master\source
  
    c:\d11\c\alcinoe-master\embarcadero\alex\11\patched_fmx;
  
    c:\d11\c\alcinoe-master\embarcadero\alex\11\patched_rtl\android;
  
    c:\d11\c\alcinoe-master\embarcadero\alex\11\patched_rtl\ios;
  
    c:\d11\c\alcinoe-master\embarcadero\alex\11\patched_rtl\win;
  
3) now you can recompile app for Windows32/windows64/android/ios in Delphi11 Alexandria.
  
p.s. original fmx and rtl files in archive just for see different, if you want to patch it for Delphi 11.1

p.s.s.
 if you get error like 'was compiled with a different version of':
 example:
[DCC Fatal Error] FMX.Platform.iOS.pas(17): F2051 Unit Macapi.MetalKit was compiled with a different version of iOSapi.UIKit.UIViewClass

just add to SEARCH PATH options path to folder with source of that [Macapi.MetalKit.pas], and REBUILD (not recompile) your project.
and repeat this operation for another and another units.

 
With respect,
Commanderz
 email: supercommander@ukr.net
 telegram: https://t.me/commanderz
