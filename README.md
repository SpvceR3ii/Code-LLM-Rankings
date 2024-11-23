# CoderLLMs
## Insight into which LLM's are the best for coding

Hey guys! I got bored today, and like the no-life I am, I decided to create a documentation for each coder LLM which is under 3b parameters!
This is really scuffed, and I honestly should've provided outputs too, but this was turned from a Discord Thread and I didn't have nitro to upload the outputs...

***PROMPT FOR EACH LLM***: "Make a Python script which asks "Agree to the Terms", and repeats it until the input given is "Yes""

### Now, let's get into it!

RANKINGS
---

**deepseek-coder:1.3b-instruct-q6_K**: Wouldn't recommend it. Generated code with excessively long comments, and required extra prompting to get anything out of it.

> **Rating**: 2.2 out of 5

**starcoder:3b**: Really bad. Didn't even make code after a lot of prompting. Hallucinated, repeated words, didn't follow instructions.

> **Rating**: 0 out of 5

**yi-coder:1.5b**: A really good model. Gave good responses for it's 1.5 billion parameters. It gave clear, consise and marked code.

> **Rating**: 4 out of 5

**qwen2.5-coder:3b**: Good code, absolutely smashed my expectations. Even added in an option for selecting "No", which simply stated "You need to accept the terms to use this application"

> **Rating**: 5 out of 5

**starcoder2:3b**: Sucks just as much as starcoder. Gives some helpful insight, but doesn't actually make code.

>**Rating**: 1 out of 5

**granite-code:3b**: It's *ok*. Doesn't do anything fancy. It added a "No" option, but didn't add in specific values for it so it was marked as non-existent and declined as an option.

> **Rating**: 2.5 out of 5

**granite3-dense:2b**: A lot better than granite-code. Produced code to my expectations, and didn't stray off task or do anything fancy. It did what I asked.

> **Rating**: 4 out of 5

**stable-code:3b**: It's a good model, but generated a weird tag that's apparently associated with Jupyter notebooks inside of the input's quotation marks.

> **Rating**: 3 out of 5

**opencoder:1.5b**: Produced a good code example, and didn't go off task. Documented it well, and even added in a "no" option.

> **Rating**: 5 out of 5

## Conclusion
I think Qwen2.5-Coder, OpenCoder, and Granite3-Dense are all great models. The rest are quite obsolete, and/or function incorrectly. Enjoy this half-assed forum which'll get a makeover in around 3 days...