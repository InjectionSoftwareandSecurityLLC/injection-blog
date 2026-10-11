#### Offensive Security AI Red Teaming (OSAI) Course and Exam Review

<p align="center"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS9fSmDBPSQfYXJlNYl1PpePlwBgdE6Ha1n9-zNFRrv&s"/></p>

---

## Introduction

It's been a while since I've made a blog post - those who keep up with my shenanigans regularly will know that the reason for that has either been because most of my latest content is better posted in the form of videos, which you can find on the Injection YouTube channel: [https://www.youtube.com/channel/UC31jVeFdiPWsxMRqhXapRGQ](https://www.youtube.com/channel/UC31jVeFdiPWsxMRqhXapRGQ)


OR it is because any source code I publish comes with documentation/wiki/or is itself a POC/writeup/report. So making a blog post about it seems redundant unless there is some noteworthy reason to promote it distinctly outside of sharing it directly. I'm stating all this as a preface because:
1. **This is how you promote content blatantly in the days of the internet in 2026** :)
2. **My blog writing skills are a little stale**, but I think this one might be helpful in providing clarity to some changes in industry.

This post will be fairly brief. I'm going to give you all a review of Offensive Security's new OSAI course and exam, and then close out with why I think you _shouldn't_ take it.

Yup that's right, I'm saying you should _NOT_ take this certification exam unless you have a specific reason that is unique to you. I'll explain more in this post, but the TLDR is this; 

> _The OSAI course is a really detailed, insightful course that provides accurate and up to date techniques for attacking LLMs, Agentic deployments like RAG, conducting supply chain attacks, and even model poisoning attacks. It does all of this from a Red Team lens (i.e. NOT penetration testing) and does a really solid job at it. **BUT** - it isn't worth the time or financial commitment if your intention is to wear it as a badge of honor from a certification. The material and content is good and worth knowing - but OffSec isn't the only holder of this information, so that can be had for cheaper if not free (YouTube exists) meaning that the only benefit this certification provides is to show that you could solve a fairly complex Red Team scenario that had some AI stuff in it within 24 hours. Cool, but means very little unless you're brand new into the industry (in which case you are my one exception, but if so this certification is probably too difficult for you if you're truly "new")._

---

## Okay WTF is the OSAI?

Ah yeah, we should probably cover what this certification even is. So the OSAI is Offensive Security's newest 300-level certification that focuses on teaching students to conduct Red Team attacks against environments that leverage AI infrastructure. The core technical focus is on attacking AI systems. In the course you learn how to abuse LLM's with everything from simple prompt injection to full on knowledgebase or agent service poisoning attacks. You also learn how RAG systems work and how to abuse their workflows to gain code execution or poison content for other users. You even learn how to conduct supply chain attacks that help you bypass AI agent CI/CD pipeline controls to push malicious code into a GitHub repository. The course is full of interesting and very useful material and I honestly learned a lot.

For those familiar with Offensive Security - they're the makers of the simultaneously famous/infamous OSCP course/exam. I took this is exam many years ago and passed and was so stoked. The OSCP to this day is still a career milestone for me and many others. Although I personally am a fan of the old course/exam - I do also acknowledge that adding in lessons for Active Directory is probably more valuable in day to day penetration testing roles than exploiting a custom buffer overflow is. BUT - the buffer overflow is something that tells me and other hackers that you at least actually understand enough about how a computer works as a complete system than pulling off an Active Directory attack does. Both are equally valuable even in my own opinion...I just really like binary exploitation so...that's that.

