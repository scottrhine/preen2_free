# preen2_free
Editing software to help authors improve their docx files

Preen version 2.88.0 ©2017 Scott Rhine
This software may be used on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
KIND, either express or implied. This tool analyzes a docx file to help eliminate problems
before sending it to an editor. This version generates a file with the same name and location
but with a suffix added (like _spell based on the options) and suggestions in comments.
If more than a couple of buttons are clicked, the results will have the suffix _preedit.docx.
The first commmand will take about 18 seconds, but later commands will be much faster.
This is not a replacement for hiring a human editor to check your work. Some document viewers
may show odd spacing. Report problems or request new features via ScottRhineBooks@gmail.com

To use, select the desired docx document by browsing, then click the Analyze button. 
By clicking the radio boxes, you can include or exclude functions.
+ spelling - Highlights words not recognized by the dictionary and rules engine of the program.
             Groups compound or hyphenated words which may be combined to form a single
             word, such as pickup or pick-up. Note that often the spelling choice depends on
             intended meaning and context(to a vehicle, a bar line, or a lifting), which is why 
             human examination of each is necessary.
             Also finds possible contractions inside quotes.
+ rlevel - Reading level. Presents a summary at the start. Draws attention to every chapter that is
             harder than average or too long. Highlights any sentences too long or difficult.
+ repeats - Highlights all words (other than common nouns which may be the subject of the paragraph)
             that repeat within a 30-word span.
             Also highlights three-word phrases repeated too often throughout the document.
+ adverb - Highlights most used adverbs in your document. Also draws attention to sentences that begin
             with And, But, and Or.
+ punct - Highlights possible extra or missing punctuation and grammar.
+ said - marks dialog tags that attract attention (stylistic).
+ POV - enforce point of view for a third-person novel.
The buttons are in this order for a reason, because spelling affects part of speech, reducing the
reading level usually eliminates adverbs, and so forth.

Special credit is given in version 2.3 for additions from the public domain dictionary Dict12 by Alan Beade.
NOTICE: The docx4j library used for reading and writing docx files are derivative works of
OpenXml4J, which is copyright Wygwam and available under two licenses, BSD and Apache License,
Version 2.0 (ASLv2). http://openxml4j.svn.sourceforge.net
Several supporting libraries for OpenXml4J (xmlgraphics-commons, commons-io, commons-logging,
and log4j) are Copyright © 2012 by The Apache Software Foundation, also licensed under the
Apache License, Version 2.0. These are bundled with PreEdit for user convenience.
