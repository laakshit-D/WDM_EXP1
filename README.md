### EX1 Creation of Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform Preprocessing
### DATE: 22-08-2025
### AIM: 
  To Create Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform preprocessing
### PROCEDURE: 
1) Open Start -> Programs -> Accessories -> Notepad
2) Type the following training data set with the help of Notepad for Employee Table.

```
--------------
Employee Data
---------------

@relation employee

@attribute name {p,q,r,s,t}
@attribute id numeric
@attribute salary {low,medium,high}
@attribute exp numeric
@attribute gender {male,female}
@attribute phone numeric

@data
p,201,medium,4,female,998877
q,202,high,6,male,889900
r,203,low,1,female,776655
s,204,medium,3,male,665544
t,205,high,8,female,554433

--------------
Weather Data
---------------
@relation weather

@attribute outlook {sunny,rainy,overcast}
@attribute temparature numeric
@attribute humidity numeric
@attribute windy {true,false}
@attribute play {yes,no}

@data
sunny,88.0,78.0,true,no
rainy,72.0,90.0,false,yes
overcast,75.0,85.0,true,yes
sunny,90.0,70.0,false,yes
rainy,66.0,95.0,true,no
overcast,80.0,60.0,false,yes
sunny,85.0,88.0,false,no
rainy,68.0,75.0,false,yes
overcast,73.0,82.0,true,yes
sunny,77.0,65.0,true,yes

```
3) After that the file is saved with .arff file format.
4) Minimize the arff file and then open Start -> Programs -> weka-3-4.
5) Click on weka-3-4, then Weka dialog box is displayed on the screen.
6) In that dialog box there are four modes, click on explorer.
7) Explorer shows many options. In that click on ‘open file’ and select the arff file
8) Click on edit button which shows employee table on weka.

### OUTPUT:
<img width="1261" height="941" alt="Screenshot 2025-08-08 113321" src="https://github.com/user-attachments/assets/cd69dee8-c5ff-4b4a-a3f3-e8ea99907fe5" />

![WhatsApp Image 2025-08-08 at 11 31 41 AM](https://github.com/user-attachments/assets/38daf447-15ff-46de-a416-40074b41857a)




### PREPROCESSING
### Procedure:
#### 1) Add -> Pre-Processing Technique:
1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Add.
9) A new window is opened.
10) In that we enter attribute index, type, data format, nominal label values for Climate.
11) Click on OK.
12) Press the Apply button, then a new attribute is added to the Weather Table.
13) Save the file.
14) Click on the Edit button, it shows a new Weather Table on Weka.

### OUTPUT:
<img width="1226" height="734" alt="Screenshot 2025-08-08 105908" src="https://github.com/user-attachments/assets/34576489-cf6a-4c8d-ac87-f6f40ea5c969" />

<img width="1227" height="733" alt="Screenshot 2025-08-08 111816" src="https://github.com/user-attachments/assets/31037fbc-1f35-49ea-b7e7-80bac605c466" />


### 2) Remove -> Pre-Processing Technique:

1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Remove.
9) Select the attributes windy, play to Remove.
10) Click Remove button and then Save.
11) Click on the Edit button, it shows a new Weather Table on Weka.

### OUTPUT:
<img width="1225" height="737" alt="Screenshot 2025-08-08 105613" src="https://github.com/user-attachments/assets/59bbbf4b-8c84-413e-a603-639ab458a91d" />
<img width="1232" height="735" alt="Screenshot 2025-08-08 111847" src="https://github.com/user-attachments/assets/d8b95dee-0fcf-4b0b-bfb6-bd5a26c97ee4" />


### Normalize -> Pre-Processing Technique:

1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Normalize.
9) Select the attributes temparature, humidity to Normalize.
10) Click on Apply button and then Save.
11) Click on the Edit button, it shows a new Weather Table with normalized values on Weka.

### OUTPUT:
<img width="1224" height="736" alt="Screenshot 2025-08-08 110010" src="https://github.com/user-attachments/assets/a20bd96b-31df-402a-a1e4-29c522cb817a" />

<img width="1224" height="732" alt="Screenshot 2025-08-08 111918" src="https://github.com/user-attachments/assets/4672023a-2858-4e40-9ffa-721113006c75" />



### RESULT: 
  Thus the program for generating employee and weather datasets has been developed, and preprocessing has been accomplished successfully.
