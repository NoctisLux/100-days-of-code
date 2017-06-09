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