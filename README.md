when i am using esp32 by espress 2.0.14 it works fine and arduino i am using 





# p10displaywithprotocolesp32ueth
maine apna khud ka ek protocol banaya hai p10 display ke liye rs485 to ttl module ke sath. |C|1|4|1|28-0-#u#R|97| like this nand sir protocol
mai nand sir ke jaisa hi khud ka ek protocol banane ka try kar rha hu p10 display ke liye jisse ki mai chizo ko apne hisab se p10 display me jo kuch dikhana hai use display kara saku. 
|C|1|4|1|28-0-#u#R|58|   -  |start|address|4 means temporary or 8 means permanent data|x axis- y axis- #u means up direction arrow #R means color of display|data| which i want to display on the p10 display. so nand sir ne ye protocol banaya hai p10 display ke liye. ye bhut hi achha project hai ye hub75 rgb p10 display ke liye unhone banaya hai.

unhone hub 12 mono color wale display ke liye bhi protocol banaya hai. jisme hum 6 tiles tak ko ek hi controller se chala sakte hai. isme unhone kya kiya hai basically ki jaise man lo 6 tiles me hume kuch data display karana hai to hum 32*6 = 192 aa gya humare pass. so 192-32= 160 so mai jab coordinates ko set karunga to 28-0 ki jagah par mai  160-0 likhunga to jis side card laga hai uske opposite sides se data jana isme suru hota hai. aur starting me humne 32 minus kiya tha kyuki hum chahte hai ki last wale tiles ko hum apne data ko print karane ke liye bacha kar rakhte hai. jisse hi humara koi data us par print ho kar aa sake. 
