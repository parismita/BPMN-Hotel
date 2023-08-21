Camunda: 8, (https://modeler.cloud.camunda.io/diagrams/79d8f8c4-bdc0-4a94-a090-c63118873d11--hotel-management?v=555,970,0.407)

Defects in Previous Model: 
1) No synchronization between pools start events
2) Receptionist was handling the assignment which increased its workload, exceeding load can lead to missed tasks and prone to errors, Hence housekeeping manager is introduced to channnelize the task assignment to cleaners and receiptionist is to take requests from the customer.
3) used send/receive tasks and events to specify which message is going where, in prev diagram it was not mentioned.
4) included more details on the process in this model, than the previous one.
