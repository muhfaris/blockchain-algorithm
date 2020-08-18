# blockchain-algorithm
What you will be able to do
- [x] Create your own blockchain
- [x] Understand how hashing works in maintaining integrity of the blockchain
- [x] See how new blocks get added
- [x] See how tiebreakers get resolved when multiple nodes generate blocks
- [x] View your blockchain in a web browser
- [x] Write new blocks
- [x] Get a foundational understanding of the blockchain so you can decide where your journey takes you from here!

## Example 
Get block :
```
## http://localhost:1111

[
 {
  "timestamp": "2020-08-18 09:08:50.505958418 +0700 WIB m=+0.001261688"
 },
 {
  "index": 1,
  "timestamp": "2020-08-18 09:09:01.810435769 +0700 WIB m=+11.305739048",
  "bpm": 3,
  "hash": "4a567f23d233d06953260d6b2dc5a905a0e8e99ad3f50da48a032be7e4376741"
 },
 {
  "index": 2,
  "timestamp": "2020-08-18 09:10:41.098273161 +0700 WIB m=+110.593576381",
  "bpm": 4,
  "hash": "53eaef389c1e96b0a16d7212d9a2f16d072bd71d8f0858dcad219566aa930b50",
  "prev_hash": "4a567f23d233d06953260d6b2dc5a905a0e8e99ad3f50da48a032be7e4376741"
 },
 {
  "index": 3,
  "timestamp": "2020-08-18 09:12:22.927523395 +0700 WIB m=+212.422826656",
  "bpm": 6,
  "hash": "6329df10a055a75170ad0fff66919e25a636bb63134b92475227ab2537706cd6",
  "prev_hash": "53eaef389c1e96b0a16d7212d9a2f16d072bd71d8f0858dcad219566aa930b50"
 }
]
```

Create blok :
```
## http://localhost:1111
{
    "bpm":6
}
```
