The bug was that num1 and num2 are strings and when added together, they are concatonated instead of their values added.
The fix is to convert string to int before adding them.

DevTools
1. citylots.json
2. part2.js
3. 11.1 MB
4. 92 ms
5. User Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/88.0.4324.104 Safari/537.36
7. Jan 26, 2021
8. fetch
9. fetchData()