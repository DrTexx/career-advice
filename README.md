# career-advice
## Freelancing
**freelance = giving up security in exchange for cash**
- think: _what experience will this give me to do the next thing_
- if there's the opportunity for freelance work but it's something you can't show, don't take it. _(unless you're getting paid a lot)_
- Andrew actively forced himself to persue jobs where he would get experience for where the next opportunies would lie. For instance, taking on PHP jobs when he was very familiar with Ruby so that he could develop his skills for the future. Even if you've got years of experience in a language.
- "be fierce on what the outcome is of projects"

## Languages
### Python
... is a well and truly estabilished language (in the same way javascript is) (_note_: don't bother looking into Django, I missed the boat)

> these things go in cycles

> if you're planning on taking a job, think about how you would present it on a CV before you even take it.

## Finding work
### Recruiters
... use them to find jobs

> A lot of the freelance work I get is from people I know
 
> A lot of my work is around consulting people I know

> There are a bunch of specialist recruiters that will be within any given industry

#### Specialist recruiters
| Recruiter | Specialisation | Notes |
| ---       | ---            | ---   |
| TORII recruitment | Web-based | Company Andrew uses often
| S2M | Web-based | Located in South Yarra |
| OPUS | Web-based | - |
| HAYES | Web-based | Very high volume, _'hard to cut through'_ |

### Freelancer.com and alternatives
... Andrew doesn't bother using for finding staff

> "As someone trying to get something done at AESOP, I don't go to freelancer.com or something, I go to recruiters and tell them what skills it is I need."_
  
> "have a chat to a bunch of recruiters"

## Recruiters

## [???]
> Potentially reaching out to the big consultancies (more generally software)

> Massive employers also have intake programs (i.e. graduate programs).

### Web-based recruiters
- TORII recruitment (company Andrew uses) (web-based)
- S2M (south-yarra)
- OPUS
- HAYES (Very high volume though, they're hard to cut through)

### Software-based
- accenture
- deloitte
- pwc
### Huge employers
- Google
- REA Group (realestate.com.au, carsales.com, etc.)
- Envato
- Xero

## Minimum requirements
There's always ways around things like needed bachelors for graduate programs
acknowledge you don't have a required qualification if you haven't got it, even in your cover letter.
### Employers searching for junior devs
who
- looking for a reasonably smart brain that can be trained to do what you need them to do
- after someone who you can tell "I want you to write some python that does this" and have them not freak out on you.
- if you can demonstate aptitude seperately than a degree thar's the way you can potentially get involved in those programs
- don't be put off by what they say are the minimum requirements (a lot of it is about signaling)
- saying a bachelors degree doesn't necesarrily mean someone who knows how to make a program, but knows how to write code

bachelors courses don't lead to a good understand of how to use implementation

typically you need 4-5 developers of varying skill levels to support junior developers of a team
"until you reach that critical mass"


e.g. "I don't currently have [x], however I have done [x] and here's my github, yadda yadda"

"they want to get to your code as fast as they can"
- "if your CV has a link to github or bitbucket it's the first thing they're going to look at" (they'll go back and look at it later, but it's primary)


>I want to go to someone's github and go "fucking hell, this person is doing a lot of stuff"
>on github, the first thing they're going to look at is your contributions
>good to be able to see they're a member of the community
>make sure Volume2byDenver is somewhere to show

----> go and read up on gitflow (a github workflow) [!!!]

master should never ever ever ever ever break

-- look into Travis (a build test software)

having stuff like tests and coverage tests is really important to have on your repos
a lot of it is signalling how you operate and how you're willing to operate

having all green badges for your tests and things is like "fuck yeah, I'm giving them a call"

even just replying to yourself in issues and commits,
descriptive commits
"creating tickets for yourself"
(also helps you at a later stage)

self-note: try transitioning code comments and things into github commits and stuff

Over-testing is a waste of time + you've got to maintain it

It's always easier to start tests at the point you start writing code

> assuming you're writing tests retrospecitively, if you're already writing exception handlers, it's a really good place to put tests.

"graceful exception handling"

TESTING:
- test the surface of your application (e.g. user input, APIs, etc.)
- don't need to test the internals of the API

example:
 google maps for Auckland
 - giving it a name, does it return a list of ints?
 - does it return a specific expected int?

WHERE TO GET STARTED WITH TESTING:
"Test-Driven Development" (aka. TDD)
"the practice is you write the test before the code"
makes you think about what you're doing before you commit code to your codebase

"before you write code to solve a problem, you write a test to articulate the problem"

[!!!] "One of the big things with all software is to try and make the deterministic"
<EXAMPLE>
1. call update with arguments
2. it does some work
3. it returns a result

what if the function, for instance, changes something in the global scope.

"without fail, take this update function, it has an inital state, it has an output functuon (I can test that).

it gets murky when its a function using the given context is talking to something else outside it's scope


priority of
understanding your own code
others being able to understand your own code
the speed at which you can write the code
