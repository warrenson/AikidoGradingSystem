# Notes

## Data Types

### 01 Grading Test Form Data
Data for each grading test form

Probably use XML flat files, as there wont be many.

### 02 Grading Test Results
The result(s) of a processed grading test form.

#### OUTPUT1:

Render PDF of result form.

#### OUTPUT2:
Write flat file in some *data_object* format, e.g. JSON

Should have a results database for collation of this data.


## UI
Essentially dynamic tabs each containing a grading form.

### The Form Tabs
Initially no tabs are created. User creates tab with button, chooses grading test from list.

The tabs will be done with jquery:

https://jqueryui.com/tabs/#manipulation


### The Grading Form
Form data imported from HTML form template files should work here.

http://api.jquery.com/load/

Form *submit* action writes result data flat file and renders PDF of result(sent to browser as download).


## Application
http://www.w3.org/TR/2011/WD-html5-20110525/offline.html#offline
