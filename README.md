# Hassam Gani

I'm a computer science student at Columbia and a machine learning researcher at [DAPLab](https://daplab.cs.columbia.edu/), working on language models. I'm interested in them end to end, from tokenization and the transformer up to how they're trained and used as agents. Right now most of my time goes to reinforcement learning and multi-agent systems.

Before DAPLab, I worked on ML security at Columbia's Software Systems Lab. I also co-founded [MorningsideMunch](https://www.morningsidemunch.com/), a dining app used by more than 1,000 Columbia and Barnard students.

More at [hassamgani.com](https://hassamgani.com), or find me on [LinkedIn](https://www.linkedin.com/in/hassamgani/), [Twitter](https://x.com/HassamAbdulGani), or by [email](mailto:gani.hassamabdul@gmail.com).

## Research

At [DAPLab](https://daplab.cs.columbia.edu/), Columbia:

- **Debate, voting, or self-refinement?** When you can only afford so many LLM calls, is it better to have models vote, refine their own answers, or debate each other? This project tests a theory that predicts which one wins, across six models and six benchmarks.
- **Self-play for LLM reasoning.** Can a language model get better at reasoning by training on problems it makes up for itself, with no labeled data? The system started with math and now covers open-ended writing. Along the way, re-measuring R-Zero, a published self-play method, showed that most of its reported gains shrink to about one point.
- **Graph vs. SQL database agents.** Do LLM agents answer database questions better when the data is stored as a graph instead of SQL tables? On clinical records the graph agent came out slightly ahead, mostly because the SQL agent mishandled questions about relative dates. The project also found 626 correct answers that the benchmark's grader had marked wrong.

At Columbia's Software Systems Lab:

- **Malicious code in pickled models.** ML models are often shared as Python pickle files, which can run hidden code the moment they're loaded. [cpyAnalyzer](https://github.com/wunused/python-ast) catches these: its loading policies blocked every malicious model while still accepting 79.8% of benign ones.

## Projects

- [MorningsideMunch](https://www.morningsidemunch.com/): a dining app covering all 21 Columbia and Barnard dining halls. It reached 1,000+ users within a month of launch, over 30% of Columbia's dining-plan holders.
- [SmartSnake](https://github.com/HassamGani/SmartSnake): a reinforcement learning agent that teaches itself to play Snake. Within 100 games its score improves 733%. [Watch it train in your browser](https://hassamgani.com/projects/snake).
- [FaceGuard](https://github.com/HassamGani/FaceGuard): face authentication for macOS that learns its owner's face in seconds, without a GPU. If someone else wakes the Mac, it emails the owner photos and a short video of them.

I work mostly in Python and PyTorch, with Swift and TypeScript for apps.
