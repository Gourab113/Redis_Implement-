# Redis

# Description

set key value : Set the value in redis
get key : Gives the value from redis, value in string
del key : delete that key
flushall : remove all the keys

exists key : Check a key is present or not
keys pattern : get the keys
keys \* : get all the keys

expire key time : expire key after some time
ttl key : The time key-value pair exixts

// store an array
lpush key value : insert the item to the array at left
rpush key value : insert the item to the end of array
lpop key : remove left item
rpop key : remove right item
lrange key startIndex endIndex : print the array

// set : unique item
sadd key value : add item to a set, it item is unique
smembers key : get the values of set

//Hashes

hset key key value : add multiple key value pair inside a key
hget key key: get the key value
hgetall key : get all the key value pairs
hdel key key : delete the property
hexixts key key : if key is exixts
