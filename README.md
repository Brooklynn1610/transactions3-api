# transactions3-api

Differences: 

Deploy 2: Focuses on organizing code into a pattern (Models, Controllers, Routes) using the native MongoDB driver. All routes are public, and anyone can read or create transactions.

Deploy 3: A major security and structure upgrade. It replaces the native driver with Mongoose (ODM), adds user registration with password hashing (bcryptjs), and uses JWT middleware to lock down routes so only authenticated users can create or view their specific transactions.

Models: I am prefer 03's

Challenges: Stuck in heroku because and docker.file

# Screenshot

<img width="1512" height="982" alt="Screenshot 2026-05-27 at 7 18 54 AM" src="https://github.com/user-attachments/assets/c8ff2116-3c14-4cb3-82f4-584934a149d2" />
<img width="1512" height="982" alt="Screenshot 2026-05-27 at 7 16 34 AM" src="https://github.com/user-attachments/assets/8acb04f7-cad9-46c5-8246-929a20dcc6e3" />
<img width="1512" height="982" alt="Screenshot 2026-05-27 at 7 09 42 AM" src="https://github.com/user-attachments/assets/d672a7e0-2765-4057-9091-1ec27ef3a763" />
