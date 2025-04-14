# Web-Dev-week2-assignment
Elemetnts &amp; Forms

<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Elements and Forms
</title>
    </head>
    <body>
        <!-- Header section -->
        <header>
            <h1>Welcome to the Information Box</h1>
        </header>
         <!-- ordered lists with Roman numerals -->
         <section>
            <h2>LISTS</h2>
            <ol type="I">
                <li>1st Item</li>
                <li>2nd Item</li>
                <li>3rd Item</li>
                <li>4th Item</li>
                <li>5th Item</li>
            </ol>
         </section>
         <!-- Image from Pexels.com -->
         <section>
            <h2>Featured Image</h2>
            <img src="Photo by Ron Lach : https://www.pexels.com/photo/group-of-children-collecting-plastics-9037596/" alt="Save the world" width="400">
         </section>
          <!-- Contact Table -->
          <section>
            <h2>Contact List</h2>
            <tableborder="1" cellpadding="8" cellspacing="0">
                <thead>
                    <tr>
                        <th>Name</th>
                        <th>Address</th>
                        <th>Mobile</th>
                        <th>Email</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Paul Max</td>
                        <td>Kiambu,Nairobi</td>
                        <td>+254 723 763 428</td>
                        <td>@infoplp.Pmax.com</td>
                    </tr>
                    <tr>
                        <td>Kim Kiama</td>
                        <td>Ngong rd.</td>
                        <td>+243 678 005 768</td>
                        <td>Kimkiama@gmail.com</td>
                    </tr>
                    <tr>
                        <td>Ben Goou</td>
                        <td>yukon,Inides</td>
                        <td>+233 786 654 923</td>
                        <td>BenGo@yahoo.com</td>
                    </tr>
                    <tr>
                        <td>Jane Wanjiru</td>
                        <td>syokimau</td>
                        <td>+254 675 884 345</td>
                        <td>JaneWanjiru@gmail.com</td>
                    </tr>
                    <tr>
                        <td>Jeremy Kiboo</td>
                        <td>Joburg,South A.</td>
                        <td>+254 563 887 234</td>
                        <td>Info@JeremyKiboo.com</td>
                    </tr>
                </tbody>
            </table>
          </section>
          <!-- Registration Form -->
           <section>
            <h2>Registration Form</h2>
            <form action="#" method="post">
                <!--Name Field-->
                <label for="name">Full_Name:</label><br>
                <input type="text" id="name" name="name" placeholder="Enter your full name" required><br><br>
                <!--Email field-->
                <label for="email">Email:</label><br>
                <input type="email" id="email" name="email" placeholder="Enter your email" required><br><br>
                <!--Password field-->
                <label for="Password">Password:</label><br>
                <input type="password" id="Password" name="Password" placeholder="Enter your passwprd" required minlength="6"><br><br>
                <!--Date field-->
                <label for="DOB">Date of Birth:</label><br>
                <input type="date" id="DOB" name="DOB" required><br><br>
                <!--Dropdown-->
                <label for="country">Country:</label><br>
                <select id="country" name="country"required>
                    <option value="">--select country--</option>
                    <option value="kenya">Kenya</option>
                    <option value="usa">USA</option>
                    <option value="uk">UK</option>
                    <option value="canada">canada</option>
                    <option value="south_africa">South_africa</option>
                </select><br><br>

                <!--Radio buttons-->
                <label>Gender:</label><br>
                <input type="radio" id="male" name="gender" value="male" required>
                <label for="male">Male</label><br>
                <input type="radio" id="female" name="gender" value="female">
                <label for="female">Female</label><br>
                <input type="radio" id="other" name="gender" value="other">
                <label for="other">Other</label><br>

                <!--Checkboxes-->
                <label>Interests:</label><br>
                <input type="checkbox" id="coding" name="interests" value="coding">
                <label for="coding">Coding</label><br>
                <input type="checkbox" id="music" name="interests" value="music">
                <label for="music">Music</label><br>
                <input type="checkbox" id="travel" name="interests" value="travel">
            <label for="travel">Travel</label><br>
            <!--submit form-->
            <input type="submit" value="Register">
            </form>
        </section>
        <!--Footer-->
        <footer>
            <p>&copy; 2025 Hiccup-Html.</p>
        </footer>
    </body>
</html>
