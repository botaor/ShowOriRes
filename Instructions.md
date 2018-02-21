<!-- View this file with a Markdown editor (eg: http://markdownedit.com) -->
# Instructions


## Introduction
In this file we are going to see how to generate the result files using the [OE2010][OE2010] software.


## OE2010 set up
The easiest way is to install OE2010 on the computer that will control the TVs. On the settings of the software, configure it to connect to the computer that has the database of the event you are managing.

Then open two windows with the preliminary results and choose the categories you want to show on the left column in one window, and the categories you want to show on the right column on the other window. One easy way to split the categories is to choose men on one side and women on the other.

Publish the results of the two windows to files `res1.html` and `res2.html` respectively. You can now open the `OriResults.html` file to see how the results look.


## Formatting the output
All of this formating is done on the layout of the results sheet. Remember that after you change the layout you will have to publish the results and refresh the browser to check the modifications. These modifications will have to be done on both results windows. But first concentrate on getting one of them right, and then just copy the formatting to the other one.

The first task in formatting the output is choosing which columns you want to show. Remember that you will have a limited space to show the results. So remove any unnecessary information (like Year Born).

Then choose the size of the table that will fit in the columns of the TV. To do this increase the size of the individual columns until you get the whole column in `OriResults.html` occupied with the results.

Now play around with the columns widths in OE and with the font size inside `OriResults.html`. Try different things until you get a result you are happy with. Remember to do the same for the other results window.


## Automatically generating results
All that is left to do is to have OE2010 regenerating the results pages automatically. For this go to the preliminary result windows and choose the automatic report. 

Choose the time interval you want. A value of 2 minutes is about right. Choose to publish the report and make sure you choose the file name `res1.html` for one window, and `res2.html` for the other.


## Final check
Now look at the TVs and make sure it is showing all the categories that you want. To make sure the results are being refreshed, look at the status time of the preliminary results. They should be updated every time the page reaches the bottom and refreshes.



<br><br><br>
Written by [Rui Botão][rui].<br>
Feb 2018


[rui]: mailto:rui@ruibotao.com "Rui"
[OE2010]: http://www.sportsoftware.de/ "OE2010"
