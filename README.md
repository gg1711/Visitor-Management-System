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

Visitor Details:
Name - Anant Sharma
Email - a.sharma@xyz.com
Phone - 9999999999
Checkin Time - 9:00 AM IST
Checkout Time - 4:00 PM IST


Host Details:
Name - Vishesh Singh
Email - vs@xyz.com
Phone - 000000000


Once Anant checks in and enters his details in the application, Vishesh should get an email stating the visitor details. and also Anant gets an Email with his UserId which will be required during Check Out.

After the meeting or visit is over, and Anant checks out at 4:00 PM, Anant should get an emails
stating his visit details :

1. Name
2. Phone
3. Check-in time,
4. Check-out time,
5. Host name
6. Address visited

