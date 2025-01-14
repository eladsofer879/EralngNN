The project includes a Distributed Neuro-Evolution NN algorithm to play a hunting game. The project was written in functional programming language - Erlang

Project overview:

1. Perform a learning mechanism in order to catch a running cat.
2. The learning process is being made via an evolutional neural network's algorithm. 
3. In order to alleviate the calculations, the learning process is being distributed into 4 nodes. Each node has a population of genes which it responsible for it’s evolution
4. Fault tolerant system – in case a node falls, the system redistribute the workload between the live nodes.
5. Each node is consisted of several components:
   * Master Server – OTP gen server
   * Population FSM – OTP gen statem
   * Agents Pool – OTP gen servers
   * Agents supervisor – OTP Supervisor

![image](https://github.com/user-attachments/assets/cdeee9c8-e8f7-414e-9c45-aea9ae7175e5)

Youtube link of the performance of the trained NN: https://www.youtube.com/watch?v=gjLjRERK-dA


<img width="774" alt="image" src="https://github.com/user-attachments/assets/e4cf0942-d3db-47e6-a082-c582a0f691ab">

Files:

1) Summary powerpoint

2) src code
