# Call For Own
20 points
>This site is another suspicious site you found in his Herbert's browser history.
>What is the message on CallForOwn?

## Solving it

When we go to the site we see this:

![Call for Own](https://raw.githubusercontent.com/DigiBrkr/csaw_hsf_qualifier_2017_CallForOwn_20/master/Call%20For%20Own.PNG)

To me  
`jtvw{l3tx0b3_e0_eph_o3l_vw3}`
looks like a flag that has been put through a substitution cipher.
First I tried running it through a rot 13 decoder since it's generally a relatively popular cipher for ctf's which turned up nothing useful.
Then I found a very cool tool called [quipqiup](https://quipqiup.com/) it's an automated cryptogram solver by a guy named Edwin Olson. I found it very helpful throughout the ctf. In this particular case I was able to use it to quickly solve this particular challenge.
I was relatively sure that `jtvw{l3tx0b3_e0_eph_o3l_vw3}` was a flag so in quipqiup I was able to make some basic assumptions i.e.
```
j = f
t = l
v = a
etc.
```
Quipqiup is by no means the most elegant solution to this problem however, it got the job done.   

`flag{w3lc0m3_t0_the_n3w_ag3}`
