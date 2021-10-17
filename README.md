# Variance_Analysis

> An Excel report generator for Inventory Variance in Adaco, just drag and drop!

**What's the use of this?**

>Every end-of-month, I spend an insumountable amount of time &#8987; (two to four hours, depending on distractions&#128530;) flipping over 60+ pages &#128196; of inventory reports, looking for duplicates items in our system generated pdf. Unfortunately importing this pdf document into a workable format like excel never quite achieves the expected result, columns positions and descriptions doesn't match, a lot processing is involve just to get this report in a workable format. 

>After learning Pandas from my Udacity course, I decided to create an app that automates the tedious processing of this document. My month-end processes &#128197; is more smoother and faster. This saves me and other managers hours. Mistakes are easily spotted &#128270; and corrected &#9989;.   

**How I built this?**

>I started by converting this document to a csv then converted it to a pandas DataFrame, from here I dropped unneccessary columns and rows. Then, write and save this DataFrame to an excel sheet, complete with time that its generated and name of the specific outlet. After generation, this excel report will auto-download and completely ready for analysis &#xe32e;. 

**Libraries used**:
* glob
* pandas
* excelwriter
