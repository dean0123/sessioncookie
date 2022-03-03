# sessioncookie
session vs cookie
- use Session, Cookie and LocalStorage in Node.js Framework 
 Session can store in 2 places. 1. on server, 2 on clinet
 
1. express-session: Server node.js server module, Generate session ID keep at client browser cookie. Server can save session ID and other key values in server session store (Memory, file, DB and other persistance session store) 
2. cookie-session: Server Node.js code module, Store session ID and other cookie key values (4K max) at client browser, Server site need to handle seperately. 
3. localstorage: H5 Browser Client Storage, access from client HTML JS code only. By now didn't see Server code module can access client browser localstorage yet (2022-03-02)
4. sessionStorage: H5 Browser Client Storage, same as localStorage, but will be gone after session disconnect terminated. 
