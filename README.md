Overview-dijit-workaround-NIM097648
===================================

Workaround for NIM097648 - When resizing the window after the Overview Map widget is hidden, the Overview Map widget does not display map any more once it reopens.


So the idea is to destroy the overview dijit, then re-initialize it when extent-change and the overview dijit is hidden. 
