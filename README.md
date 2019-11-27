# Visitor-Management-System

Designed a responsive website for Visitors management in a large organisation. Here visitors on arrival will Check in. So they will register on Visitors registrationa portal in which they will enter required details. Visitor will be mailed a unique UserID which will be required when he wants to check out.


# Requirments-
We need an application, which can capture the Name, email address, phone no of the visitor and
same information also needs to be captured for the host on the front end.
At the back end, once the user enters the information in the form, the backend should store all of
the information with time stamp of the entry.
This should trigger an email to the host informing him of the details of the visitor.
There should also be a provision of the checkout time which the guest can provide once he
leaves. This should trigger an email to the guest with the complete form which should include:
1. Name
2. Phone
3. Check-in time,
4. Check-out time,
5. Host name
6. Address visited.

# Example of the intended workflow

Visitor Details:<br>
Name - Anant Sharma<br>
Email - a.sharma@xyz.com<br>
Phone - 9999999999<br>
Checkin Time - 9:00 AM IST<br>
Checkout Time - 4:00 PM IST<br>


Host Details:<br>
Name - Vishesh Singh<br>
Email - vs@xyz.com<br>
Phone - 000000000<br>


Once Anant checks in and enters his details in the application, Vishesh should get an email stating the visitor details, and also Anant gets an Email with his UserId which will be required during Check Out.

After the meeting or visit is over, and Anant checks out at 4:00 PM, Anant should get an emails
stating his visit details :

1. Name<br>
2. Phone<br>
3. Check-in time<br>
4. Check-out time<br>
5. Host name<br>
6. Address visited<br>


# Website Architecture-

![Architecture](https://i.imgur.com/dsNBuOJ.jpg)

Steps given is actually showing working of website.

1) Visitor needs to fill his details in the website.
2) He will receive a mail with his unique UserId. In the meantime, Visitor's host will also receive a mail that a guest has arrived for him.
3) During the checkout, Visitor needs to enter his UserId and Email Id which will be verified from the database. If the User is laready inside, then he can successfully CheckOut.

# Main Page

![Main Page](https://i.imgur.com/Ae7FNM7.png)

# Registration Form

![Registration](https://i.imgur.com/hL1t22r.png)

# Javascript Message

![Simple Message with UserId](https://i.imgur.com/yue9Mor.png)

# Visitors mail on Entry

![Visitors Mail](https://i.imgur.com/FfVl8ae.png)

Contains all important details specially UserID which will be used in Exiting.

# Host mail on Entry

![Host Mail](https://i.imgur.com/5DtupBw.png)

Host also receives mail on his guest entry which contains all information about guest along with the CheckIn time.

# Database gets updated

![Database](https://i.imgur.com/0dM4z28.png)

I created a php page to fetch data from the MySQl database which will show visitors details along with who is inside. <b> This page can only be viewed by manager or Authorised persons.</b> I have kept its Url different <i>http://visitor.almafiesta.com/display.php</i> , We can also keep a Authorisation system also to access this page.
  
Please note that It is showing departure time of Sakshi Gupta, still as inside because she hasn't checked out.

# Check Out

![Exit](https://i.imgur.com/6wGbdiJ.png)

Guest during the checkOut need to enter his EmailId and UserId to get verified.

# Verification

If the Visitor enters correct details, he will she this dialog box on his screen.

![Correct Details](https://i.imgur.com/ls11835.png)

If the details do not match that of database, he will get an error dialog box.

![Wrong Details](https://i.imgur.com/U5gTUhI.png)

If the visitor tries to checkOut again, he will see this message in his dialog box.

![Already Checked out](https://i.imgur.com/ssVgJ9Y.png)

# Database

![database gets updated](https://i.imgur.com/vU1HbZ7.png)

See the details of Sakshi Gupta, it is updated with her time of Checkout.

# Visitor gets Thanks mail

![visit complete](https://i.imgur.com/cKL9sGZ.png)

Visitor receives one final mail with all his details as well an updated CheckIn and CheckOut time.

<b>------------------------------------------------------------------------------------------------------------------------------------

# Features

1) This is a <b>responsive website</b> and will work on all devices. Use inspect to experience it.
![Inspect](https://i.imgur.com/CtRWDds.png)

2) This website has used HTML, CSS, Javascript, BootStrap, MySQl, PHP. This is created from scratch and no template is copied.

3) This Visitor Management portal is live <i> http://visitor.almafiesta.com </i>. Please have a visit.

4) Managers and Adminstrators can check the MySQL database. I have fetched all its details from MySQL to a dynamic webpage. Have a look <i> http://visitor.almafiesta.com/display.php </i>.


# Further possible Extensions

1) As we have implemented our website with a Login access system, We can easily extend our Visitor Mangaement website to other tasks also.

2) We can also keep a feedback form in the exit form, which will help us to get more idea about Host behaviour and capabilities.

3) In case of busy schedule of host, we can keep a track of guest for host and provide a better meeting time. In this case, we will ask our visitors to first fill the form and get an idea of waiting time. This will help in better management of visitors and will not waste Visitors time.


 
