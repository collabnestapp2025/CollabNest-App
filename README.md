# CollabNest

Finding the right team members for projects, hackathons, or college events can be a major challenge. CollabNest solves this problem by creating a dedicated collaborative platform for campus. It's a mobile app that helps students discover upcoming events, search for peers based check their skills,projects and connect directly through in-app chat. Whether you're looking to build a team for a competition or find a partner for a project, CollabNest is the central hub to sync up and skill up.

### 📱 User Application  
The main application side for students to connect, find teams, and manage their profile.  
Students can also **view other users’ profiles, check their projects and skills, send messages, send/accept team invites, and view upcoming events**.


## 🔐 1. Register Screen  
A clean and user-friendly registration page where students create an account by entering their username, email, and password.  
Users must verify their email using a Firebase verification link before they can log in.

**Features:**
- Username, Email, Password & Confirm Password fields  
- Email verification button  
- Eye icon to toggle password visibility  
- Firebase-backed registration logic  
- Smooth UI with modern design elements  

**Screenshot:**  
<img src="https://github.com/Patil-Kalpak/CollabNest-App/blob/main/screenshots/createAccont.jpeg" width="200">


---

## 🔑 2. Login Screen  
The main login page for returning users to access their CollabNest account.

**Features:**
- Email & password login  
- “Forgot password?” option  
- Password visibility toggle  
- Link to sign up  
- Dedicated button to switch to Admin Login  

**Screenshot:**  
<img src="https://github.com/Patil-Kalpak/CollabNest-App/blob/main/screenshots/userLogin.jpeg" width="200" style="margin-right:20px;">
  <img src="https://github.com/collabnestapp2025/CollabNest-App/blob/main/screenshots/firstuser.jpeg" width="200">
</p>

## 📝 3. Edit Profile Screen  
The Edit Profile screen allows users to build a complete professional profile inside the app.  
Students can showcase their skills, projects, and achievements, making it easier for others to find the right teammates.

**Features:**
- Upload or change **profile picture (DP)**  
- Add or update **skills**  
- Add **project details**  
- Add **GitHub profile link**  
- Upload **Resume (PDF)**  
- Add **LinkedIn link**  
- Add **LeetCode profile link**  


- All data is synced with Firebase for real-time updates  

**Screenshot:**  
<img src="https://github.com/Patil-Kalpak/CollabNest-App/blob/main/screenshots/editProfile.jpeg" width="200">
<img src="https://github.com/Patil-Kalpak/CollabNest-App/blob/main/screenshots/ediprofile2.jpeg" width="200">




## 🔍 4. Search Users & View Profile Details  
This feature allows students to explore the entire CollabNest community and find the right people for project collaborations, hackathons, or study groups.

**Features:**
- Search users by **name**
- View full **profile details** of any student  
- Profile includes:
  - Profile picture (DP)  
  - Skills  
  - Projects  
  - GitHub link  
  - LinkedIn link  
  - LeetCode link  
  - Resume (PDF)  
  

**Screenshot:**  
<img src="https://github.com/Patil-Kalpak/CollabNest-App/blob/main/screenshots/serachUsers.jpeg" width="200">
<img src="https://github.com/Patil-Kalpak/CollabNest-App/blob/main/screenshots/userProfile.jpeg" width="200">
<img src="https://github.com/Patil-Kalpak/CollabNest-App/blob/main/screenshots/userprofie2.jpeg" width="200">



## 💬 5. Chat System  
The chat feature allows students to communicate instantly with other users inside the app.  
It is fully real-time and powered by Firebase Realtime Database.

**Features:**
- One-on-one real-time messaging  
- Messages appear instantly without refresh  
- Users receive **notifications** when they get a new message  
- Clean and simple chat UI  
- Shows sender/receiver message bubbles  
- Automatically scrolls to the latest message  
- Sends messages even if the user is on another screen  

**Screenshot:**  
<img src="https://github.com/Patil-Kalpak/CollabNest-App/blob/main/screenshots/chat.jpeg" width="200">
<img src="https://github.com/Patil-Kalpak/CollabNest-App/blob/main/screenshots/chat2.jpeg" width="200">
<img src="https://github.com/Patil-Kalpak/CollabNest-App/blob/main/screenshots/chat3.jpeg" width="200">
<img src="https://github.com/Patil-Kalpak/CollabNest-App/blob/main/screenshots/chatBlueicon.jpeg" width="200">

## 📅 6. Event Calendar & Event Details  
CollabNest includes a fully interactive event system where students can explore all upcoming campus events in one place.

### **🔸 Event Calendar**
The calendar screen displays the entire month with **yellow dots** marking dates that have scheduled events.

**Features:**
- Interactive monthly calendar  
- Dots highlight dates with events  
- Tap any highlighted date to view events on that day  
- Smooth navigation between months  
- Clean UI for quick scanning of event timelines  

