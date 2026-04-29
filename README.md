<img width="1280" height="602" alt="Screenshot 2026-04-29 at 10 10 12 PM" src="https://github.com/user-attachments/assets/cd12a52e-5523-40f1-bffe-251be2abf104" /><img width="1280" height="344" alt="Screenshot 2026-04-29 at 10 08 11 PM" src="https://github.com/user-attachments/assets/8d7084eb-668b-4e19-8eb1-6fb082f3a334" /><img width="1280" height="323" alt="Screenshot 2026-04-29 at 10 06 27 PM" src="https://github.com/user-attachments/assets/44ce2ea2-0867-46e3-9fd8-be1df42fa040" /><img width="1280" height="417" alt="Screenshot 2026-04-29 at 10 06 07 PM" src="https://github.com/user-attachments/assets/cf0f2833-e1b6-4b20-aeae-0336f86f434f" /><img width="1280" height="417" alt="Screenshot 2026-04-29 at 10 06 07 PM" src="https://github.com/user-attachments/assets/b5088c0a-fc1b-4afb-abd4-7a0e2c3cbb70" /><img width="1280" height="472" alt="Screenshot 2026-04-29 at 10 01 25 PM" src="https://github.com/user-attachments/assets/fbde2d6a-ba5a-4c30-994d-3deaa2c6fb8e" /><img width="1280" height="537" alt="Screenshot 2026-04-29 at 9 55 56 PM" src="https://github.com/user-attachments/assets/f9e7ccc8-7533-4ff2-9efe-3968b8aae229" /># Printing Management System

This is a Bash-based Operating System lab project for managing a small printing service from the terminal.

## How to run

```bash
chmod +x printing_management_system.sh
./printing_management_system.sh
```

After ensuring permission it can also run it with:

```bash
bash printing_management_system.sh
```

## Project files

- `printing_management_system.sh`: main application
- `users.txt`: user accounts
- `admin.txt`: admin accounts
- `in_progress_orders.txt`: pending print requests
- `history.txt`: approved/completed requests
- `prepaid.txt`: approved prepaid package balances
- `prepaid_requests.txt`: pending prepaid package requests

## Main features

- User registration and login
- Admin registration and login
- Submit print requests
- Track pending print status
- Buy prepaid printing packages
- Admin approval or rejection for prepaid requests
- Admin approval or rejection for print requests
- Print request history
- User prepaid package balance checking
- Admin view of all users' prepaid packages
- File-based data storage without database

## User features

- Create a new account
- Log in securely with username and password
- Submit print job details:
  - file name
  - number of copies
  - pages per copy
  - black and white or color
  - one-sided or double-sided
  - payment by bKash transaction or prepaid package
- Buy prepaid page packages
- See purchased package balances
- Check current request status
- View approved print history

## Admin features

- Create admin account
- Log in as admin
- View all pending print requests
- Approve or reject print requests
- View completed requests
- View all pending prepaid requests
- Approve or reject prepaid package requests
- View all approved prepaid balances

## Output from the terminal : 
1) Welcome page :
  <img width="1280" height="537" alt="Screenshot 2026-04-29 at 9 55 40 PM" src="https://github.com/user-attachments/assets/6ef696fd-5812-4891-ad1f-d1add8ada42b" />
<br>
<br>
<br>

2) Choosing number 1 :

<img width="1280" height="537" alt="Screenshot 2026-04-29 at 9 55 56 PM" src="https://github.com/user-attachments/assets/c4097de1-8b42-46f0-abb0-461eaba63633" />
<br>
<br>
<br>

3) User Registration :


<img width="1280" height="344" alt="Screenshot 2026-04-29 at 9 59 43 PM" src="https://github.com/user-attachments/assets/a00cfd0f-3969-414b-9ba7-2f3abe59aca2" />
<br>
<br>
<br>
4) Choosing 2 for User Login :


<img width="1280" height="451" alt="Screenshot 2026-04-29 at 9 59 53 PM" src="https://github.com/user-attachments/assets/52caf068-e5bf-491f-8d6f-404d7c437968" />
<br>
<br>
<br>
 5) User Log in 
 <img width="1280" height="274" alt="Screenshot 2026-04-29 at 10 00 16 PM" src="https://github.com/user-attachments/assets/221d28ba-b15f-44c6-95b7-e78fc626bc28" />
<br>
<br>
<br>

