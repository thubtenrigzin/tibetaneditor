# tibetaneditor

This PyQt5 project is a beta version of readability editor for the Tibetan language.

The readability editor assesses the readability of a text by highlighting words according to their level of difficulty. Levels of frequency are defined by analysing the frequency of words in a given language.

The beta version allows users to:

1. write or paste text in the editor
2. segment and highlight the text by clicking on the segment icon

To test the tool, paste the text from test_source.txt in the editor and click the segmentation icon. The result should look like this:

![test](test_result.png)

Features comming soon:

- level list selection + color picker
- POS tagging
- spell-checking
- rules and vocab list editing for segmentation/POS tagging/spell-checking
- suggestion of spelling correction
- suggestion of vocabulary alternative

## Release note

- Version: 0.2

- Changelog
	
	* POS Tagging
	* Level List Color Selection
	* Words Counting
	* Highlighter Optimized
	* Optional Display by Spaces or Tags

- Version: 0.3

- Changelog
    
    * Tagging by clicking on the part of speech
    * Fix the highlight problems in tagging and re-segment
    * Add warning when switching modes from plain text to other