**Screenshot:**  
<img src="https://github.com/Patil-Kalpak/CollabNest-App/blob/main/screenshots/EventCalendar.jpeg" width="200">

---

### **🔸 Upcoming Events List**
Below the calendar, users can scroll through all upcoming events.

**Features:**
- Scrollable list of events  
- Event name, date, time & venue  
- Cards with modern design and shadows  
- Events automatically sorted by nearest date  

**Screenshot:**  
<img src="https://github.com/Patil-Kalpak/CollabNest-App/blob/main/screenshots/caledarupcoming.jpeg" width="200">

---

### **🔸 Event Details Page**
When a user clicks on an event, they see a detailed page with everything they need to know.

**Features:**
- Event poster/banner at the top  
- Date & time  
- Venue  
- Complete event description  
- Host & participant details  
- Prize pool, coordinator info  
- Option to **register** for the event  

**Screenshots:**  
<img src="https://github.com/Patil-Kalpak/CollabNest-App/blob/main/screenshots/viewEvents.jpeg" width="200" style="margin-right:20px;">
<img src="https://github.com/Patil-Kalpak/CollabNest-App/blob/main/screenshots/viewevents2.jpeg" width="200">




## 🧑‍🤝‍🧑 7. Register for an Event (Create a Team)
Students can register for events by creating their own team.  
This allows hackathons, competitions, and group events to easily manage participants.

### **🔸 Team Registration Flow**
When a student taps **“Register for this Event”**, a pop-up appears asking them to enter their **Team Name**.

**Features:**
- Create a custom **Team Name**
- Smooth dialog pop-up for entering details
- Once registered, the UI updates to **“Already Registered”**
- Prevents duplicate registrations
- Team information stored in Firebase under the specific event
- Ensures accurate participant count and event capacity management

**Screenshot (Team Name Dialog):**  
<img src="https://github.com/Patil-Kalpak/CollabNest-App/blob/main/screenshots/register1.jpeg" width="200">

---

### **🔸 After Registration**
Once the user registers successfully:
- The button changes to **“Already Registered”**
- User cannot register again
- Event organizers can view the registered team

**Screenshot (After Registration UI):**  
<img src="https://github.com/Patil-Kalpak/CollabNest-App/blob/main/screenshots/register2.jpeg" width="200">






## 👥 8. Teams & Invitations Management  
CollabNest allows students to manage their event teams directly from the Home screen.  
Users can view their teams, respond to invitations, and explore team details.  
Only the **team leader** has permission to add new members.

---

### 🔸 **Your Teams (Home Screen)**  
Users can see all the teams they are part of, along with the event names.

**Features:**
- View all joined teams  
- Each card displays team name + event name  
- Tap any team to open detailed team view  

**Screenshot:**  
<img src="https://github.com/Patil-Kalpak/CollabNest-App/blob/main/screenshots/UserHome.jpeg" width="200">

---

### 🔸 **Team Details (Leader & Members)**  
All team members can open the Team Details page to see information about the team.  
However, only the **team leader** gets the option to add new members.

**Common Features (Visible to All Members):**
- View team name  
- View event name  
- Max participants allowed  
- List of all team members  
- Leader badge shown next to the team leader  
- Current team progress (e.g., 1/3, 2/3)

**Leader-Only Features:**
- “**Add Member**” button  
- Ability to send invitations to new members  

**Screenshot:**  
<img src="https://github.com/Patil-Kalpak/CollabNest-App/blob/main/screenshots/ViewTeam.jpeg" width="200">
<img src="https://github.com/Patil-Kalpak/CollabNest-App/blob/main/screenshots/addUserinteam.jpeg" width="200">




## 🏠 9. User Home Screen  
The Home screen gives users a complete overview of all important updates in one place — teams, invitations, and upcoming events.

---

 

### 🔸 **Invitations (Accept or Decline)**  
Users receive invitations from team leaders inviting them to join a team.

**Features:**
- Shows event name and who invited the user  
- **Accept** to join the team  
- **Decline** to reject the invitation  
- Team updates immediately after acceptance  
- Invitation card disappears after action  

**Screenshot:**  
<img src="https://github.com/Patil-Kalpak/CollabNest-App/blob/main/screenshots/UserHome.jpeg" width="200">

---

### 🔸 **After Joining a Team**  
Once the user accepts an invitation:
- The team is added to **Your Teams** list  
- A small confirmation card may appear (ex: *“Joined TLE Eliminators for CodeBlue!”*)  
- User can now open the team and view all members  

**Screenshot:**  
<img src="https://github.com/Patil-Kalpak/CollabNest-App/blob/main/screenshots/showinvite.jpeg" width="200" style="margin-right:20px;">
<img src="https://github.com/Patil-Kalpak/CollabNest-App/blob/main/screenshots/viewteams.jpeg" width="200">

---

### 🔸 **Upcoming Events (Home Screen)**  
At the bottom of the Home screen, users can browse all upcoming events.

