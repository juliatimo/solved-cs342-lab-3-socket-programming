Download Link: https://assignmentchef.com/product/solved-cs342-lab-3-socket-programming
<br>
<strong>Reference Text Book: </strong>“<em>Unix Network Programming</em>”, Volume 1, by W. Richard Stevens (publisher: Prentice Hall) (refer to first few chapters)

<strong><u>Table 1:  Allocation of applications to groups</u> </strong>

<table width="708">

 <tbody>

  <tr>

   <td width="64"><strong>  App ID </strong></td>

   <td width="71"> </td>

   <td width="35"> </td>

   <td width="29"> </td>

   <td width="35"><u>  </u></td>

   <td width="29"> </td>

   <td width="68"><strong><u>Students </u></strong></td>

   <td width="64"><strong>   Group </strong></td>

   <td width="35"><strong>IDs </strong></td>

   <td width="29"> </td>

   <td width="35"> </td>

   <td width="29"> </td>

   <td width="35"> </td>

   <td width="29"> </td>

   <td width="35"> </td>

   <td width="22"> </td>

   <td width="64"> </td>

  </tr>

  <tr>

   <td width="64"><strong>1 </strong></td>

   <td width="71">1</td>

   <td width="35"> </td>

   <td width="29">2</td>

   <td width="35"> </td>

   <td width="29">3</td>

   <td width="68">4</td>

   <td width="64">5</td>

   <td width="35"> </td>

   <td width="29">6</td>

   <td width="35"> </td>

   <td width="29">7</td>

   <td width="35"> </td>

   <td width="29">8</td>

   <td width="35"> </td>

   <td width="22">9</td>

   <td width="64"> </td>

  </tr>

  <tr>

   <td width="64"><strong>2 </strong></td>

   <td width="71">10</td>

   <td width="35"> </td>

   <td width="29">11</td>

   <td width="35"> </td>

   <td width="29">12</td>

   <td width="68">13</td>

   <td width="64">14</td>

   <td width="35"> </td>

   <td width="29">15</td>

   <td width="35"> </td>

   <td width="29">16</td>

   <td width="35"> </td>

   <td width="29">17</td>

   <td width="35"> </td>

   <td width="22">18</td>

   <td width="64"> </td>

  </tr>

  <tr>

   <td width="64"><strong>3 </strong></td>

   <td width="71">19</td>

   <td width="35"> </td>

   <td width="29">20</td>

   <td width="35"> </td>

   <td width="29">21</td>

   <td width="68">22</td>

   <td width="64">23</td>

   <td width="35"> </td>

   <td width="29">24</td>

   <td width="35"> </td>

   <td width="29">25</td>

   <td width="35"> </td>

   <td width="29">26</td>

   <td width="35"> </td>

   <td width="22">27</td>

   <td width="64"> </td>

  </tr>

  <tr>

   <td width="64"><strong>4 </strong></td>

   <td width="71">28</td>

   <td width="35"> </td>

   <td width="29">29</td>

   <td width="35"> </td>

   <td width="29">30</td>

   <td width="68">31</td>

   <td width="64">32</td>

   <td width="35"> </td>

   <td width="29">33</td>

   <td width="35"> </td>

   <td width="29">34</td>

   <td width="35"> </td>

   <td width="29">35</td>

   <td width="35"> </td>

   <td width="22">36</td>

   <td width="64"> </td>

  </tr>

  <tr>

   <td width="64"><strong>5 </strong></td>

   <td width="71">37</td>

   <td width="35"> </td>

   <td width="29">38</td>

   <td width="35"> </td>

   <td width="29">39</td>

   <td width="68">40</td>

   <td width="64">41</td>

   <td width="35"> </td>

   <td width="29">42</td>

   <td width="35"> </td>

   <td width="29">43</td>

   <td width="35"> </td>

   <td width="29">44</td>

   <td width="35"> </td>

   <td width="22">45</td>

   <td width="64"> </td>

  </tr>

  <tr>

   <td width="64"><strong>6 </strong></td>

   <td width="71">46</td>

   <td width="35"> </td>

   <td width="29">47</td>

   <td width="35"> </td>

   <td width="29">48</td>

   <td width="68">49</td>

   <td width="64">50</td>

   <td width="35"> </td>

   <td width="29">51</td>

   <td width="35"> </td>

   <td width="29">52</td>

   <td width="35"> </td>

   <td width="29">53</td>

   <td width="35"> </td>

   <td width="22">54</td>

   <td width="64"> </td>

  </tr>

  <tr>

   <td width="64"><strong>7 </strong></td>

   <td width="71">55</td>

   <td width="35"> </td>

   <td width="29">56</td>

   <td width="35"> </td>

   <td width="29">57</td>

   <td width="68">58</td>

   <td width="64">59</td>

   <td width="35"> </td>

   <td width="29">60</td>

   <td width="35"> </td>

   <td width="29">61</td>

   <td width="35"> </td>

   <td width="29">62</td>

   <td width="35"> </td>

   <td width="22">63</td>

   <td width="64"> </td>

  </tr>

  <tr>

   <td width="64"><strong>8 </strong></td>

   <td width="71">64</td>

   <td width="35"> </td>

   <td width="29">65</td>

   <td width="35"> </td>

   <td width="29">66</td>

   <td width="68">67</td>

   <td width="64">68</td>

   <td width="35"> </td>

   <td width="29">69</td>

   <td width="35"> </td>

   <td width="29">70</td>

   <td width="35"> </td>

   <td width="29">71</td>

   <td width="35"> </td>

   <td width="22">72</td>

   <td width="64"> </td>

  </tr>

  <tr>

   <td width="64"><strong>9 </strong></td>

   <td width="71">73</td>

   <td width="35"> </td>

   <td width="29">74</td>

   <td width="35"> </td>

   <td width="29">75</td>

   <td width="68">76</td>

   <td width="64">77</td>

   <td width="35"> </td>

   <td width="29">78</td>

   <td width="35"> </td>

   <td width="29">79</td>

   <td width="35"> </td>

   <td width="29">80</td>

   <td width="35"> </td>

   <td width="22">81</td>

   <td width="64">82</td>

  </tr>

 </tbody>

