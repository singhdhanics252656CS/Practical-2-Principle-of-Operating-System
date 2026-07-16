# Practical-2-Principle-of-Operating-System

Aim:
Process Communication using Message Passing                                                                                                 
Use message queues/pipes to solve the producer-consumer problem.                                                                            
Compare and contrast shared memory vs. message-passing approaches.                                                                          
Analyze blocking vs. non-blocking communication.                                                                                            


Extra question: Add a size limit to the queue (Queue(maxsize=3)) and observe the blocking
behavior.                                                                                                                                   
• Producer will wait (block) when the queue is full (i.e., has 3 items) — it can’t add
more until the consumer removes at least one.                                                                                               
• Consumer will wait (block) if the queue is empty — it can’t consume until producer
adds something.                                                                                                                             
