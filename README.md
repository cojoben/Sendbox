# Sandbox
Vulnerability Title: User Traverse Vulnerability Exists in Sandbox V6.1.0

Date: October 11, 2023

Utilizing Authors：Buckeye

Supplier homepage： https://www.yhz66.com/

Software Link：https://xafg.nh2000.com:6443/file2download/file/DownLoad?app=linuxservercentos

test platform：http://yhz.yhz2000.com/webfolder/#/doc/login

When accessing the chat interface after logging in to Sandbox http://yhz.yhz2000.com/webfolder/#/im/index The server will send a request to the/server/services2/user/getUserJwt interface, and the server will respond with a JWT token. Using this token, the user's information can be seen in the/im/user/78679 interface. By traversing 78679, other user information can be viewed
