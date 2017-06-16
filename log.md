# 100 Days Of Code - Log

### Day 0: June 5, 2017

**Today's Progress**: Setting up Otto's repository for the 100-day challenge.

**Thoughts:** Rewriting Otto's documentation in English will take a while, but it will probably be beneficial in the long run. Will start from scratch again. Unsure whether I should consider design and documentation "coding" per se, so I won't; I'll just get to the code and see what comes naturally.

**Link to work:** [Otto](https://github.com/NoctisLux/otto)

### Day 1: June 6, 2017

**Today's Progress:** Wrote the first few classes of Otto (Event, Task) and tests.

**Thoughts:** That was surprisingly easy. I ignore if getting to work was simpler than I expected thanks to the literal months of thought and notes I spent on this project, or if it's just better to just get to work for a project of that scale. Took roughly an hour plus a few minutes here and there to rewrite minor stuff.

**Link to work:** [Otto](https://github.com/NoctisLux/otto)

### Day 2: June 7, 2017

**Today's Progress:** Started working on Schedule's constructor (filling a timeline from a list of events), learned dateutil.rrule (for repeating events and tasks), started reading PEP 257 on docstring conventions. Rethinking Schedule.timeline to contain a list of single Occurrences, rather than pure Events (will take another day).

**Thoughts:** First obstacle: realizing that my python3-dateutil package was outdated and did not include rrule.replace (which would have been handy). Should remember this is always the case with Debian. Need some place to lock myself in to escape external interruptions; no such thing with a working connection (yet) alas. Already working with the heart of the program, I didn't think it would happen so fast, and I'm afraid to run into issues because of it, like branching into more and more complex problems from just this Schedule constructor.

**Link to work:** [Otto](https://github.com/NoctisLux/otto)

### Day 3: June 8, 2017

**Today's progress:** implemented the scheduling of an Event through its Occurrence(s). Added \_\_repr\_\_() and \_\_str\_\_() to Event, Task and Occurrence for easier testing. Read through and applied PEP8 recommendation.

**Thoughts:** So many PEP to read! Next up is PEP 257 on docstrings. What about annotations? Am guessing most of those recommendations have to do with third-party tools generating the documentation for me. Should I apply and use those?

**Link to work:** [Otto](https://github.com/NoctisLux/otto)

### Day 4: June 9, 2017

**Today's Progress:** Added plaintext docstrings.

**Thoughts:** Spent all day reading up on docstrings conventions and formats as well as Python annotations. It took a while, but I settled with plaintext docstring with a very bare format (actually based on an example from PEP257). Maybe I'll have to change to better stuff later on if I end up using a given tool for automatic documentation or type-checking, but I don't for now and plaintext comments are the easiest to migrate from. Kind of an unproductive day, but to stay consistent and readable, it had to be done earlier rather than later.

**Link to work:** [Otto](https://github.com/NoctisLux/otto)

### Day 5: June 10, 2017

**Today's Progress:** Added to Schedule a \_\_repr\_\_() and the bare bones of an \_\_str\_\_() methods.

**Thoughts:** Working with Python is such a pleasure, I hardly considered it work today. Might do some Free Code Camp exercises or maybe work on a more complex feature a bit.

**Link to work:** [Otto](https://github.com/NoctisLux/otto)

### Day 6: June 11, 2017

**Today's Progress:** Added get_free_time() to Schedule.

**Thoughts:** Starting to get into the functions that represent the core of the time management calculations. Starting to think about writing unit tests to ensure everything works perfectly before I get overwhelmed by the complexity of nested functions and all the possible sources of an unexpected bug.

**Link to work:** [Otto](https://github.com/NoctisLux/otto)

### Day 7: June 12, 2017

**Today's Progress:** Started getting familiar with the unittest module and wrote a couple basic unit tests for Events. Listed Exception for next test cases.

**Thoughts:** Many different unit testing modules exist for Python. The choice wasn't easy. Will probably implement the same tests with multiple frameworks to get familiar with each major one and decide on a favorite. Did not find many situations that would require raising special exceptions in the project so far. Wonder if I am missing any.

**Link to work:** [Otto](https://github.com/NoctisLux/otto)

### Day 8: June 15, 2017

**Today's Progress:** Over the past two days, researched good practices on exceptions in Python, listed the exceptions to expect from the four classes I have, listed tests to perform and implemented all tests for Event.

**Thoughts:** My routine got interrupted by a series of appointments and the installation of new hardware in the office, but I managed to squeeze some productivity here and there. Not enough to count towards the daily challenge in my opinion though. Now's the time to get back to it.

**Link to work:** [Otto](https://github.com/NoctisLux/otto)

### Day 9: June 16, 2017

**Today's Progress:** More tests laid out for Schedule.

**Thoughts:** Writing tests turns out to be more dull than I would have thought. It feels unsatisfying to write code that is designed to fail. As a result, progress has been slow. Will try to finish this the next few days.

**Link to work:** [Otto](https://github.com/NoctisLux/otto)