**Features:**
- Event poster with modern UI  
- Event name, date, time, venue  
- **View Details** button  
- Scrollable event list  

**Screenshots:**  
<img src="https://github.com/Patil-Kalpak/CollabNest-App/blob/main/screenshots/Homepage_upcomingevents.jpeg" width="200" style="margin-right:20px;">
<img src="https://github.com/Patil-Kalpak/CollabNest-App/blob/main/screenshots/homepageupcomingevents2.jpeg" width="200">

---

### Summary  
The Home screen ensures users can:
- Quickly see their teams  
- Respond to invitations  
- Join new teams  
- Access upcoming event information  
All in one clean, central dashboard.










## 🛠️ 10. Admin Panel  
The Admin Panel is designed for college event coordinators or club heads who are responsible for creating and managing events on the CollabNest platform.

Admins are assigned a **unique login ID and password** by the system administrators.

---

### 🔐 **Admin Login**  
Admins can securely log in using their admin credentials.  
They also have the option to switch back to the user login screen.

**Features:**
- Username & password login  
- Password visibility toggle  
- Forgot Password option  
- “Login as User” quick switch  

**Screenshot:**  
<img src="https://github.com/Patil-Kalpak/CollabNest-App/blob/main/screenshots/adminLogin.jpeg" width="200">

---

## 🗓️ 11. Create New Event (Admin Only)  
Admins can create and publish events that become visible to all students in the app.

The event creation form includes all necessary details for a well-structured event post.

---

### 🔸 **Event Creation Form Fields**
Admins can enter:

- **Event Name**  
- **Event Date**  
- **Start Time & End Time**  
- **Location / Venue / Online Link**  
- **Event Description**  
- **Speaker / Host Names**  
- **Max Participants Allowed**  
- **Registration Link (Optional)**  
- **Prize Pool (Optional)**  
- **Event Coordinator (Optional)**  
- **Upload Event Poster**  

**Screenshots:**  
<img src="https://github.com/Patil-Kalpak/CollabNest-App/blob/main/screenshots/CreateEvent.jpeg" width="200" style="margin-right:20px;">
<img src="https://github.com/Patil-Kalpak/CollabNest-App/blob/main/screenshots/Createevent2.jpeg" width="200">

---

### ⚠️ **Duplicate Date Detection (Collision Check)**  
To maintain event scheduling clarity, CollabNest automatically checks if another event already exists on the selected date.

**If an event exists on that date:**
- The admin sees a warning message  
- They are prompted to choose another date  
- The event cannot be posted with a conflicting date  

This ensures clean scheduling and avoids overlapping or clashing events.

---

### ✔ **Successful Event Creation**  
After submitting all fields and passing validation, the event becomes visible to:
- **All students on the Home screen (Upcoming Events section)**  
- **The Event Calendar (highlighted with a dot)**  

Admins can then monitor participation through their club or separately.

---



## 📢 12. Send Notifications (Admin Only)  
CollabNest gives admins the ability to send important updates and announcements directly to students.  
Notifications are powered by **Firebase Cloud Messaging (FCM)** and can be targeted to **all users** or only to **participants of a specific event**.

---

### 🔸 **Send Notification to All Users**  
Admins can broadcast announcements that reach every student using the app.

**Features:**
- Enter **Notification Title**  
- Enter **Notification Message**  
- Send instantly to all users  
- Confirm dialog before sending  

**Screenshot:**  
<img src="https://github.com/Patil-Kalpak/CollabNest-App/blob/main/screenshots/sendNotificationpage.jpeg" width="200">

---

### 🔸 **Send Notification to Event Participants Only**  
Admins can also notify students who are registered for **a specific event**.

**Features:**
- Admin sees a list of all events  
- Selecting an event opens a popup  
- Enter Title & Message  
- Sends notification only to registered students  
- Useful for reminders like:  
  - "Event starts in 10 minutes"  
  - "Venue changed"  
  - "Bring your laptops"  

**Screenshot:**  
<img src="https://github.com/Patil-Kalpak/CollabNest-App/blob/main/screenshots/SendNotification2.jpeg" width="200">




## 🛠️ 13. Tech Stack  
CollabNest is built using a modern and scalable tech stack:

### **Frontend (Mobile App)**
- Kotlin (Android)
- XML for UI Layouts  
- ViewModel + LiveData  
- RecyclerView & ViewPager  
- Glide (Image Loading)

### **Backend**
- Firebase Authentication  
- Firebase RealTime Database  
- GitHub to store Images
- Firebase Cloud Messaging (FCM)
- High-performance operations
- Secure API endpoints
- Future scalability
- hosted on Render


 ## 👨‍💻 Developers & Contact  

**Kalpak Patil**  
📧 Email: kalpakpatil131@gmail.com
🔗 GitHub: https://github.com/Patil-Kalpak  

**Saina**  
📧 Email: sainasaindane28@gmail.com  

**Alfiya**  
📧 Email: heetgandhi2511@gmail.com  
 



