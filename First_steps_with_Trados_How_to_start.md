---

title: First steps with Trados - how to start
layout: default
nav_order: 4

---
FIRST STEPS WITH TRADOS - HOW TO START
===============

Since you are expected to work with Trados, it is vital to know some basic steps that need to be followed.

**TRADOS PACKAGE - HOW TO OPEN IT**

Every single project consists of several XML files that will be provided to you in a Trados package. In order to start working with it, please follow these steps:

Locate the Trados Package File: The Trados package file typically has a ".sdlppx" extension. The core part of your Trados package name is the name of the project assigned to you.

![Trados](Tradospackage.jpg)

Launch SDL Trados Studio.

Open the Trados Package: In SDL Trados Studio, go to the "File" menu and select "Open Package." Alternatively, you can use the keyboard shortcut Ctrl + O. This will open a file dialog box.
![open](First steps with Trados - how to start/openpage.jpg)
Select the Trados Package File: Navigate to the location where the Trados package file is saved, select it, and click "Open."

Review Contents: Once the package is imported, you'll see its contents in the SDL Trados Studio interface. This includes the source files, any translation memories or termbases included in the package, and other project resources.

**TRANSLATION PHASE**

Now have a look at your **translation pane**. In other words, it is the place where you need to insert your translation. Every file consists of several segments. You can see some numbers near them. 
These are the so-called matches. Here is a short overview:

| Name            | Description                                                                                                                                                      |
|-----------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 100% Match      | These segments are an exact match with a segment stored in the translation memory. This means that the entire segment has been translated previously.             |
| Context Match (CM)   | Context matches have a high degree of similarity to previously translated segments, identified by analyzing surrounding text and context.                          |
| Repetitions (light green)     | Repetitions occur when the same segment appears multiple times within a document, allowing translators to apply the translation consistently throughout the text. |
| Fuzzy Match (1-99%)     | Fuzzy matches are similar to 100% matches but with minor differences, such as variations in punctuation, terminology, or word order (percentage range between 50 and 99%).                             |
| No Match        | When Trados cannot find any similar segments in the translation memory, it categorizes the segment as a "no match," requiring translation from scratch.     
|

**SHOULD I STAY OR SHOULD I GO? HOW TO HANDLE THE TRADOS SEGMENTS**

Now try to remember the chapter devoted to project briefing analysis. Have a look at the given project requirements and check what the client ordered. If it is **translation-only**, please start with the first segment you see
and continue with all of them, checking all the content. Try to maintain consistency within the file itself as well as in the entire project. Don't forget to confirm every single segment with the "Confirm" button. Otherwise you are bound
to lose all your work results!

![confirm](confirm.jpg)

**FUZZY MATCHES - TRICKS AND BEST PRACTICES**

While it is fairly easy to handle the 100% matches and repetitions, things go a bit complicated when you encounter a fuzzy match. In such a case, Trados provides a suggested translation along with a percentage indicating the level of similarity to the stored translation. Begin by reviewing the suggested translation and the source segment to understand the context.

Compare Source and Target: Compare the source segment with the suggested translation to identify any differences. Pay attention to variations in punctuation, terminology, word order, and context.

Depending on the degree of similarity and the context, you may need to edit the suggested translation to align it with the current segment. Make adjustments to ensure accuracy and coherence with the surrounding text. Sometimes the changes may be just minor, so please be careful.

**FINAL...COUNTDOWN...NO, FINAL STEPS**

Now that you have reached the 100% score in the bottom page bar, you need to proceed differently, depending on your workflow. For more information, please see the following chapters.

![progressbar](progress_bar.jpg)
