This is a repository to download g'mic-pdn dll used for g'mic-pdn plugins for paint.net which was built via Windows x64.

Installation:

    1. Open the GmicPDN.zip
    2. Extract the entire content into one of those locations

    C:\Program Files\paint.net\Effects
    C:\Users\User\Documents\paint.net App Files\Effects

-----------------------------

To install GmicPdn effect plugins, there are two methods of doing so.

Method A)

    1. Make sure that there are enough GmicPDN folder copies. Then, rename them to the name of the effect plugins.
    2. Extract deps.json, and the dll file directly into the renamed GmicPDN folder.

Method B)

    1. Extract deps.json, and the dll file directly into the GmicPDN folder.
    
Method A allows for avoidance of breaking incompatibility at the cost of space. However, the downside is that new GmicSharpNative builds will be required. Method B will ensure easy installation of updated plugins as they are updated with the new GmicSharpNative builds in mind.


