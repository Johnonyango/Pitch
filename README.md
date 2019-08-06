# [Pitch]

## By John Onyango

## Description

The Pitch It web application is meant for users to post pitches on different categories. These categories are:

1. Product Pitch
2. Interview Pitch
3. Academic Pitch
4. Business
5. Promotion Pitch
6. Political
7. Technology
8. Health
A user can select any of the categories from the navbar to view the pitches on these categories

Other users can give feedback to the pitch posts by commenting, liking or disliking the pitch.

## # Behavior Driven Development
<table>
    <tr>
      <th>Behavior</th> 
      <th>Input</th> 
      <th>Output</th>   
    </tr>
    <tr>
        <td>Displaying various news sources</td>
        <td>Click on a news source</td>
        <td>The user lands to a page with a list of articles from the source</td>
    </tr>
    <tr>
        <td>Displaying the preview of an article</td>
        <td>Loading page</td>
        <td>Displays image, title, description and publication date</td>
    </tr>
    <tr>
        <td>Displaying the whole article</td>
        <td>Click on the article</td>
        <td>The user is redirected to the source to read the whole article</td>
    </tr>
</table>

### Prerequisites

This web application requires the following software tools to operate
-Python version 3.6
-Flask
-Pip
-virtualenv
-A text  Editor


## Getting Started

* Clone this repository to your local computer.
* Ensure you have python3.6 installed in your computer.
* From the terminal navigate to the cloned project folder.
* Create a virtual environment and access the folder via your virtual machine
 
 * run python3.6 manage.py server on the project directory

* Run ```chmod +x start.sh``` followed by ``` ./start.sh ``` while in the project folder to start the project.
* Once started, the project can be accessed on your localhost using the address: ``` localhost:5000 ```.
* This application can also be accessed by clicking the following link: 

## Technologies Used

* Python v3.6
* CSS(Boostrap/css.min)
* Flask
* Html

## Prepare environment variables
export DATABASE_URL='postgresql+psycopg2://username:password@localhost/pitch'

export SECRET_KEY='Your secret key'



## MIT License

Copyright (c) 2019 John Onyango

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE. 

Copyright (c) 2019 JOHN ONYANGO

