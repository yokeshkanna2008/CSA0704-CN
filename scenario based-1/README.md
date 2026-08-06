 #Error Detection using Parity Bit and Checksum

## Aim
To detect errors in transmitted messages using parity bit and checksum.

## What is Parity?
A parity bit is an extra bit added to data. It helps detect if a single bit changes during transmission.

## What is Checksum?
A checksum is calculated by adding the ASCII values of all characters. The receiver calculates it again and compares it with the original checksum.

## Result
Both parity and checksum detected the simulated transmission errors. The checksum is generally more reliable because it can detect more types of errors than a simple parity bit.