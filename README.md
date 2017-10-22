
## 🤘 BlockSnobbery: GOLOS/STEEM blockchain redis-streamer. 

***

* **No block will be missed** Checkpoint in case of a pause
* **No intervals hell** there are no intervals such as silly 3000ms
* **Clean & Native Websockets** No libraries required such as golos-js || steemjs
* **Redis cache for fast synchronization**

***

### 💾 Install

You should already have installed nodejs.org & redis.io

* `git clone https://github.com/vikxx/BlockSnobbery`
* `cd BlockSnobbery`
* `npm install ws`
* `npm install redis`
* `node snob.js now`

***

Start from the specified block:
> node snob.js 1234565

Start with the newest block:
> node snob.js now                                          

Start with the Last remembered block:                          
> node snob.js       

***

Realtime block listener: `node snob.js now`


|Processed block num  | Age last ops |Current on Steem  | State  | Ops count  | Ops lenght  |   
|---|---|---|---|---|---|

![Capture.JPG](https://steemitimages.com/DQmee4VDMWHAqi3dKACkWGHMq63XP3ba6NAbj6DVJ9QV8Yt/Capture.JPG)

Processing Block History after pause: `node snob.js`

|Processed block | Age block |Current on Steem|State|Remain|Ops count| Ops lenght  |   
|---|---|---|---|---|---|---|

![Capture2.JPG](https://steemitimages.com/DQmbsDcqjFZQX9AQUj9ob8qJCtYDoSRNSAT7iZk4H2HvELP/Capture2.JPG)

