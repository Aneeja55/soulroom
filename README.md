# 💻 TinkerSpace Badge

Built something awesome at TinkerSpace?  
**Don’t let it go unnoticed.**  
Use this badge to proudly showcase your work and show others you were there, building something real.

---

## 🌟 What Is This?

The **TinkerSpace Badge** is more than a sticker. It’s your proof that you didn’t just talk about building—you actually did it.  
It tells the world you were part of something hands-on, something that matters.

> Projects fade. But when you wear this badge, people know you were _in the room_ where it happened.

---

## ✅ Who Can Use It?

This badge is for:

- 🛠 Makers who’ve built or contributed to projects at TinkerSpace  
- 👩‍💻 Hackathon participants  
- 📣 Supporters of hands-on learning and tech-for-good  
- 💡 Anyone who doesn’t just scroll, but actually builds  

---

## 📌 Why You Should Use This Badge

✔ Show you’re a **real builder**, not just a watcher  
✔ Help others discover cool TinkerSpace projects  
✔ Become part of the **maker story**—someone who inspires others  
✔ It’s proof you took part in a growing community of doers  

> _If your README doesn’t say “Built at TinkerSpace,” did you really build it at TinkerSpace?_

---

## 🧩 How to Use

Copy the code below into your README, profile, or docs:

```markdown
[![💻 Built at TinkerSpace](https://img.shields.io/badge/Built%20at-TinkerSpace-blueviolet?style=for-the-badge&label=%F0%9F%92%BBBuilt%20at&labelColor=turquoise&color=white)](https://tinkerhub.org/tinkerspace)



# SoulRoom


## Basic Details
### Team Name: Cybrosis


### Team Members
- Member 1: Anandhu S
- Member 2: Anaya Wilson
- Member 3: Aneeja J
- Member 4: Abhinav Rajesh


### Hosted Project Link
https://soulroom-six.vercel.app/

### Project Description

1.Only authenticated users can access and post messages in chat rooms.

2. Real-Time Messaging
Messages are stored in a messages table in Supabase.
Each message is associated with a room_id, a sender_id, and content.
Supabase real-time listeners (supabase.from(...).on(...)) keep the chat live without needing to refresh the page.
3. Room-Based Architecture
Users can join different chat rooms.
Each message is tied to a specific room via the room_id column.
Room switching filters messages accordingly.

4. Row Level Security (RLS)
The Supabase messages table uses RLS policies to secure data.
Authenticated users are only allowed to:
Insert messages if the sender_id matches their own auth.uid().
View messages for rooms they belong to (optional).


How It Works

This project is a real-time live chat application built using React for the frontend and Supabase for the backend. Users must authenticate themselves through Supabase Auth, which provides secure login and session handling. Once logged in, users can join specific chat rooms, where the app fetches existing messages from the Supabase database. When a user sends a message, it is inserted into the messages table in the Supabase PostgreSQL database, along with metadata like the sender's ID and room ID. Supabase Realtime enables live updates by listening to new message inserts—whenever a new message is added to the database for a specific room, it is pushed instantly to all clients subscribed to that room. This ensures that the chat updates in real time without the need for manual refreshes. The app uses Supabase’s Row Level Security (RLS) policies to ensure that only authenticated users can insert and view messages, and only for the correct rooms. The frontend UI is already styled and functional using Tailwind CSS, and no changes are needed there. Overall, the application offers a secure, responsive, and scalable real-time messaging experience, all without a custom backend server.

## AI Tools used
ChatGpt
Lovable
Supabase
GitHub Copilot

### Implementation
The implementation of this live chat application begins with setting up the Supabase backend, where the messages table is created to store chat data, including fields like content, room_id, sender_id, and timestamps. Row Level Security (RLS) is enabled on the table, and policies are written to ensure that only authenticated users can insert and read messages relevant to them. On the frontend, the app is built using React and Tailwind CSS, creating a clean and interactive user interface. User authentication is handled via Supabase Auth, allowing users to log in and maintain sessions securely. Once authenticated, users are assigned a room and can send messages. When a message is sent, a POST request inserts the message into the Supabase database, and Supabase Realtime triggers push the new message to all connected clients in that room. The frontend listens for these updates using supabase.channel() and updates the UI dynamically. Overall, the implementation leverages Supabase’s built-in authentication, database, and real-time features to create a fully functional, serverless chat experience.



# Screenshots 
![landing page](https://github.com/user-attachments/assets/02543528-f389-4cbd-8b48-d6dbb6de228c)
![signup](https://github.com/user-attachments/assets/23eba463-26f4-4bfa-a0fa-20af0f4bc3d7)
![login](https://github.com/user-attachments/assets/82a57f96-c1a1-44eb-8363-372fcbfbffda)
![chat](https://github.com/user-attachments/assets/7a536f85-baf7-4de5-a8e9-3a0e19588f8f)
![thoughts sharing](https://github.com/user-attachments/assets/e14149d7-ee05-4b34-a664-1cb95369042c)
![plant](https://github.com/user-attachments/assets/97f416e5-b4c2-47d8-adf2-1656bba3a1ab)


Mobile Interface
![mobile landing page](https://github.com/user-attachments/assets/071b4fa6-c204-4fcb-b288-818fed303efd)

![mobile login](https://github.com/user-attachments/assets/ca8de394-c2bc-44f7-bbcc-009299e3b283)
![mobile create room](https://github.com/user-attachments/assets/d2731491-c7f2-48a6-b32e-172e990532f3)
![mobile roomcode creation](https://github.com/user-attachments/assets/2aa061b0-dd5c-47bb-bf1c-76fa9e0c72d4)




### Project Demo

https://github.com/user-attachments/assets/d86fade0-a760-4cd3-a30f-9207786879ec