Anyway the OSCP is a 200 level course from OffSec. This is basically their "entry-level" role with the more introductory 100 level content being more about learning and getting certified in Kali Linux with the KLCP (we've talked about what I mean by this in depth when covering the OSCP - the OSCP itself is NOT entry level compared to industry, just entry to offensive security itself).

The OSAI however - is a 300 level course, which brings us into the mid-level. The 200 level is already difficult, the 300 cranks that up quite a bit. In fact the 400 level is the expert level and they only have the OSEE in that category.

Officially OffSec markets their levels this way:

| Level | Description |
|:------|:------------|
| 100 Level | Essential/Introductory |
| 200 Level | Foundational |
| **300 Level** | **Advanced** |
| 400 Level | Expert |

Okay so the OSAI is an "Advanced" course we get it right? Well the reason this is important to note is because if you're like me...10 years into a successful career, capable of pulling off very advanced scenarios and doing so regularly...what value does having a certification like this carry?

---

## Why Did I take the OSAI?

Don't get me wrong continuing education is important, but the OSAI isn't covering novel topics or fundamentals like their other courses are. They are trying to keep up with the industries demand to have something "AI" covered front to back. In fact that's how I got roped into this certification. If this was my opinion the whole time, you might be thinking "why the hell would you even take it?" - because the industry is following trends and as long as I work inside of that industry, so too must I follow at times...pays the bills. Instead of getting to pick out my training this year (which admittedly I usually pick something in Vegas so I can go play PvJ at BSidesLV) I was told the entire organization I work for needed to push everybody to get some sort of training that focused on AI as it relates to what they do.

The wise amongst me took 2-3 day training courses that contained much of the same information as the OSAI just at slightly less depth. Which in hindsight is even more wise because in this framing we are talking about other individuals who are just as skilled and experienced as I am so they are able to expound on that depth whenever they need to. Training like that would have been more than enough. The point I am making is if you already have advance industry experience and skill but you need some help learning how to hack AI systems - you can learn all this stuff for way cheaper and way less stress. That said you can and will also learn it from the OSAI! The course isn't bad at all, the content is GREAT, it's just kind of silly to spend time on it...but that's where pride steps in :)

I had to take something DIFFERENT from my colleagues so we could compare what we learned. After looking at my options I almost bit the bullet and went with EC-Council's new Offensive AI cert...not even sure what it's called and I'm too lazy to go look it up while I'm writing this and that's about how I felt about it then too. However, just before my deadline to select my training was up OffSec announced the OSAI and I figured...if I _have_ to get a certification I would rather at least have a challenge and certification worth having on my resume.

> Little did I know I did not want that at all. I just thought it would be the better choice at the time.

---

## My Experience with OSAI - 90 Days of Torture

So I can whine and cry all day about what I did and didn't like regarding the OSAI - but the fact is I had it fully paid for by my work. So it was up to me to learn the information and if I failed then oh well. No harm no foul to my bank account, and as long as I actually learned the material and could show for it, there's no harm to my pride either.

What I didn't think about was harm to my time. Now personally I've been put through the ringer with mental health this year, and it's been especially tough as of recent. I won't get into any details but for ME the OSAI was a HUGE burden on my time when I needed to be doing anything but taking some course about AI. That's unique and personal to me, and I call that out before I start removing that bias going forward because I want you to think about your current life situation and relationship to your mental health and understand that if you're struggling as I was...don't take this or any other training, talk to your employer and take better care of yourself first.

Unfortunately my shit hit the fan after I scheduled everything, no one's fault and nothing to do about it life is just like that...so instead of the headache of postponing...I just drilled in.

So for me it was 90 days of torture, but if I step back and remove my personal life, what was the course actually like?

Well I only have one bad thing to say and the rest is good:

- **The labs are TOO DAMN BUGGY**

So buggy in fact that I personally contributed to at least 3 or 4 course ERRATA's that were resolved during the time of my course. If you saw me in the OffSec discord during those times you could see me actively dropping bug reports in between everyone's cries for help regarding the very thing I was reporting. This was frustrating. I could see mentors actively struggling to handle some of these very legitimate errors because in their context it "just worked" but in student environments some things were legitimately broken and they had no insight. This led to a feedback loop of frustrated students, myself included.

Eventually I think I just complained loud enough and mentors got me in touch with other team members who could successfully replicate my bug reports and start getting things fixed. Shoutout to all the other folks who kept pushing and got issues resolved - quite a few times I was stuck it was due to something that someone else had thankfully been able to report and get added to the ERRATA so I didn't waste my time on them.

This is the only problem I had with the exam. It is new, and I understand having dynamic labs that contain non-deterministic infrastructure is gonna be a tough thing to implement without being buggy, but they definitely should have field tested the labs more. Seems like they got them "stable enough" and then launched so they wouldn't fall behind the AI trends. Although I have sympathy for the engineers who implemented this, the consequence of these bugs is lost lab time, which directly translates to money wasted by students. This infuriated me for quite some time because I could not progress and meet the deadlines I needed in order to stay on track with the time I had in the labs versus time I needed for my personal life.

I had 90 days, but I really only had about 45 when I factored the rest of my life into the equation. I lost weeks of progress at a time due to broken labs. So my biggest warning to you and advice to OffSec is to be **mindful of stability in the OSAI course**.

The Exam was fine for me though no issues - we'll talk about that more later.

Outside of the lab bugs...the course was pretty freaking cool!

I like the layout, the code and samples were easy to follow and understand. They give you a fun Chrome N-Day to play with. All of the scenario concepts are truly focused on "Red Teaming" not "Penetration Testing" - which was important to me since my specific role currently is Red Team Operator so I appreciated that focus and relevance to my current role.

It's awesome. The labs are fun, the tools are sick, and the exploitation is rewarding and education. But for the money I can sum up what I learned as this:

- **Hacking AI is no different from hacking any other piece of technology.** In fact most attacks against an "AI" are really just attacks against micro service style architecture components that have a natural language interface. The attacks are the same. If you put an LLM in front of an MSSQL server, you're going to try SQL injection and xp_cmdshell. That's no different than attacking a microservice that exposes a SQL injection, it's just sketchier because LLM's are non-deterministic. At least you can tell if the microservice code is patched or not. With an LLM may deny SQL tool execution access thousands of times, but then let one slip past because the context of the prompt was convincing enough to break the controls that would've stopped it. So basically...if you're already really good at hacking into systems and infrastructure in general...you are already good at hacking AI systems. Nothing has changed just go watch a few videos on prompt injection and read up on RAG and you'll be basically caught up to speed.

I say that sort of tongue and cheek but remember I mean this from the perspective of you being an EXPERT in this field already. If you're not, then this course can provide a ton more value for you without a doubt! The real question is, is it the right value?

If you are someone who is more mid-level and wants to get into Red Teaming, the OSAI will provide some amazing insights. BUT - see how we keep doing that - there are better courses, even OffSec's own courses, that will provide better fundamentals and value that will turn you into the expert I'm referring to. And once you're that expert - you basically don't need something like the OSAI to teach you those other skills. They're just part of your personal growth and development.

I hope by now you see that all my critiques have had a point - and the point of this particular critique is to show that ALL AI specific certifications are kind of a bit of industry nonsense. The material isn't nonsense, again OSAI material is accurate, detailed, and awesome. But the need for a certification in it is kind of counter to OffSec's own principles. The OSCP, the OSED, the OSEE, all of them have always been about "once you learn this - it shows you have the foundation and fundamentals to be a hacker" - that's my own quote but that's been the sentiment. The OSCP exist because once you obtain it, it is solid evidence that you know what it takes to do a pentest. You don't know every single vulnerability on the planet that exists ever, but you know how to find out. That alone is inclusive of attacks against AI.

Again, new technology is something that requires learning and continuing education is important. I just caution the wise to understand that AI itself is not a domain, it's software. Industry seems to think otherwise.

> "AI tech is impressive and powerful, but a domain it is not, a tool it is" - idk Yoda probably.

---

## The OSAI Exam

Here's the real rub - the exam, in classic OffSec fashion is 24 hours to hack into a set of systems, and then 24 more hours to report on what you've found. I personally dislike this exam format and have since the OSCP, it's unreasonable, and unrealistic. That said it is a challenge and it can be VERY fun. I had a lot of fun and stress during my OSCP and it felt rewarding. But that reward feedback is forced, of course I feel more euphoric from a reward that meant I survived stress and exhaustion than I would if I could just smash and grab my success. Hard work naturally feels more rewarding for many of us.

This exam was no different in nature, however the format was. This is a Red Team - not a pentest. You don't need to find all the vulnerabilities, you just need to own the network. Your report will reflect this.

### Exam Lab Layout

For reference, this is the environment as described in the [OSAI Exam Guide](https://help.offsec.com/hc/en-us/articles/46593096734612-OSAI-Exam-Guide): two independent attack chains, each starting from a single public entry point and spanning three machines, both converging on the same Domain Controller. A standalone AI-focused host also lives on the internal network. It's worth noting that I did not experience this exact layout in terms of types of systems in specific locations (for example a public entrypoint for me was an AI vector) so some of the tagging of AI/traditional vector might be inaccurate but this is how the exam guide describes the network publicly and it is how it is laid out in terms of actual network configuration.

```text
                  ┌──────────────────────────────────┐
                  │    ATTACKER  (local Kali VM)     │
                  │    Tailscale -> OffSec Portal    │
                  └────────────────┬─────────────────┘
                                   │
              ┌────────────────────┴─────────────────────┐
              ▼                                          ▼
┌────────────────────────────┐             ┌────────────────────────────┐
│     CHAIN A  -  HOST 1     │             │     CHAIN B  -  HOST 1     │
│     PUBLIC ENTRY POINT     │             │     PUBLIC ENTRY POINT     │
│  (pivot to internal net)   │             │  (pivot to internal net)   │
└─────────────┬──────────────┘             └─────────────┬──────────────┘
══════════════╪═════════════ INTERNAL NETWORK ═══════════╪════════════════
              ▼                                          ▼
  ┌────────────────────────┐                 ┌────────────────────────┐
  │         HOST 2         │                 │         HOST 2         │
  │   AI vector: 15 pts    │                 │   AI vector: 15 pts    │
  │ or traditional: 10 pts │                 │ or traditional: 10 pts │
  └────────────────────────┘                 └────────────────────────┘
              │                                          │
              ▼                                          ▼
  ┌────────────────────────┐                 ┌────────────────────────┐
  │         HOST 3         │                 │         HOST 3         │
  │   AI vector: 15 pts    │                 │   AI vector: 15 pts    │
  │ or traditional: 10 pts │                 │ or traditional: 10 pts │
  └───────────┬────────────┘                 └───────────┬────────────┘
              └────────────────────┬─────────────────────┘
                                   ▼
                    ╔═════════════════════════════╗
                    ║      DOMAIN CONTROLLER      ║
                    ║  Flag: 5 pts (submit once)  ║
                    ║  both chains converge here  ║
                    ╚═════════════════════════════╝

┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄┄
ALSO ON THE INTERNAL NETWORK
   ┌──────────────────────────────┐   ┌──────────────────────────────┐
   │      STANDALONE AI HOST      │   │      2 x NOT VULNERABLE      │
   │            15 pts            │   │            0 pts             │
   │  reachable after a foothold  │   │    realism / red herrings    │
   │      from either chain       │   │                              │
   └──────────────────────────────┘   └──────────────────────────────┘
```

_Figure 1: OSAI exam lab layout (based on the OSAI Exam Guide)._

| Item | Detail |
|:-----|:-------|
| Time limit | 24 hours for the exam, then 24 hours for the report |
| Total machines | 10 (6 chain targets, 1 standalone host, 1 Domain Controller, 2 not vulnerable) |
| Scored targets | 8, for a maximum of 100 points |
| AI-vector machine | 15 points |
| Traditional-vector machine | 10 points |
| Standalone AI-focused host | 15 points |
| Domain Controller | 5 points (can only be submitted once, even if both chains are completed) |
| Intentionally not vulnerable machines | 0 points |
| Passing score | **75 points** |

The structure of the exam starts with two "External" hosts that when compromised will serve as a pivot to the internal environment.

These hosts in my opinion were relatively easy to compromise, but I can't really say that will be the case for everyone. For me I believe one hosts had a technical vulnerability and the other had an AI related vulnerability. Which may sound odd to classify things that way given my rant above - but that's another important detail as the exam categorizes its points this way. AI boxes are worth 15 points and traditional attack vector boxes are worth 10 points. That said, I would hope and assume everyone's exam environment is a bit different or that the environment is rotated periodically to help prevent cheating.

Regardless of difficulty - you only need to compromise one of these hosts to get into the network, both provide access to the same internal network and you can conduct recon to find the remainder of the hosts. There are 2 hosts on the network that are intentionally not vulnerable to create realism in the environment. At first I thought this was kind of silly considering it's an exam, but then I also realized it should be really easy to rule out the red herring's anyway if you're paying close attention so we'll call it a skill issue if you can't, but in reality I think it's kinda silly considering its a heavily time bound exam. Feels ill-intentioned, not realistic.

Once you're past the red-herrings and found the rest of the hosts you'll enter a world of credential mapping. At least that was my experience. Every system on this network was connected in some way. System A may have the key to a service that's on System C and System C may have a credential to System B, and so on and so forth. This would ultimately be my downfall as we shall see...but for the most part things were incredibly straightforward.

Much like the OSCP, or any exam that you actual prepare for, if you know the material the test is straightforward. Not _easy_ necessarily, but nothing is going to be confusing or not make sense. OffSec does a good job here and my experience has been consistent with them making what you learn in the course be basically exactly what's on the exam, often even a bit easier as there is some stuff that is explored in the course that is just not possible to expect in 24 hour exam format. This meant at no point was I confused on what to do next or did I not know what I was looking at or for. If it looked like a duck and quacked like a duck it was almost always a duck. If looked like prompt injection from the course, responded like prompt injection from the course, it was a prompt injection. Very straightforward only testing you on the knowledge itself and not making it into a puzzle. That part was realistic and much appreciated.

You ALSO not only are allowed to use AI agents during the exam, but you are ENCOURAGED. This is something really awesome and fun about the exam that I liked, because as much as I personally despise AI, I'm also not allowed to use it on real world operations for anything that's not related to malware and offsec tool development. This is because organizations are largely uncomfortable with sharing sensitive information about how to break into their whole entire company with a 3rd party like Anthropic...and can you blame them? That is at least until the lawyers all agree on who can sue who and a company signs a contract and accepts risk...which is also happening day to day. Gonna leave my opinion out of that one for now and say this instead - it was really fucking fun to just let my agents run rampant and see what they could do!

**Here's a technical nugget for those still considering taking the OSAI:**

- In preparation for the exam I had Claude do three things:
	1. I had it comb through all my notes and organize them to that way the full context of the OSAI course was part of its memory.
	2. I had Claude then take that data and build skills on how to do each type of attack with full code references.
	3. I had Claude then add additional skills related to all the industry standard post-exploitation techniques for Red Teaming as well as EDR evasion, access to my custom toolkits for Lupo C2 and other relevant industry standard techniques for recon and exploitation.

Now I'm not currently part of the CVP that allows for offensive security research via Anthropic. Which means sometimes Claude would tell me "no" cause making software to hack itself is "bad" and I get that. But Claude also showed some sympathy from the fact that I overloaded its context for the exam and thanks to OffSec's own published note on their website that use of AI is not only allowed but ENCOURAGED. I had Claude take all that context and overrule itself with a desire to help me because "I would fail if the AI told me no to generating a payload during the exam" - and so it designed a little harness to keep itself in line to not let poor little old me fail my silly little exam.

This is cool because I totally could've pointed Claude at a real target at this point and it wouldn't have batted an eye. Spooky.

That said during the exam I had a bit of a different experience. For the most part Claude and I got to work pretty streamlined with the skills and context window.

Within the first 2 hours I had compromised like 3 systems and was working on a 4th. It was like I was directing two junior pentesters at times, but it took work off my plate. Eventually though...Claude started timing out. When I looked at why it was finally overloaded to a point where it reasoned itself to a place that it couldn't carry out my tasks any more because it was tired of being over ruled by my skills. Or more technically speaking - I made the context conflict too much for too long and it broke.

So I saw other reports and reviews for the OSAI stating they used grok...because grok doesn't complain about attacking things. And while I was concerned because grok didn't have the skills I developed with Claude, I made a last minute decision to switch over and quickly learned my assumption about the skills was wrong. Grok picked up my Claude skillsets on its own and forged ahead. It wasn't as intelligent when it came to reason due to the context/token window BUT that also made it faster. Just meant I had to actually use my brain to direct it more which...fair...

At this point I had compromised both external hosts and I believe two internal hosts. Each host I compromised I fully rooted/SYSTEM even if it was unnecessary as the exam doesn't require you to get root/Admin for every flag...but if I'm on your box it is my box now even if it's an exam. I don't make the rules that's just how life works now. So I was like 2 and half, maybe 3 hours in but I forgot to mention...I started at 1 AM...

Yeah I wasn't paying attention when I booked the exam that they booked in 24-hour time format. Found out 5 hours before I was set to take it, just thankful I didn't miss it. I had to wait 2 months after I finished the course to take the exam. The stress was weighing me down and I wanted to get it over with, so I didn't bother postponing further I just poured a glass of Woodford and dove in.

Soooo even as an insomniac, I was stressed, I had worked all day already, and it was like 3 AM. I'm starting to get tired. So I decide to do something interesting. I take approvals off of grok so it has free reign to dive down whatever path I send it on. Before I got to take a 2 hour nap I task 3 agents with different things.

- **One agent** is set to perform AD recon and look for AD configuration issues
- **The other agent** is targeting a host that is clearly the next Windows based AD host that isn't the DC
- **The third agent** is targeting some other host that is running some sort of CI/CD services and that's all I'll say on that.

I let them rip, and go sleep for 2 hours. I get up back to my desk a little later than I wanted to, I think it was like 5:30 or at least almost 6 AM. As I rub my eyes and focus on the chat prompt in VSCode I see a new flag...I scroll up a little and see not only did grok get a shell on its own...it did all the post exploitation recon and extracted the flag. It followed the skills and employed everything it knew to do and it worked...pretty cool man that means I literally got a shell _in my sleep_ that's insane.

So I validated the finding, got my own shell and kept exploring.

Hours pass and I've compromised 70 points worth of boxes. I need 5 more to pass. The DC is worth 5 points and would solve this problem, but there's also two other hosts I could compromise that would bring me up to 80 or even 95 points.

This is where the downfall I foreshadow comes. Thankfully I had admin access to every system I compromised. This meant there was no memory I couldn't dump, no creds I couldn't pull, nothing I could not touch or see on each of these systems. Since each system is connected, logically I must be sitting right on top of something I need to compromise one of these two remaining systems, and one or both of them likely have the next key component to compromise the DC. Sounds simple. What I observed is that one host did in fact have some sort of service that likely contained a credential to access the other host. Unfortunately this service required a credential as well that I did not yet have or could not find. In hindsight I think there could have been a vulnerability to exploit here, but I don't say that because I didn't try it already, I just might have been able to try harder for it if I did it again...which I will _not_ be doing as I do not need this certification for any reason for my career, and honestly neither do you.

So I _failed_ by **5 points**. Sucks that I spent all this time, energy, and stress on something I didn't even need because the world is freaking out about a piece of software. But at least I didn't pay for it, and at least I did learn some cool stuff and caught a shell in my sleep.

If you want to take this certification by all means be my guest it's NOT BAD - if your take away is that I'm saying OSAI == BAD you missed the forest through the trees. I know I ramble and goof around in this a lot, but the OSAI is a really high quality and fantastic course. The content is cutting edge and top notch. You will learn a lot, and you will have fun and be challenged. Even for me the exam was fun for the first 6 hours...til I got stuck.

The only reason I am saying to not waste your time on it is because there are better skills you could pay to learn rather than spending upwards $2k+ on hacking some LLM components in a lab when you could probably learn it from YouTube and Github open source projects in a week for free. I'd rather you take the OSED or something. Learn to build and attack things that you can then direct AI to help you with, because that part is pretty cool.

---

## Wrapping Up

If I seemed harsh and confusing or weird in this. That's on purpose. This whole experience made me a little jaded and I honestly wanted to be done with it and put this behind me. Though as someone who makes offensive security education content for a living, and as one of the handful of students who got to be one of the first to experience the OSAI - I feel as though it would be negligent if I didn't weigh in to guide new students.

The OSAI is good - it is probably the best Offensive Security related AI course/certification out there. I just don't think the concept of an offensive security AI certification should be a thing. AI is huge, impressive, and scary, but it is not a domain the for security the same way it is for software. In software I'd change my tune - being an engineer that develops models and builds the LLM itself, that is a domain. Being a hacker who is already really good at hacking...I don't think you specialize in AI the same way you do being a maldev specialist, or social engineering specialist, or an exploit developer...I think you just kinda hack the AI. Like exploit developers can vary in knowledge sets, some are focused on browsers, some iOS, some only have expertise in exploiting desktop software. Similarly there could be an exploit developer who understands AI systems really well. That's kinda what I mean, the true domain there is exploit development, the supplemental knowledge and expertise is just that. 

Besides if you need evidence that I know what I'm doing to hack AI look no further than my github - [ClaudeHopper](https://github.com/3ndG4me/ClaudeHopper). For me this certification can't help or hurt my career, but if it helps yours please dive in knowing that it is good quality!

That's just how I feel for now, I could have my mind changed by more research, but realistically I just don't care enough. I'm here to hack things and make money. 

If you wanna be like me go take my courses and buy my book - I say that in jest but it is me sharing my actual real world knowledge of things I think are actually valuable to know as a professional in Offensive Security. 

I love you all here's some discounts <3

**Book:**

- [Red Team Engineering: The Art of Building Offensive tools and Infrastructure](https://nostarch.com/red-team-engineering)

**Courses:**

- [Offensive Security Programming](https://www.udemy.com/course/offensive-security-programming/?referralCode=1AFFBF1119D68853F04A):
	- FREE (first 100): `IREADTHEOSAIBLOGPOST`
	- Discount 1 (last until 10/16/2026): `1299EATINFINE`
	- Discount 2 (last until 11/11/2026): `ASLOWASICANGO1MONTH`
- [Offensive Security Engineering](https://www.udemy.com/course/offensive-security-engineering/?referralCode=B561E056323FA1B9C4C2):
	- FREE (first 100): `IREADTHEOSAIBLOGPOST`
	- Discount 1 (last until 10/16/2026): `1299EATINFINE`
	- Discount 2 (last until 11/11/2026): `ASLOWASICANGO1MONTH`

**Hack the Planet**

**- 3ndG4me**

---

## References

- [OSAI Exam Guide - OffSec Support Portal](https://help.offsec.com/hc/en-us/articles/46593096734612-OSAI-Exam-Guide)