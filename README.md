# Random-Reddit-Memesite
This set of files can automate deployment of a python flask website on ubuntu. This website pulls random images from reddit. 
Credits for api :https://github.com/D3vd/Meme_Api.git

You can use configure ansible on your ubuntu server and run these playbooks directly from your control node to your managed nodes. I used aws with an ubuntu EC2 instance to host the website. You can refresh the website every 30 seconds for a new meme. The ansible playbook imports tasks directly from the present working directory to run on the managed node.

