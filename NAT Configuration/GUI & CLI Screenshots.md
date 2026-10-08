
<img width="413" height="541" alt="image" src="https://github.com/user-attachments/assets/269deb4e-49cc-44d4-a1be-fe4831ac9e12" />
<img width="692" height="543" alt="image" src="https://github.com/user-attachments/assets/09bcefa5-3875-40e0-9abc-110ab2b53013" />

# Validation
 We can initiate traffic from PC and from CLI we can see NAT Translation in the session details for the traffic requested.

 Refer to the below CLI session details

 <img width="1357" height="755" alt="image" src="https://github.com/user-attachments/assets/ef23d915-9b03-48c4-a07f-bf1254e18f25" />


As it can be seen from session details, for the dns traffic in s2c flow destination ip is different from source ip of c2s flow. This shows Source NAT is done here.

 Source NAT : 172.16.71.2 ---> 172.16.60.51

 <img width="1354" height="860" alt="image" src="https://github.com/user-attachments/assets/05099ff7-de6a-4bed-b3c6-9ead225b893a" />
