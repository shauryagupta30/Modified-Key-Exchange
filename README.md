# DHKE-NIS

How to Run:

- Make sure you are in root directory of project
- JDK installed in your machine and Java Path set

For Starting Server:

```shell script
# For compilation
javac -classpath src/ src/server/Server.java 
# For Execution - Arguments are mandatory
java -classpath src/ server.Server <server_id> 9001
```

For Starting Client
```shell script
# For compilation
javac -classpath src/ src/client/Client.java 
# For Execution - Arguments are mandatory
java -classpath src/ client.Client <client_id>
```



Our proposed project aims to Implement, Test Validity, Feasibility and Practical Application of  a Proposed Key Sharing Algorithm based on Diffie-Hellman Key Exchange Algorithm for Thin clients with resource constraints
 
# The following objectives have been achieved which were initially proposed to be completed:

1.To find a solution for implementing a improved Diffie-Hellman Key Agreement algorithm to improve the security of Embedded Systems and IoT devices with limited computational resources.

2.To Implement the computationally modified Diffie-Hellman Algorithmin Java.3.Testing the results which include: Testing the Efficiencyof the implemented algorithm along with comparison with existing diffie-Hellman Key exchange algorithmand obtain Quantitative and Qualitative measures to prove the feasibility of the given implementation

Some other results and key highlights:

1.Designed caching technique for higher efficiency and lesser search times and searchcycles.[discussed on pg. 27],which resulted in decreased time for overall computations in the long term application of DH Algorithm which require repetitive connection and disconnection cycles.

2.Implemented new connection request method supporting the above point.[Discussed on pg .28]Conclusion:Our Studyandconcludes that the use of computationally modified Diffie Hellman Key exchange Algorithm allows the computationally constrained clients to use a secure key exchange mechanism as stated in [17]“manythin clients do not use any security mechanism for saving computational resources”.

Our study provides the evidence of the given approach in [17] is implementable and also introduced 2 new design methodsto make the implementation of Modified Diffie-Hellman key exchange mechanism to be easier, these methods as mentioned above in “Some other results and key highlights”section..
