# DDK_DDoS_tool
First style will be a type that let server send SYN/ACK to the random client with fake IP and get no response.

![image](https://user-images.githubusercontent.com/67073582/121868093-299b4580-cd33-11eb-9485-67a0efac0e33.png)

* The capacity of the queue is limited.
* The data of SYN should have been keep in the queue for a peroid of the time.
* We are an anonymous client, so, of couse, we won't respond.
* The server will resend SYN/ACK five times during 1s + 2s + 4s+ 8s+ 16s + 32s = 63s in linux.
* So ... we can do something.