6) Submit a print request :
<img width="1280" height="408" alt="Screenshot 2026-04-29 at 10 00 28 PM" src="https://github.com/user-attachments/assets/3d368e82-c185-449c-ba5b-ecf3ae22118a" />

<img width="1280" height="472" alt="Screenshot 2026-04-29 at 10 01 25 PM" src="https://github.com/user-attachments/assets/6132f6ec-d8d3-4607-b224-f7b7d323f6d4" />
<br>
<br>
<br>

7) Buy a prepaid package :



<img width="1280" height="477" alt="Screenshot 2026-04-29 at 10 02 09 PM" src="https://github.com/user-attachments/assets/494236b0-eb33-4421-af78-a8eeb07127a8" />

<br>
<br>
<br>

8) Submitting a print request with prepaid without Admin approval :

<img width="1280" height="477" alt="Screenshot 2026-04-29 at 10 04 20 PM" src="https://github.com/user-attachments/assets/5a8dbb7a-b68f-4e29-ba3e-e395155a10e9" />


<img width="1280" height="544" alt="Screenshot 2026-04-29 at 10 05 05 PM" src="https://github.com/user-attachments/assets/4962d751-ab47-4bc5-84f6-cf7b76834584" />

<br>
<br>
<br>


9) See History :

<img width="1280" height="417" alt="Screenshot 2026-04-29 at 10 06 02 PM" src="https://github.com/user-attachments/assets/0627d1cb-0572-4183-bd34-a1f7e3197adb" />

<br>
<br>

**As Admin has not approved yet no history will be shown**


<img width="1280" height="417" alt="Screenshot 2026-04-29 at 10 06 07 PM" src="https://github.com/user-attachments/assets/57dbb530-7e97-4357-a46e-4c91cbb7025a" />


<br>
<br>
<br>

10) See purchased packages:

<img width="1280" height="417" alt="Screenshot 2026-04-29 at 10 06 20 PM" src="https://github.com/user-attachments/assets/6897445f-e64e-47da-b86d-a86998543f89" />
<br>
<br>

**As Admin has not approved yet no history will be shown**

<img width="1280" height="323" alt="Screenshot 2026-04-29 at 10 06 27 PM" src="https://github.com/user-attachments/assets/68ba97fa-0b64-4c17-ad2b-9f767a0081f8" />

11) Log out:


<img width="1280" height="400" alt="Screenshot 2026-04-29 at 10 06 35 PM" src="https://github.com/user-attachments/assets/8887de03-3eae-45e1-8df1-ee2037002fb6" />


12) Admin Register :

<img width="1280" height="435" alt="Screenshot 2026-04-29 at 10 06 45 PM" src="https://github.com/user-attachments/assets/31c38c05-a26b-464e-b7de-dc6a4d40ca96" />


<img width="1280" height="344" alt="Screenshot 2026-04-29 at 10 08 11 PM" src="https://github.com/user-attachments/assets/7b824eb0-8540-4f60-b08c-ca370c372e7a" />


13) Admin Login :

<img width="1280" height="445" alt="Screenshot 2026-04-29 at 10 08 21 PM" src="https://github.com/user-attachments/assets/afb09488-4fbc-439e-94fb-c645055e7504" />


<img width="1280" height="275" alt="Screenshot 2026-04-29 at 10 08 46 PM" src="https://github.com/user-attachments/assets/0b02a7ef-a60c-4458-a636-e962f4a519ac" />


<br>
<br>
<br>


14) View Pending Requests :



<img width="1280" height="451" alt="Screenshot 2026-04-29 at 10 09 01 PM" src="https://github.com/user-attachments/assets/62354a89-04c2-489b-94ab-a2cd5163f416" />

<img width="1280" height="774" alt="Screenshot 2026-04-29 at 10 09 20 PM" src="https://github.com/user-attachments/assets/05654ea4-f205-4d10-90eb-3482069e540e" />


15) Approve/ Reject print request :

<img width="1280" height="357" alt="Screenshot 2026-04-29 at 10 09 31 PM" src="https://github.com/user-attachments/assets/139695d7-779c-442c-afe5-91a62fb07417" />


<img width="1280" height="602" alt="Screenshot 2026-04-29 at 10 10 12 PM" src="https://github.com/user-attachments/assets/2db942fa-4674-4b87-9810-a6b4f6e2975e" />


<br>
<br>
<br>








