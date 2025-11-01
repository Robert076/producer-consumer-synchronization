# producer-consumer-synchronization
Two threads, a producer and a consumer, with the producer feeding the consumer.

Uses a mutex and 2 conditional variables.

There is a queue of adjustable size, and one thread (the producer one) pushes stuff to the queue while it's not full,
in the meantime the other thread (the consumer) takes stuff out of the queue.

It will compute the scalar product of 2 vectors.

Read the code for more insights.
