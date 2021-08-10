# Basic building Block of Web Development


## IP  

* IP stands for Internet Protocol.

* Internet protocol is the communications protocol that is address assigned to each device to connected to the network.

* Data is divided into the small pieces called 'Packet'.

## Classes in IPv4
|**CLASS**|**ADDRESS RANGE**|**USED IN**|  
| ------------- | -------------| -----------|  
|Class A|0.0.0.0-127.255.255.255|Very large networks|  
|Class B|128.0.0.0-191.255.255.255|Medium networks|    
|Class C|192.0.0.0-223.255.255.255|Small networks|    
|Class D|224.0.0.0-239.255.255.255|Multicast| 
|Class E|240.0.0.0-255.255.255.255|Reserved for Future Research |
## Port
* When referring to a physical device, a hardware port or peripheral port is a hole or connection found on the front or back of a computer
* Ports allow computers to access external devices such as printers

## Port Number

* Port number related to the network addressing.
* Port Number, which helps to get connected with a particular server.
* There are total 65535 ports      

|**Port**|**Description**|   
|-------------- | -----------------|      
|Port 0 to 1023|Reserved port used by system|  
|Port 1024 to 49151|Application port|  
|Port 49152 to 65535|Open port| 

## Web Port
*  2 web port assigned for HTTP and HTTPS
*  For HTTP port 80 is used and for HTTPS port 443 is used

 ### Server 

 <p> A server is a hardware and software devices which bascially take a request from thhe client or user and give it back to response.</p>

 ### Web server

 <p>Websites is a collection of web pages while web server is a software that respond to the request for the resources. </p>


<!-- HTTP Verbs -->
## HTTP Verbs


 > HTTP verb nothing but the set of requests methods to indicate the action to be performed for the given resource.

| Methods       | Description                              |
| ------------- | -------------                            |      
| POST          | It is used to send a data to the server. eg.Uploading a file.                                                       |
| GET           | It is used to retrive the information from the server using given URL.                                                  |
| PUT           |  It is used to request the server to store the included body at a location specified by the given URL.                   |
| HEAD          | This method is same as that of a GET request, but without the response body and it transfers the header section only.  |
| DELETE        | It will delete the specified resources.   |
| CONNECT       | It will establish the tunnel to the server identify by the resource.                                                   |
| OPTIONS       | It will describe communication options for the target resouce.                                                    |
