# CodepathWeek9

The honeypot I deployed was the Ubuntu - Dionaea with HTTP honeypot. I encountered no issues getting this honeypot to run. 

After running the honeypot for about 4 hours, I got the following results:

![alt text](https://github.com/mmw5hy/CodepathWeek9/blob/master/attack_stats.png)

The top ip attacker 199.111.226.204 was my machine that I ran the `npm` command from. The next top attacker ip was from China at 121.12.125.178. After that, the next most attacked from ip addresses were all from Russia. The most attacked port was 3306, then 23, then 5060, then 445, and lastly 3389. My `mhn-honeypot-1` was the honeypot that caught these attacks, no attack signatures were recorded, and no malware samples were found.

I have no unresolved questions regarding the data collected. I found that this lab was interesting, and I appreciated getting the experience using google cloud. 
