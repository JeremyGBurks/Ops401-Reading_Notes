## Ethical hacking: Log tampering 101

![log](https://user-images.githubusercontent.com/97761340/193438552-919009fd-4d59-4bf8-bedb-698b8b4ae67b.jpeg)

### Why this reading matters in relation to topics covered in class this week
We have been learning more about the different ways an attacker can gain access, escalate privileges, evade security defenses, moving laterally, and persisting.
If an attacker wants to be successful they need to wipe away any trace they were there; this is where log clearing comes in. We actually used Atomic Red Team
attack frameworks that were mapped to the Mitre Att&ck framework. We cleared Windows Event logs then used a SIEM tool (Splunk) to investigate if it was able to
send logs of this clearing, which it did!

***

### Explanation of topic via an analogy from work/personal life
Before sending a phone in you need to factory reset it. Clear logs that show you have been there and have recorded system actions. This was a difficult topic to 
think of an analogy because when you think about log clearing to cover tracks it really comes down to trying to hide evidence from doing something you don't
want someone else to see.


### Things I want to know more about:
The four-step process to covering your tracks--->
1. Disable auditing--I would like to know more about how this is done on different operating systems
2. Clearing logs 
3. Modifying logs- I like to know more about this and what type of trail it leaves, if any.
4. Erasing command history (Does Windows or Mac retain history the same as Linux? If so, can you erase the command history?)

***

### Sources cited
https://resources.infosecinstitute.com/topic/ethical-hacking-log-tampering-101/
