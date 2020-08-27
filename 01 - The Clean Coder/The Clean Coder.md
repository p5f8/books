The Clean Coder  
A Code of Conduct for Professional Programmers  
Author: Robert C. Martin  
  
Chapter 01 - Clean Code
-----------------------

- Be Careful What You Ask For
  
  What would happen if you allowed a bug to slip through a module, and it cost your company $10,000 ?  
  The nonprofessional would shrug his shoulders, say "stuff happens", and start writing the next module.  
  The professional would write the company a check for $ 10,000! 
 
- Taking Responsability
  
  Always ship with tests.

- First, Do No Harm

  Drawing from the Hippocratic oath ?  
  What harm can a software developer do?
  
- Do no harm To Function

  As programmers, we want our software to work. As ours customers and employers.  
  We harm the function of our software when we create bugs.  
  Errors: It won’t ever get to zero, but it is your responsibility to get as close as possible to it.  
  
- QA Should Find Nothing

  It is unprofessional in the extreme to purposely send code that you know to be faulty to QA.  
  If QA or user find a bug, you should be determined to prevent it from happening again.

- You Must Know It Works

  TDD always.
  80% tests codes at least.
  
- Automated QA

  Any doubts?

- Do No Harm To Structure

  Software should be easy to change.  
  You should be able to make changes without exorbitant costs. Ever.  
  Merciless refactoring.  
  Programmers should treat software the way a sculptor treats clay - they continuously shape and mold it.  
  
