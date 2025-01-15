# CSE134B-SS20-HW1
# Name: Julio Rivas
# PID: A18059395


https://juliorivas.netlify.app/

# Part 1

##  Question 2. Chrome DevTools - Network (4 points)

Requests by Content Type
Total # of Requests: 

1 - Document Type

1 - CSS

1 - JS

1 - Font

10 - Images

1 - MP4 

1 - icon

Total: 16

**Total Bytes Sent** (i.e. the amount of data your browse receives and downloads, read this Links to an external site. for details): 6.7 MB sent
Waterfall of Requests Screen Capture:

![waterfall graph](images/waterfall.png)

## Question 3. Client-Side Inherently Insecure Demo (1 point)
![red font h1](images/redfont.png)

# Part 3

## Question 1. HTTP Response Headers + Network Analysis
1. Take a screen capture of the HTTP response headers for UCSD (the root HTML document)
   ![UCSD Response Header](images/ucsdresponse.png)
2. Take a screen capture of the HTTP response headers for UCI (the root HTML document)
   ![UCI Response Header](images/uciresponse.png)
3. What is troubling about the UCI response HTTP headers?

    The UCI response HTTP header reveals the type of server UCI uses
4. With the help of DevTools, for each page, give a rough breakdown of the % of data transferred dedicated to 

**UCI Website**
   - Documents
     - 8/77
   - Stylesheets
     - 9/77
   - Scripts  
     - 17/77
   - Fonts
     - 5/77
   - Images
     - 16/77
     - 
**UCSD Website**
5, 10, 21, 5, 32
   - Documents
     - 5/78
   - Stylesheets
     - 10/78
   - Scripts  
     - 21/78
   - Fonts
     - 5/78
   - Images
     - 32/78

## Question 2. JavaScript Off

Figure out how to disable JavaScript in your Chrome browser. Visit ucsd.edu,scripps.eduLinks to an external site., and ucla.eduLinks to an external site.. Describe the changes to these two home pages in terms of the look and functionality:

1. UCSD visual changes (screen capture)
![UCSD No JS](images/UCSDjs.png)
2. UCSD broken features (text description)
- The search bar doesn't work
3. Scripps visual changes (screen capture)
![UCI NO JS](images/UCIjs.png)
4. Scripps broken features (text description)
- The menu doesn't work 
5. UCLA visual changes (screen capture)
![UCLA No JS](images/UCLAjs.png)
6. UCLA broken features (text description)
- The twitter posts at the bottom no longer display
- Some of the sliding picture modules don't show up