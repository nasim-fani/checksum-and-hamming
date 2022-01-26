# checksum-and-hamming
Data layer error detection and correction

---
## Error Detection

**checksum**

*Step-01:*
 
At sender side,

If m bit checksum is used, 


1.   The data unit to be transmitted is divided into segments of m bits.
2.   All the m bit segments are added.
3.   The result of the sum is then complemented using 1’s complement arithmetic.
The value so obtained is called as **checksum**.
 

*Step-02:*
 

The data along with the checksum value is transmitted to the receiver.
 

*Step-03:*
 

At receiver side,

If m bit checksum is being used, 
1. The received data unit is divided into segments of m bits.
2. All the m bit segments are added along with the checksum value. 
3. The value so obtained is complemented and the result is checked.

---
## Error Correction

**Hamming code**

*Steps:*

1.   Calculate the no of redundant bits required
2.   Determine the parity bits
3.   Check for errors
