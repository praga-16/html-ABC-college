# html-city-tourism
## Ex-1
### Creating a html file to display the contents as seen in the following image.
#### Program:
name : pragatheesvarana AB
<br> roll no : 212221240039

##### table.html
```
<!DOCTYPE html>
<html>
<head>
    <title>My Day</title>
    <style>
        table {
            width: 100%;
            border-collapse: collapse;
        }
        th, td {
            border: 1px solid black;
            padding: 10px;
            text-align: left;
        }
        th {
            background-color: yellow;
        }
        .main-content {
            width: 70%;
            vertical-align: top;
        }
        .images-content {
            width: 30%;
            vertical-align: top;
        }
        .centered {
            text-align: center;
        }
        .image-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 10px;
        }
        .image-grid img {
            width: 100%;
            height: auto;
        }
    </style>
</head>
<body>
    <table class="center">
        <tr>
            <th colspan="2" class="centered">My Day</th>
        </tr>
        <tr>
            <td class="main-content">
                <ol>
                    <li>wake up early
                        <ul>
                            <li>5AM</li>
                            <li>walk</li>
                            <li>jog</li>
                        </ul>
                    </li>
                    <hr>
                    <li>breakfast
                        <ul>
                            <li>8AM</li>
                            <li>eggs</li>
                            <li>coffee</li>
                        </ul>
                    </li>
                    <hr>
                    <li>go to Saveetha
                        <ul>
                            <li>8AM</li>
                            <li>attend classes</li>
                            <li>to be continued</li>
                        </ul>
                    </li>
                    <hr>
                </ol>
            </td>
            <td class="images-content">
                <table>
                    <tr>
                        <th class="centered">Things to watch</th>
                    </tr>
                    <tr>
                        <td>
                            <div class="image-grid">
                                <img src="c:\Users\PRAGA\OneDrive\Desktop\web table\im1.jpeg" alt="Walking Image">
                                <img src="c:\Users\PRAGA\OneDrive\Desktop\web table\im2.png" alt="Eggs Image">
                                <img src="c:\Users\PRAGA\OneDrive\Desktop\web table\im3.jpeg" alt="Coffee Image">
                                <img src="c:\Users\PRAGA\OneDrive\Desktop\web table\im4.jpeg" alt="Classroom Image">
                            </div>
                        </td>
                    </tr>
                </table>
            </td>
        </tr>
    </table>
</body>
</html>

```
#### Output:
![web table](https://github.com/praga-16/html-ABC-college/assets/95266924/9a4d4edf-7101-4f03-b449-3b73d2a9e3a7)


#### Result:
 Thus,Creating a html file to display the content in the above picture was executed successfully.

##### index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ABC College</title>
</head>
<body>
    <header>
        <img src="images/logo.png" alt="College Logo">
        <h1>Name</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="academics.html">Academics</a></li>
                <li><a href="admission.html">Admission</a></li>
                <li><a href="gallery.html">Gallery</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section>
            <h2>Welcome to ABC College</h2>
            <p>Our college is committed to providing excellent education and fostering the personal and professional growth of our students. We offer a variety of programs in Arts, Science, and Commerce, led by a dedicated faculty in a supportive learning environment.</p>
        </section>
    </main>
</body>
</html>
```
#### Output:
![Screenshot 2024-07-03 113607](https://github.com/praga-16/html-ABC-college/assets/95266924/57a423af-285c-433e-92be-2d15da0a1203)


#### Result:
 Thus,Creating a html file to display the content in the above picture was executed successfully.

##### academics.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Academics - College Name</title>
</head>
<body>
    <header>
        <img src="images/logo.png" alt="College Logo">
        <h1>ABC College</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="academics.html">Academics</a></li>
                <li><a href="admission.html">Admission</a></li>
                <li><a href="gallery.html">Gallery</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section>
            <h2>Academic Departments</h2>
            <ul>
                <li>Science
                    <ul>
                        <li><a href="courses/computer-science.html">Computer Science</a></li>
                        <li><a href="courses/mathematics.html">Mathematics</a></li>
                    </ul>
                </li>
                <li>Arts
                    <ul>
                        <li><a href="courses/english.html">English</a></li>
                        <li><a href="courses/sociology.html">Sociology</a></li>
                    </ul>
                </li>
                <li>Commerce
                    <ul>
                        <li><a href="courses/economics.html">Economics</a></li>
                        <li><a href="courses/business-management.html">Business Management</a></li>
                    </ul>
                </li>
            </ul>
        </section>
    </main>
</body>
</html>

```
#### Output:
![Screenshot 2024-07-03 113509](https://github.com/praga-16/html-ABC-college/assets/95266924/21d7d5f3-c40c-4f93-837b-b7a4ad486c66)


#### Result:
 Thus,Creating a html file to display the content in the above picture was executed successfully.

##### admission.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Admission - College Name</title>
</head>
<body>
    <header>
        <img src="images/logo.png" alt="College Logo">
        <h1>ABC College</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="academics.html">Academics</a></li>
                <li><a href="admission.html">Admission</a></li>
                <li><a href="gallery.html">Gallery</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section>
            <h2>Admission Form</h2>
            <form>
                <label for="name">Full Name:</label>
                <input type="text" id="name" name="name" required><br>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required><br>

                <label for="phone">Phone Number:</label>
                <input type="tel" id="phone" name="phone" required><br>


                
                <label for="dob">Date of Birth:</label>
                <input type="date" id="dob" name="dob" required><br>

                <label for="course">Course Interested:</label>
                <select id="course" name="course">
                    <option value="computer-science">Computer Science</option>
                    <option value="mathematics">Mathematics</option>
                    <option value="english">English</option>
                    <option value="sociology">Sociology</option>
                    <option value="economics">Economics</option>
                    <option value="business-management">Business Management</option>
                </select><br>

                <label for="address">Address:</label>
                <textarea id="address" name="address" required></textarea><br>

                <button type="submit">Submit</button>
            </form>
        </section>
    </main>
</body>
</html>

```
#### Output:
![Screenshot 2024-07-03 113553](https://github.com/praga-16/html-ABC-college/assets/95266924/5123778c-ce8b-4b70-9308-f29491c823c6)


#### Result:
 Thus,Creating a html file to display the content in the above picture was executed successfully.
 
##### gallery.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gallery - ABC College</title>
</head>
<body>
    <header>
        <img src="images/logo.png" alt="College Logo">
        <h1>College Name</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="academics.html">Academics</a></li>
                <li><a href="admission.html">Admission</a></li>
                <li><a href="gallery.html">Gallery</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section>
            <h2>Gallery</h2>
            <div>
                <img src="images/gallery1.jpeg" alt="Gallery Image 1">
                <img src="images/gallery2.jpeg" alt="Gallery Image 2">
                <img src="images/gallery3.jpeg" alt="Gallery Image 3">
                <img src="images/gallery4.jpeg" alt="Gallery Image 4">
            </div>
        </section>
    </main>
</body>
</html>

```
#### Output:
![Screenshot 2024-07-03 113531](https://github.com/praga-16/html-ABC-college/assets/95266924/c3b64c22-7f5e-4123-91df-d1967330eb9b)


#### Result:
 Thus,Creating a html file to display the content in the above picture was executed successfully.
##### cs.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Computer Science - ABC College</title>
</head>
<body>
    <header>
        <img src="../images/logo.png" alt="College Logo">
        <h1>ABC College</h1>
        <nav>
            <ul>
                <li><a href="../index.html">Home</a></li>
                <li><a href="../academics.html">Academics</a></li>
                <li><a href="../admission.html">Admission</a></li>
                <li><a href="../gallery.html">Gallery</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section>
            <h2>Computer Science</h2>
            <p>The Computer Science program offers a comprehensive curriculum that covers the fundamentals of computing, programming, algorithms, and data structures. Students will learn to develop software, understand computer systems, and solve complex problems.</p>
            <h3>Faculty</h3>
            <ul>
                <li>Prof. Billy Bowden</li>
                <li>Dr. Rod Tucker</li>
                <li>Prof. Emilia Williams</li>
            </ul>
            <h3>Timetable</h3>
            <table>
                <tr>
                    <th>Day</th>
                    <th>Time</th>
                    <th>Subject</th>
                </tr>
                <tr>
                    <td>Tuesday</td>
                    <td>08:00 - 10:00</td>
                    <td>Operating Systems</td>
                </tr>
                <tr>
                    <td>Wednesday</td>
                    <td>11:00 - 12:30</td>
                    <td>DBMS</td>
                </tr>
                <tr>
                    <td>Saturday</td>
                    <td>15:00 - 17:00</td>
                    <td>Python Programming</td>
                </tr>
            </table>
        </section>
    </main>
</body>
</html>
```
#### Output:
![Screenshot 2024-07-03 113735](https://github.com/praga-16/html-ABC-college/assets/95266924/6116e921-4e24-4e10-8c07-729a1ab93b0b)
#### Result:

 Thus,Creating a html file to display the content in the above picture was executed successfully.
##### mathematics.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mathematics - College Name</title>
    <link rel="stylesheet" href="../styles.css">
</head>
<body>
    <header>
        <img src="../images/logo.png" alt="College Logo">
        <h1>College Name</h1>
        <nav>
            <ul>
                <li><a href="../index.html">Home</a></li>
                <li><a href="../academics.html">Academics</a></li>
                <li><a href="../admission.html">Admission</a></li>
                <li><a href="../gallery.html">Gallery</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section>
            <h2>Mathematics</h2>
            <p>The Mathematics program provides a deep understanding of mathematical principles and techniques. Students will explore topics such as calculus, algebra, geometry, and statistics, developing analytical and problem-solving skills.</p>
            <h3>Faculty</h3>
            <ul>
                <li>Prof. Alan Turing</li>
                <li>Dr. Ada Lovelace</li>
                <li>Prof. Carl Gauss</li>
            </ul>
            <h3>Timetable</h3>
            <table>
                <tr>
                    <th>Day</th>
                    <th>Time</th>
                    <th>Subject</th>
                </tr>
                <tr>
                    <td>Monday</td>
                    <td>10:00 - 11:30</td>
                    <td>Calculus</td>
                </tr>
                <tr>
                    <td>Wednesday</td>
                    <td>12:00 - 13:30</td>
                    <td>Algebra</td>
                </tr>
                <tr>
                    <td>Friday</td>
                    <td>09:00 - 10:30</td>
                    <td>Statistics</td>
                </tr>
            </table>
        </section>
    </main>
</body>
</html>

```
#### Output:

![Screenshot 2024-07-03 113350](https://github.com/praga-16/html-ABC-college/assets/95266924/69fdc26e-e4c4-402c-a46c-c84735988bf4)

#### Result:
 Thus,Creating a html file to display the content in the above picture was executed successfully.
#### economis.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Economics - ABC College</title>
</head>
<body>
    <header>
        <img src="../images/logo.png" alt="College Logo">
        <h1>ABC College</h1>
        <nav>
            <ul>
                <li><a href="../index.html">Home</a></li>
                <li><a href="../academics.html">Academics</a></li>
                <li><a href="../admission.html">Admission</a></li>
                <li><a href="../gallery.html">Gallery</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section>
            <h2>Economics</h2>
            <p>The Economics program provides an understanding of economic principles, theories, and models. Students will learn about microeconomics, macroeconomics, and the impact of economic policies.</p>
            <h3>Faculty</h3>
            <ul>
                <li>Prof. Adam Smith</li>
                <li>Dr. John Maynard Keynes</li>
                <li>Prof. Milton Friedman</li>
            </ul>
            <h3>Timetable</h3>
            <table>
                <tr>
                    <th>Day</th>
                    <th>Time</th>
                    <th>Subject</th>
                </tr>
                <tr>
                    <td>Tuesday</td>
                    <td>09:00 - 10:30</td>
                    <td>Microeconomics</td>
                </tr>
                <tr>
                    <td>Thursday</td>
                    <td>11:00 - 12:30</td>
                    <td>Macroeconomics</td>
                </tr>
                <tr>
                    <td>Friday</td>
                    <td>13:00 - 14:30</td>
                    <td>Economic Policy</td>
                </tr>
            </table>
        </section>
    </main>
</body>
</html>

```
#### Output:

![Screenshot 2024-07-03 113828](https://github.com/praga-16/html-ABC-college/assets/95266924/0c28c303-ace1-4e90-95e0-e1cbf2f33ee3)

#### Result:
 Thus,Creating a html file to display the content in the above picture was executed successfully.
