agrona-manytooneringbuffer-example
===

This example shows you how to send fire-and-forget messages between applications using an [Agrona](https://github.com/real-logic/Agrona) ManyToOneRingBuffer.

The example starts a consumer that receives messages sent from multiple producers at a set interval.

##Running the Example
The example can be run using the following gradle command:

```
$ ./gradlew run
```