- Work Ethic

  Your carrer is your responsability.  
  Work 40 hours, and study 20 hours. (Martin's Law)  
  Work 40 hours, and study 10 hours. (Pablo's Law) :-) (v1)
  Work 40 hours, and study 30 hours. (Pablo's Law) :-) (v2)
  
- Know Your Field

  Do you know what a Nassi-Schneiderman chart is? If not, why not?   
  Do you know the difference between a Mealy and a Moore state machine? You should.  
  Could you write a quicksort without looking it up?   
  Do you know what the term “Transform Analysis” means?  
  Could you perform a functional decomposition with Data Flow Diagrams?  
  What does the term “Tramp Data” mean?   
  Have you heard the term “Conascence”?  
  What is a Parnas Table?  
  
  Remember Santayana’s curse: “Those who cannot remember the past are condemned to repeat it.”  
  
  -- Design patterns. You ought to be able to describe all 24 patterns in the GOF book and have a working knowledge of many of the patterns in the POSA books.  
  -- Design principles. You should know the SOLID principles and have a good understanding of the component principles.  
  -- Methods. You should understand XP, Scrum, Lean, Kanban, Waterfall, Structured Analysis, and Structured Design.  
  -- Disciplines. You should practice TDD, Object-Oriented design, Structured Programming, Continuous Integration, and Pair Programming.  
  -- Artifacts: You should know how to use: UML, DFDs, Structure Charts, Petri Nets, State Transition Diagrams and Tables, flow charts, and decision tables.  
  
- Continuous Learning

- Practice
  
  Do a Kata or two every day!  
  
  Learn another language.

- Collaboration

  Work with other, but get away by yourself to work!  
  
- Mentoring


- Know Your Domain

- Identify With Your Employer / Customer

  Your employer’s problems are your problems.

- Humility

  However, a professional also knows that there will be times when he will fail, his risk calculations will be wrong, his abilities will fall short; he’ll look in the mirror and see an arrogant fool smiling back at him.  

  So when a professional finds himself the butt of a joke, he’ll be the first to laugh.  
  
  He will never ridicule others, but will accept ridicule when it is deserved and laugh it off when it’s not.  
  
  Howard’s advice: Laugh  


- Bibliography  

   Robert C. Martin, Principles, Patterns, and Practices of Agile Software Development, Upper Saddle River, NJ: Prentice Hall, 2002  
   

Chapter 02 - Saying No
----------------------
  
> "Do; or do not. There is no trying." - Yoda

- Professionals speak truth to power. Professionals have the courage to say no to their managers.  
  Aren't you supposed to do what your boss says? No. Not if you are a professional.  
  Slaves are not allowed to say no.  

- Adversarial Roles
  One of the reviewers of this book truly hated this chapter. He had built teams where there were no adversarial relationships; the teams worked together in harmony and without confrontation.  
  But I wonder if his teams are really as confrontation free as he supposes.  
  
- My own experience has been that the hard decisions are best made through the confrontation of adversarial roles.

- Managers are people with a job to do, and most managers know how to do that job pretty well. Part of that job is to pursue and defend their objectives as aggressively as they can.

- By the same token, programmers are also people with a job to do, and most of them know how to get that job done pretty well. If they are professionals they will pursue and defend their objectives as aggressively as they can.

- Say no at first! And then work out a solution that is mutually agreeable to both.

- What About The Why?
  Why it will take two weeks is just a detail.  
  Providing too much detail can be an invitation for micro-management.  

- High Stakes  
  "Firing me isn’t going to change the estimate, Charles"  
  
- Being a "Team Player"
  Never say trying, only say it I can do or I can not do.

- Trying
  Yoda: "There is no trying."  
  By promising to try you are saying that you have a new plan. What is that new plan?  
  
- Passive Aggression
  Happen when you let things happen. Interesting...
  Always say no at all the right times, and in all the right ways.

- The Cost Of Saying Yes
  Most of the time we want to say yes.  
  that HAS-A is better than IS-A
  Is good code impossible in modern software development?

- The Typical Project Proposal
  Enter the nefarious “3rd party.”
  Never truly be confident with the customer.
  
- Two Weeks to Completion
  The client will always extend the deadline.
  They will always want more features. 
  They will always want change—LATE. And here’s the formula for what to expect
  (# executives)^2 +
   2 * # new executives + 
   + # your kids
   = DAYS ADDED AT LAST MINUTE
   
- The Clients Never Care as Much as You Do
  
- Always take a look at the process.
  Are you coding too much?  
  Are unit tests and integrated tests compromised?
  Are you coding too fast?
  Are you sleeping well?

  1 or more than 1 yes, well, It's time so say 'No'.
  

Chapter 03 - Saying Yes
-----------------------

- Recognizing lack of commitment
Some words: need/should, hope/wish, let's,   

- How does commitment sounds like?
I will ... by .....  
You’re stating a fact about something YOU will do with a clear end time. Period.  

but you have to get through the next two stages: meaning it, and following through.


Chapter 04 - Coding
-------------------

- Being able to sense your errors is really important. Not just in typing, but in everything. 

- Having error-sense means that you very rapidly close the feedback loop and learn from your errors all the more quickly.  

- I’ve found that in each case that the key to mastery is confidence and error-sense.  

> Preparedness

1. First, your code must work. You must understand what problem you are solving and understand how to solve that problem. You must ensure that the code you write is a faithful representation of that solution.  
2. Your code must solve the problem set for you by the customer. Often the customer’s requirements do not actually solve the customer’s problems.  
3. Your code must fit well into the existing system.
4. Your code must be readable by other programmers.
5. If you are tired or distracted, do not code.

> 3 AM CODE

1. Don’t write code when you are tired.
2. Dedication and professionalism are more about discipline than hours.
3. I'm really do not like to work late at night.

> Worry Code

1. The trick is to learn how to shut down the background process, or at least reduce its priority so that it’s not a
continuous distraction.

> The Flow Zone

You must be there, in "The Zone", when you are practicing.  
Get out of "The Zone" when you are coding.  
When you get in "The Zone", you lost the big picture.  

> Music

I don't like to listen to music when I'm coding.

> Interruptions

Are you rude? hmm
Sometimes, however, it’s not the Zone that’s at fault, it’s just that you are trying to understand something complicated that requires concentration. There are several solutions to this.  

Solutions: Pair, TDD or BDD.

> Writer's Block

Are you getting enough sleep?  
Or are you felling worry, fear, and depression?  

> Creative Input

Creativity breeds creativity.  
Have you ever tried good old space opera?  

> Debugging Time

For some reason software developers don’t think of debugging time as coding time.  
A software developer who creates many bugs is acting unprofessionally.  


> Pacing Yourself

Software development is a marathon, not a sprint.  

> Know When To Walk Away

Creativity and intelligence are fleeting states of mind.  
When you are stuck, when you are tired, disengage for awhile. Give your creative subconscious a crack at the problem.  

> Driving Home

> The Shower

> Being Late

You will be late. It happens to the best of us.  
Regularly measure your progress against your goal, and come up with three fact-based end dates: best case, nominal case, and worst case.  
Do not incorporate hope into your estimates!  
Update these numbers daily.  

> Hope

Hope is the project killer.  
Hope destroys schedules and ruins reputations.
Make sure that the team and the stakeholders understand the situation, and don’t let up until there is a fall-back plan.  
Don’t let anyone else have hope.  

> Rushing

What if your manager insists that you “do what it takes”? Hold to your estimates!  
Tell your boss that you’ve already considered the options (because you have) and that the only way to improve the schedule is to reduce scope.  
Do not be tempted to rush.  
There is no way to rush.  
You can’t make yourself code faster.  
You can’t make yourself solve problems faster.  
If you try, you’ll just slow yourself down and make a mess that slows everyone else down, too.  
Deprive your boss, your team, and your stakeholders of hope.  

> Overtime

Therefore you should not agree to work overtime unless:
1. you can personally afford it, 
2. it is short term, two weeks or less, and (
3. your boss has a fall-back plan in case the overtime effort fails.

> False Delivery

> Define "DONE"

> Help

> Helping others

15-30 minutes a day, it's nice.

> Being Helped

Do not protect your turf.  
It is unprofessional to remain stuck when help is easily accessible.  

> Mentoring

Bibliography:

[Martin09]: Robert C. Martin, Clean Code, Upper Saddle River, NJ: Prentice Hall, 2009.  
[Martin03]: Robert C. Martin, Agile Software Development: Principles, Patterns, and Practices, Upper Saddle River, NJ: Prentice Hall, 2003.  




Stoped at page 110.  