</table>

<strong> </strong>

<h1><strong>Application ID 1: </strong>Banking System using Client-Server socket programming</h1>

In this application, you require implementing two C programs, namely Client and Bank Server, and they communicate with each other based on TCP sockets. The goal is to implement a simple Banking System.




Initially, the client will connect to the bank server using the server’s TCP port already known to the client. After successful connection, the client sends a Login Message (containing the Username and password) to the bank server. The client side, we can have three different types of user modes namely, Bank_Customer, Bank_Admin and Police. The bank server has the following files with him: Login_file (contains the login entries, assume limited number of static entries only), Customer_Account_files (Assume the bank has 10 Bank_Customers only and one file for each customer, which maintains the transaction history. Refer to Login_file and Customer_Account_files formats for more details). Once the Bank server receives the login request, it validates the information and performs the functionalities according to the user mode type. The system must provide the following functionalities to the following users:

<ul>

 <li><strong>Bank_Customer:</strong> The customer should able to see AVAILABLE BALANCE in his/her account and MINI STATEMENT of his/her account.</li>

 <li><strong>Bank_Admin:</strong> The admin should be able to CREDIT/DEBIT the certain amount of money from any Bank_Customer ACCOUNT (as we do it in a SBI single window counter.&#x263a;). The admin must update the respective “Customer_Account_file” by appending the new information. Handel the Customer account balance underflow cases carefully.</li>

 <li><strong>Police: </strong>The police should only be able to see the available balance of all customers. He is allowed to view any Customers MINI STATEMENT by quoting the Customer _ID (i.e. User_ID with user_type as ‘C’).</li>

</ul>

<strong>Login_file entry format: </strong>

<table width="431">

 <tbody>

  <tr>

   <td width="135"><strong>User_ID</strong></td>

   <td width="135"><strong>Password</strong></td>

   <td width="162"><strong>User_Type (C/A/P) </strong></td>

  </tr>

 </tbody>

</table>

<strong>Customer _Account_files entry format:</strong>

<table width="650">

 <tbody>

  <tr>

   <td width="151"><strong>Transaction_Date</strong></td>

   <td width="283"><strong>Transaction Type (Credit/Debit)</strong></td>

   <td width="216"><strong>Available Account_Balance </strong></td>

  </tr>

 </tbody>

</table>

Implement the functionalities using proper REQUEST and RESPONSE Message formats. After each negotiation phase, the TCP connection on both sides should be closed gracefully releasing the socket resource. You should accept the IP Address and Port number from the command line (Don’t use a hard-coded port number). Prototype for command line is as follows:

<h2>Prototypes for Client and Server</h2>

<strong>Client: </strong>&lt;executable code&gt;&lt;Server IP Address&gt;&lt;Server Port number&gt;

<strong>Server: </strong>&lt;executable code&gt;&lt;Server Port number&gt;

NB: Please make necessary and valid assumptions whenever required.







<h1><strong>Application ID 2: </strong>Client Server Trading System using socket programming</h1>

A Client-Server Based Trading System is to be designed with the following specifications. There will be a set of traders who will trade with each other in the automated system. There will be a Server which will register requests from traders for buying and selling quantities of Items. The Server will also match the buy with the sell requests from different traders based on certain price rules (as listed below). Traders will log on to the trading system through the trading client (assume Trader ID and password is stored in a file). They will have the option to view the currently available items (for buy/sell), their quantities and their prices. They will also send requests for buying and selling items and specify the quantity and price. Traders will also have the option to view their matched trades at any time. There are ten known items which the traders can trade in with their codes from 1 to 10. There will be a maximum of 5 traders (with codes from 1 to 5) who can log on to the system and work. One trader should work from one client at a time only.The functionalities of any client will be:

<ul>

 <li><strong>Login to the System:</strong> The trader will execute the client, give the trader number and will be logged in. After that he/she will have the following options in a menu. Several clients will login (from different terminals) and assumed they don’t trade simultaneously to reduce the complexity.</li>

 <li><strong>Send Buy Request:</strong> The trader will send a buy request by stating the item code, the quantity and unit price.</li>

 <li><strong>Send Sell request:</strong> The trader will send a sell request by stating the item code, the quantity and unit price.</li>

 <li><strong>View Order Status:</strong> The Trader can view the position of buy and sell orders in the system. This will display the current best sell (least price) and the best buy (max price) for each item and their quantities.</li>

 <li><strong>View Trade Status:</strong> The trader can view his/her matched trades. This will provide the trader with the details of what orders were matched, their quantities, prices and counterparty code.</li>

</ul>

There will be only one server which will be running and perform the functions of order processing and trade matching in addition to acknowledging logins by clients and  servicing their requests. The order processing will be as follows. There will be a buy and a sell order queue for each item. On receiving buy/sell order request from a trader, the server will put it in the appropriate order queue. If there is a possibility of a trade match, then that trade match will take place, the traded items will be appropriately updated and the result of the trade along with the details of the counterparties, item, quantity and price will be stored in the traded set. The matching rule is as follows:

<ol>

 <li>On a buy Request at price P and quantity Q of an item I, the server will check if there is any pending sell order for the same item at price P’ ≤ P.</li>

 <li>Among all such pending sell orders, the match will be made with the one having the least selling price.</li>

 <li>If both have same quantity, i.e., Q’= Q, then both these orders will be removed from their respective queues and the result will be put into the traded set.</li>

 <li>If Q’ &gt; Q then the buy request will be fully traded and the remaining part, i.e., Q’ – Q of the sell order will remain in the sell queue at the same price P’.</li>

 <li>On the other hand, if Q’ &lt; Q then the sell order will be fully traded and the remaining buy order will be tested for more matches.</li>

 <li>If the buy order cannot be matched, it will be put into the buy queue.</li>

 <li>A similar rule will apply for a sell request and all these requests will be handled in a FCFS basis.</li>

</ol>

You should accept the IP Address and Port number from the command line (Don’t use a hard-coded port number). *Please make necessary and valid assumptions whenever required.

Prototype for command line is as follows:

<h2>Prototypes for Client and Server</h2>

<strong>Client: </strong>&lt;executable code&gt;&lt;Server IP Address&gt;&lt;Server Port number&gt; <strong>Server: </strong>&lt;executable code&gt;&lt;Server Port number&gt;

<strong> </strong>

<h1><strong>Application ID 3: </strong>Base64 encoding system using Client-Server socket programming</h1>

In this application, you require to implement two C programs, namely server and client to communicate with each other based on TCP sockets. The aim is to implement simple Base64 encoding communication protocol.

Initially, server will be waiting for a TCP connection from the client. Then, client will connect to the server using server’s TCP port already known to the client. After successful connection, the client accepts the text input from the user and encodes the input using Base64 encoding system. Once encoded message is computed the client sends the Message (Type 1 message) to the server via TCP port. After receiving the Message, server should print the received and original message by decoding the received message, and sends an ACK (Type 2 message) to the client. The client and server should remain in a loop to communicate any number of messages. Once the client wants to close the communication, it should send a Message (Type 3 Message) to the server and the TCP connection on both the server and client should be closed gracefully by releasing the socket resource.

The messages used to communicate contain the following fields:

<table width="275">

 <tbody>

  <tr>

   <td width="169"><strong>Message_ Type </strong></td>

   <td width="106"><strong>Message </strong></td>

  </tr>

 </tbody>

</table>

<ol>

 <li>Message_type: integer</li>

 <li>Message: Character [MSG_LEN], where MSG_LEN is an integer constant</li>

 <li>&lt;Message&gt; content of the message in Type 3 message can be anything.</li>

</ol>




You also require implementing a “<strong><em>Concurrent Server</em></strong>“, i.e., a server that accepts connections from multiple clients and serves all of them <em>concurrently</em>.

You should accept the IP Address and Port number from the command line (Don’t use a hard-coded port number).

Prototype for command line is as follows:

<h2>Prototypes for Client and Server</h2>

<strong>Client: </strong>&lt;executable code&gt;&lt;Server IP Address&gt;&lt;Server Port number&gt; <strong>Server: </strong>&lt;executable code&gt;&lt;Server Port number&gt;




NB: Please make necessary and valid assumptions whenever required.

<strong><em> </em></strong>

<strong><em><u>Base64 Encoding System Description:</u> </em></strong>

Base64 encoding is used for sending a binary message over the net. In this scheme, groups of 24bit are broken into four 6 bit groups and each group is encoded with an ASCII character. For binary values 0 to 25 ASCII character ‘A’ to ‘Z’ are used followed by lower case letters and the digits for binary values 26 to 51 &amp; 52 to 61 respectively. Character ‘+’ and ‘/’ are used for binary value 62 &amp; 63 respectively. In case the last group contains only 8 &amp; 16 bits, then “==” &amp; “=” sequence are appended to the end.

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<h1><strong>Application ID 4: </strong>Multi-stage DNS Resolving System using Client-Server socket programming</h1>

In this application, you require implementing three C programs, namely Client, Proxy Server (which will act both as client and server) and DNS Server, and they communicate with each other based on TCP sockets. The aim is to implement a simple 2 stage DNS Resolver System.




Initially, the client will connect to the proxy server using the server’s TCP port already known to the client. After successful connection, the client sends a Request Message (Type 1/Type 2) to the proxy server. The proxy server has a limited cache (assume a cache with three IP to Domain_Name mapping entries only). After receiving the Request Message, proxy server based on the Request Type (Type 1/Type 2) searches its cache for corresponding match. If match is successful, it will send the response to the client using a Response Message. Otherwise, the proxy server will connect to the DNS Server using a TCP port already known to the Proxy server and send a Request Message (same as the client). The DNS server has a database (say .txt file) with it containing set of Domain_name to IP_Address mappings. Once the DNS Server receives the Request Message from proxy server, it searches in its file for possible match and sends a Response Message (Type 3/Type 4) to the proxy server. On receiving the Response Message from DNS Server, the proxy server forwards the response back to the client. If the Response Message type is 3, then the proxy server must update its cache with the fresh information using FIFO scheme. After each negotiation phase, the TCP connection on both sides should be closed gracefully releasing the socket resource.

<strong>Request Message Format: </strong>

<table width="199">

 <tbody>

  <tr>

   <td width="109">Request_Type</td>

   <td width="89">Message</td>

  </tr>

 </tbody>

</table>

<ul>

 <li>Type 1: Message field contains Domain Name and requests for corresponding IP address.</li>

 <li>Type 2: Message field contains IP address and request for the corresponding Domain Name.</li>

</ul>

<strong>Response Message Format: </strong>

<table width="242">

 <tbody>

  <tr>

   <td width="143">Response_Type</td>

   <td width="98">Message</td>

  </tr>

 </tbody>

</table>

<ul>

 <li>Type 3: Message field contains Domain Name/IP address.</li>

 <li>Type 4: Message field contains error message “entry not found in the database”.</li>

</ul>

You should accept the IP Address and Port number from the command line (Don’t use a hard-coded port number).

Prototype for command line is as follows:

<h2>Prototypes for Client and Server</h2>

<strong>Client: </strong>&lt;executable code&gt;&lt;Server IP Address&gt;&lt;Server Port number&gt;

<strong>Server: </strong>&lt;executable code&gt;&lt;Server Port number&gt;

NB: Please make necessary and valid assumptions whenever required.

<strong> </strong>

<h1><strong>Application ID 5: </strong>Client-Server programming using both TCP and UDP sockets</h1>

In this application, you require to implement two C programs, namely server and client to communicate with each other based on both TCP and UDP sockets. The aim is to implement a simple 2 stage communication protocol.

Initially, server will be waiting for a TCP connection from the client. Then, client will connect to the server using server’s TCP port already known to the client. After successful connection, the client sends a Request Message (Type 1 message) to the server via TCP port to request a UDP port from server for future communication. After receiving the Request Message, server selects a UDP port number and sends this port number back to the client as a Response Message (Type 2 Message) over the TCP connection. After this negotiation phase, the TCP connection on both the server and client should be closed gracefully releasing the socket resource.

In the second phase, the client transmits a short Data Message (Type 3 message) over the earlier negotiated UDP port. The server will display the received Data Message and sends a Data Response (type 4 message) to indicate the successful reception. After this data transfer phase, both sides close their UDP sockets.

The messages used to communicate contain the following fields:

<table width="325">

 <tbody>

  <tr>

   <td width="117"><strong>Message_Type </strong></td>

   <td width="128"><strong>Message_Length </strong></td>

   <td width="79"><strong>Message </strong></td>

  </tr>

 </tbody>

</table>

<ol>

 <li>Message_type: integer</li>

 <li>Message_length: integer</li>

 <li>Message: Character [MSG_LEN], where MSG_LEN is an integer constant</li>

</ol>

&lt;Data Message&gt; in <strong>Client </strong>will be a <strong>Type 3</strong> message with some content in its message section.

You also require implementing a “<strong><em>Concurrent Server</em></strong>“, i.e., a server that accepts connections from multiple clients and serves all of them <em>concurrently</em>.

You should accept the IP Address and Port number from the command line (Don’t use a hard-coded port number).

Prototype for command line is as follows:

<h2>Prototypes for Client and Server</h2>

<strong>Client: </strong>&lt;executable code&gt;&lt;Server IP Address&gt;&lt;Server Port number&gt;

<strong>Server: </strong>&lt;executable code&gt;&lt;Server Port number&gt;

NB: Please make necessary and valid assumptions whenever required.






















<h1><strong>Application ID 6: </strong>Relay based Peer-to-Peer System using Client-Server socket programming</h1>

In this application, you require implementing three C programs, namely Peer_Client, and Relay_Server and Peer_Nodes, and they communicate with each other based on TCP sockets. The aim is to implement a simple Relay based Peer-to-Peer System.




Initially, the Peer_Nodes (peer 1/2/3 as shown in Figure 1) will connect to the Relay_Server using the TCP port already known to them. After successful connection, all the Peer_Nodes provide their information (IP address and PORT) to the Relay_Server and close the connections (as shown in Figure 1). The Relay_Server actively maintains all the received information with it. Now the Peer_Nodes will act as servers and wait to accept connection from Peer_Clients (refer phase three).

In second phase, the Peer_Client will connect to the Relay_Server using the server’s TCP port already known to it. After successful connection; it will request the Relay_Server for active Peer_Nodes information (as shown in Figure 2). The Relay_Server will response to the Peer_Client with the active Peer_Nodes information currently having with it. On receiving the response message from the Relay_Server, the Peer_Client closes the connection gracefully.

In third phase, a set of files (say, *.txt) are distributed evenly among the three Peer_Nodes. The Peer_Client will take “file_Name” as an input from the user. Then it connects to the Peer_Nodes one at a time using the response information. After successful connection, the Peer_Client tries to fetches the file from the Peer_Node. If the file is present with the Peer_Node, it will provide the file content to the Peer_Client and the Peer_Client will print the file content in its terminal. If not, Peer_Client will connect the next Peer_Node and performs the above action. This will continue till the Peer_Client gets the file content or all the entries in the Relay_Server Response are exhausted (Assume only three/four Peer_Nodes in the system).

Implement the functionalities using appropriate REQUEST and RESPONSE Message formats. After each negotiation phase, the TCP connection on both sides should be closed gracefully releasing the socket resource. You should accept the IP Address and Port number from the command line (Don’t use a hard-coded port number).

Prototype for command line is as follows:

<h2>Prototypes for Client and Server</h2>

<strong>Client: </strong>&lt;executable code&gt;&lt;Server IP Address&gt;&lt;Server Port number&gt;

<strong>Server: </strong>&lt;executable code&gt;&lt;Server Port number&gt;

NB: Please make necessary and valid assumptions whenever required.




<h1><strong>Application ID 7: </strong>Point-of-Sale Terminal using socket programming</h1>

Use socket programming to implement a simple client and server that communicate over the network and implement a simple application involving Cash Registers. The client implements a simple cash register that opens a session with the server and then supplies a sequence of codes (refer <strong><em>request-response messages format</em></strong>) for some products. The server returns the price of each one, if the product is available, and also keeps a running total of purchases for each client’s transactions.  When the client closes the session, the server returns the total cost. This is how the point-of-sale terminals should work. You can use a TXT file as a database to store the UPC code and item description at the server end.

You also require implementing a “<strong><em>Concurrent Server</em></strong>“, i.e., a server that accepts connections from multiple clients and serves all of them <em>concurrently</em>.

<strong><em>Request-response messages format </em></strong>

<table width="404">

 <tbody>

  <tr>

   <td width="135"><strong>Request_ Type</strong></td>

   <td width="135"><strong>UPC-Code</strong></td>

   <td width="135"><strong>Number</strong></td>

  </tr>

 </tbody>

</table>

Where

<ul>

 <li><strong><em>Request_Type</em></strong> is either 0 for <strong><em>item</em></strong> or 1 for <strong><em>close</em></strong>.</li>

 <li><strong><em>UPC-code</em></strong> is a 3-digit unique product code; this field is meaningful only if the <strong><em>Request_Type</em></strong> is 0.</li>

 <li><strong><em>Number</em></strong> is the number of items being purchased; this field is meaningful only if the <strong><em>Request_Type</em></strong> is 0.</li>

</ul>

For the <strong><em>Close</em></strong> command, the server returns a number, which is the total cost of all the transactions done by the client. For the <strong><em>item</em></strong> command, the server returns:

<table width="259">

 <tbody>

  <tr>

   <td width="160"><strong>Response_ Type</strong></td>

   <td width="100"><strong>Response</strong></td>

  </tr>

 </tbody>

</table>

Where:

<ul>

 <li>&lt;Response_type&gt; is 0 for <strong><em>OK</em></strong> and 1 for <strong><em>error</em></strong></li>

 <li>If <strong><em>OK</em></strong>, then &lt;Response&gt; is as follows:

  <ul>

   <li>if client command was “close”, then &lt;response&gt; contains the total amount.</li>

   <li>if client command was “item”, then &lt;response&gt; is of the form &lt;price&gt;&lt;name&gt;              where</li>

  </ul></li>

</ul>

&lt;price&gt; is the price of the requested item

&lt;name&gt; is the name of the requested item

<ul>

 <li>If <strong><em>error</em></strong>, then &lt;Response&gt; is as follows: a null terminated string containing the error; the only possible errors are “<strong><em>Protocol Error</em></strong>” or “<strong><em>UPC is not found in database</em></strong>“.</li>

</ul>

You should accept the IP Address and Port number from the command line (Don’t use a hard-coded port number).

Prototype for command line is as follows:

<h2>Prototypes for Client and Server</h2>

<strong>Client: </strong>&lt;executable code&gt;&lt;Server IP Address&gt;&lt;Server Port number&gt;

<strong>Server: </strong>&lt;executable code&gt;&lt;Server Port number&gt;

The connection to the server should be gracefully terminated. When the server is terminated by pressing <strong><em>Control+C</em></strong>, the server should also gracefully release the open socket (Hint: requires use of a signal handler).

NB: Please make necessary and valid assumptions whenever required

<h1><strong>Application ID 8: </strong>File Transfer Protocol (FTP) using Client-Server socket programming</h1>

In this assignment, you require to implement two C programs, namely server and client to communicate with each other based on TCP sockets. The goal is to implement a simple File Transfer Protocol (FTP). Initially, server will be waiting for a TCP connection from the client. Then, client will connect to the server using server’s TCP port already known to the client. After successful connection, the client should be able to perform the following functionalities:

<ul>

 <li><strong>PUT:</strong> Client should transfer the file specified by the user to the server. On receiving the file, server stores the file in its disk. If the file is already exists in the server disk, it communicates with the client to inform it. The client should ask the user whether to overwrite the file or not and based on the user choice the server should perform the needful action.</li>

 <li><strong>GET: </strong>Client should fetch the file specified by the user from the server. On receiving the file, client stores the file in its disk. If the file is already exists in the client disk, it should ask the user whether to overwrite the file or not and based on the user choice require to perform the needful action.</li>

 <li><strong>MPUT and MGET:</strong> MPUT and MGET are quite similar to PUT and GET respectively except they are used to fetch all the files with a particular extension (e.g. .c, .txt, etc.). To perform these functions both the client and server require to maintain the list of files they have in their disk. Also implement the file overwriting case for these two commands as well.</li>

</ul>

Use appropriate message types to implement the aforesaid functionalities. For simplicity assume only .txt and .c file(s) for transfer.

You should accept the IP Address and Port number from the command line (Don’t use a hard-coded port number).

Prototype for command line is as follows:

<h2>Prototypes for Client and Server</h2>

<strong>Client: </strong>&lt;executable code&gt;&lt;Server IP Address&gt;&lt;Server Port number&gt;

<strong>Server: </strong>&lt;executable code&gt;&lt;Server Port number&gt;

NB: Please make necessary and valid assumptions whenever required.

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<h1><strong>Application ID 9: TFTP Server</strong></h1>

This application involves writing a TFTP client in C. TFTP stands for Trivial File Transfer Protocol and is the predecessor to FTP, however uses UDP for communication. It is still used today for transferring new firmware to routers and other embedded devices and also for booting network terminals.

It is a simple protocol and therefore straightforward to understand. It has two main uses:

<ul>

 <li>Transferring a file from a client to server.</li>

 <li>Transferring a file from a server to a client.</li>

</ul>

Your task will be to write code for a client (you do not have to implement a server) that can perform both of these functions. In other words, you need to write code that can PUT a file from your client onto a server and GET a file from a server to your client.

The first thing you need to do after finishing reading this instruction is to very thoroughly read the RFC1350 that details TFTP. The RFC document contains all the information you need about how TFTP works, so it is essential that you read and understand it before starting to program.

You have to do the followings.




<ol>

 <li>Write the socket handling code to open the UDP socket to the server (do not use TCP sockets).</li>

 <li>Open and close the file being dealt with.</li>

 <li>Construct packets using the pre-defined packet header and send the following</li>

</ol>

<ul>

 <li>Read request packets</li>

 <li>Write request packets</li>

 <li>Acknowledgment packets</li>

 <li>Data packets</li>

</ul>

<ol start="4">

 <li>Handle receiving data and perform the appropriate action</li>

</ol>

<ul>

 <li>Write data to file</li>

 <li>Read data from file and send to server</li>

 <li>Handle errors from server</li>

</ul>




You should accept the IP Address and Port number from the command line (Don’t use a hard-coded port number).

Prototype for command line is as follows:

<h2>Prototypes for Client and Server</h2>

<strong>Client: </strong>&lt;executable code&gt;&lt;Server IP Address&gt;&lt;Server Port number&gt;

<strong>Server: </strong>&lt;executable code&gt;&lt;Server Port number&gt;

NB: Please make necessary and valid assumptions whenever required.