🎵 Music Playlist Manager using Doubly Linked List

A menu-driven Music Playlist Manager developed in C++ using the Doubly Linked List data structure. The project demonstrates insertion, deletion, traversal, and bidirectional navigation of songs in a playlist

📌 Project Overview

This application allows users to manage a music playlist efficiently through a console-based menu system. Each song is stored as a node containing:

Song Title
Artist Name
Previous Pointer (prev)
Next Pointer (next)

The playlist supports forward and backward navigation, making it an ideal demonstration of Doubly Linked List operations.

🛠️ Data Structure Used
Doubly Linked List
Dynamic memory allocation
Bidirectional traversal
Node insertion and deletion operations
🧩 Node Structure
C++
struct Song {
string title;
string artist;
Song* prev;
Song* next;
};
✨ Features
Add a new song
Delete a song
Display playlist
Display playlist in reverse order
Play current song
Play next song
Play previous song
Play complete playlist
Repeat entire playlist
Show current song
Exit application
📋 Menu Options
Plain Text
1. Add Song
2. Delete Song
3. Display Playlist
4. Display Playlist in Reverse
5. Play Current Song
6. Play Next Song
7. Play Previous Song
8. Play Complete Playlist
9. Repeat All
10. Show Current Song
11. Exit
🔄 Operations Implemented
➕ Insertion
Create a new song node.
Insert at the end of the playlist.
Update previous and next links.
➖ Deletion
Search song to delete.
Reconnect neighboring nodes.
Update head/current pointers when required.
▶️ Next Song Navigation
C++
current = current->next;
⏮️ Previous Song Navigation
C++
current = current->prev;
🔁 Reverse Traversal

Traverse from the last song toward the first using the prev pointer.

⚠️ Edge Cases Handled
Empty playlist
Single-song playlist
First node deletion
Last node deletion
Song not found
Previous navigation at first song
Next navigation at last song
🧪 Testing

The application has been tested for:

✅ Insertion Operations
 ✅ Deletion Operations
 ✅ Forward Traversal
 ✅ Reverse Traversal
 ✅ Next/Previous Navigation
 ✅ Repeat Playlist Functionality
 ✅ Boundary Conditions and Exceptions

📚 Learning Outcomes

This project demonstrates:

Node Creation
Insertion
Deletion
Traversal
Bidirectional Navigation
Current Node Management
Dynamic Memory Handling in C++

🚀 Technologies Used
C++
VS Code
Data Structures & Algorithms
Doubly Linked List
👩‍💻 Author

Vaishnavi Dhanawade
 Second Year B.Tech (Electronics & Computer Engineering)

