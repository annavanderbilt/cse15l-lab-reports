# Lab Report 2

## Part 1

`ChatServer` code: 

  ![Image](chatservercode1.png)
  ![Image](chatservercode2.png)

Using `add-message`:

  ![Image](addmsg1.png)

- The `handleRequest(URI url)` method is called.
- The relevant argument is the url of the server (`http://localhost:4000/add-message?s=Hello ChatServer!&user=Anna`), and the class field `chatHistory` is initialized as an empty String.
- After the first `add-message`, `chatHistory` is updated to `Anna: Hello ChatServer!` with a newline.

  ![Image](addmsg2.png)

- The `handleRequest(URI url)` method is called again.
- The relevant argument is again the url of the server (this time `http://localhost:4000/add-message?s=Hello Anna :D&user=ChatServer`), but now the class field `chatHistory` is the updated String (`Anna: Hello ChatServer!` plus a newline).
- After the second `add-message`, `chatHistory` is updated to display `ChatServer: Hello Anna :D` after the previous line. 


## Part 2 


