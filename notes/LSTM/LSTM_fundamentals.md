# LSTM Fundamentals

## What is Sequence Data?

Sequence data contains observations that have an order in time.

Example:
10,20,30,40,50

## What is a Sliding Window?

Input:
[10,20,30,40]

Target:
[50]

## Sequence Length

Number of past timesteps provided to the model.

Example:
sequence_length = 4