# play-slam
A game of cards I played with my daughter's. We are making this game and therefore we are making the rules the same as we played then.

Thank You to https://github.com/pakastin/deck-of-cards/

data ideas
data stream two a fast and long:

fast
```
Starting deck 1234567890JQK1234567890JQK1234567890JQK1234567890JQK // dropping soots

list all posablie moves:
  table:
  12345 //drop inner moves
  aA|Bb
  67890 //drop inner moves
  
Moves to concider

1A,1B,2A,2B,3A,3B,4A,4B,5A,5B,6A,6B,7A,7B,8A,8B,9A,9B,0A,0B

Moves posib - normally two or three moves like:
["1A","3A","8B"]

Now we can just send 1,2 or 3

so the game state can be sent with:
3940J54QJ8642725Q0QJ4838300167KJ715969289KQ316K15K27110311342...
```
decode
```
3940J   // 0
54QJ    // 1
864     // 2
27      // 3
2       // 4
5Q0QJ   // 5
4838    // 6
300     // 7
16      // 8
7       // 9
KJ71596928 a
9          A
KQ316K15K2 b
7          B
            <----\
Posablie moves    \
0 to 1 that 0 to A | 
1 to 0             |
7 to A             |
6 to B             |
["0A","7A","6B"]   |
                   |
Moves              |
1 11311342...      |
7A                 |
                    \
Find posablie moves>/


```
long
```
Starting deck 
1h2h3h4h5h6h7h8h9h0hJhQhKh 
1d2d3d4d5d6d7d8d9d0dJdQdKd
1s2s3s4s5s6s7s8s9s0sJsQsKs
1c2c3c4c5c6c7c8c9c0cJcQcKc

...


```
