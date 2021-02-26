# Dumb v Smart

-- Can Dumb Possibly Beat Smart?

## BACKGROUND

It is widely believe, smarter is always better. In many cases, the smart wins largely because it has more prior or advanced knowledge, which the dumb usually does't know, and also because the smart workes harder on fully utilizing the advanced knowledge.  In wireless communication and networking, the prior knowledge usually includes the information of next channel condition, the next transmission timing and transmission power of other coexiting users.  In literature, it has long been established that knowing prior knowledge is beneficial and even critical in achieving optimal performance in multiuser precoding, access probe design, advance multiuser receiver design, etc.  Especially, this is well demonstrated in comparison with simple and "dumb" traditional approaches.  

In this random access channel design project, I, however, want to show that due to many implementation limitations and considerations, the dumb may sometimes win also, even though it has the least prior knowledge (e.g., the tranmission power and timing) of others users.  


The very early beginning of this project started when I was working for LG Electronics Mobile Research on a project in 2005 for impproving the reverse link channel capcity of 3G/CDMA2000 mobile network. At that time after Hurrican
Katrine disaster, https://en.wikipedia.org/wiki/Hurricane_Katrina, the industry suddenly realized that the 3G ALOHA based reverse link design could hardly accommendate the simultaneous access requests by a large amount of users in    some emergent situations and crowd events.  However, besides the group-based prioritization and futher randmonization on random channel accesses, the indstry couldn't figure out better and feasible systematic changes, which may significantly mitigate the reverse-link access congestion issue. (Indeed, we had some group policy based randominzation scheme proposed and accepted into 3G/CDMA2000 standards at that time.)


Later in 2011 with the emerging of M2M or IoT devices and services, the industry predicted that there would be another acccess congestion challenge soon, providing millions or even billions of low-cost IoT devices to be deployed in the 3G/3.5G/4G mobile networks.  This time, I made another contribution to 3GPP2 with a completely different thinking.  Instead of further prioritizing and randomizing network accesses,  I proposed a kind of new access probe and reception design.  Instead of proposing smarter or more powerful access probes, I proposed dumbe, low rate and low power access probes.  The good news is, this contribution was also accepted by 3GPP2 after harmonzed with Qualcomm's framework contributions.  


## WHAT IS THE SMARTNESS DISCUSSED HERE?




The principle of the dumb access protocol suggested here can be used for improving random access capacity.  The targeted applications, for example, includes improving IoT network capacity.


