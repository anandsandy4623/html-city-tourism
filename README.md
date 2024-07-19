# html-city-tourism
One Home page that leads to other pages. The Home page should contain the name of the City as heading along with a logo. There should be a tab with the following links:  Home;  Heritage;  Hotel Booking;  Gallery. There should be an appropriate description of the college on the home page.

## PROGRAM
### INDEX.HTML
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Saveetha Engineering College</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <img  src="logo1.png" alt="College Logo" height="50">
        
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
            <h2>Welcome to College Name</h2>
            <p>Welcome to our college, where we provide top-notch education and a vibrant campus life. Explore our academic programs, meet our distinguished faculty, and become part of our thriving community.</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 College Name. All rights reserved.</p>
    </footer>
</body>
</html>
```
### ADMISSION.HTML
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Admission - Saveetha Engineering College</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <img src="logo1.png" alt="College Logo" height="50">
        
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
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required><br>

                <label for="dob">Date of Birth:</label>
                <input type="date" id="dob" name="dob" required><br>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required><br>

                <label for="phone">Phone:</label>
                <input type="tel" id="phone" name="phone" required><br>

                <label for="address">Address:</label>
                <textarea id="address" name="address" required></textarea><br>

                <label for="course">Course Interested:</label>
                <select id="course" name="course" required>
                    <option value="computer-science">Computer Science</option>
                    <option value="mathematics">Mathematics</option>
                    <option value="english">English</option>
                    <option value="sociology">Sociology</option>
                    <option value="economics">Economics</option>
                    <option value="business-management">Business Management</option>
                </select><br>

                <input type="submit" value="Submit">
            </form>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 College Name. All rights reserved.</p>
    </footer>
</body>
</html>
```
### GALLERY.HTML
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gallery - Saveetha Engineering College</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <img src="logo1.png" alt="College Logo" height="50">
        
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
                <img src="image1.png" alt="Gallery Image 1" height="200" width="300">
                <img src="image2.png" alt="Gallery Image 2" height="200" width="300"><br>
                <img src="image3.png" alt="Gallery Image 3" height="200" width="300">
                <img src="image4.png" alt="Gallery Image 4" height="200" width="300">
            </div>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 College Name. All rights reserved.</p>
    </footer>
</body>
</html>
```
## OUTPUT
![image](https://github.com/user-attachments/assets/c8b061d3-3231-4669-967f-d797c6c5acb0)
![image](https://github.com/user-attachments/assets/695f8114-6bd1-4434-a3ad-1f0cf101985c)
![image](https://github.com/user-attachments/assets/18aec369-3901-4929-a2d8-783cc6c57504)
![image](https://github.com/user-attachments/assets/d3b6dc84-e348-4cb7-a1a7-a4001e0650ca)



