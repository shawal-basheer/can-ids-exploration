CAN Bus Traffic Exploration

A first look at the Car Hacking: Attack and Defense Challenge 2020 dataset, started while preparing an application for the RISE master’s thesis on interpretable CAN bus intrusion detection.

What I looked at so far, using one file of normal driving traffic:

The recording is 74.7 seconds long and contains 179,346 messages, which is about 2,400 messages per second.

There are 73 distinct arbitration IDs on this bus.

The traffic is highly regular. The three most frequent IDs each appear exactly 7,466 times, which works out to 100 messages per second, or one every 10 milliseconds. The least frequent appear about once per second.

What I want to look at next: whether the gaps between individual messages are as regular as the averages suggest, and how those gaps change in the files that contain attacks.

The dataset is not included in this repository. It is available from IEEE DataPort.
