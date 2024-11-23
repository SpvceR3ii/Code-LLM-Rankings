### Coding LLM Benchmarking  

**Hey Guys! I got bored today and decided to create a documentation on which coder LLMs are the best under 3B parameters. This is a half-assed attempt, but I hope it helps you understand their capabilities. Let's dive into the rankings below!**  

***PROMPT FOR EACH LLM***: "Make a Python script that asks 'Agree to the Terms' and repeats it until the input given is 'Yes'."  

---

**RANKINGS**  
---  

1. **Qwen2.5-Coder:3b**  
   - **Position**: **#1**  
   - **Why?** Absolutely smashed my expectations! The model generated good code and added an option for selecting "No," which simply stated, "You need to accept the terms to use this application."  
   - **Verdict**: The top choice if you want a no-nonsense, effective solution.  

2. **OpenCoder:1.5b**  
   - **Position**: **#2**  
   - **Why?** Produced a good code example, didn’t go off task, and documented it well. It even added a "No" option.  
   - **Verdict**: A rock-solid performer for concise and clean code generation.  

3. **Yi-Coder:1.5b**  
   - **Position**: **#3**  
   - **Why?** Delivered clear and concise code that stuck to the instructions without any weird tangents.  
   - **Verdict**: Great performance, though it didn’t go above and beyond.  

4. **Granite3-Dense:2b**  
   - **Position**: **#4**  
   - **Why?** Stayed on task and produced code to expectations. No frills, no mess.  
   - **Verdict**: A solid choice, even if it’s not particularly flashy.  
  
*Both Yi-Coder and Granite3-Dense are on the same level, but have been separated.*

5. **Stable-Code:3b**  
   - **Position**: **#5**  
   - **Why?** Generated functional code but included a weird tag that’s associated with Jupyter notebooks inside the input's quotation marks.  
   - **Verdict**: Decent, but needs refinement.  

6. **Granite-Code:3b**  
   - **Position**: **#6**  
   - **Why?** Added a "No" option but didn’t assign specific behavior to it, making it effectively useless.  
   - **Verdict**: Basic and functional but lacks depth.  

7. **DeepSeek-Coder:1.3b-Instruct-Q6_K**  
   - **Position**: **#7**  
   - **Why?** Generates excessively long comments and needs extra prompting to produce usable code.  
   - **Verdict**: Only consider if you're desperate or enjoy decoding messy outputs.  

8. **StarCoder2:3b**  
   - **Position**: **#8**  
   - **Why?** Provided some helpful insights but failed to generate any actual code.  
   - **Verdict**: A disappointing follow-up to its predecessor.  

9. **StarCoder:3b**  
   - **Position**: **#9**  
   - **Why?** Utterly failed. Didn’t generate code, hallucinated words, repeated phrases, and ignored instructions.  
   - **Verdict**: A straight-up trainwreck. Avoid at all costs.  

---

**Final Thoughts**  

If you’re looking for reliable coding LLMs, **Qwen2.5-Coder**, **OpenCoder**, and **Granite3-Dense** are the way to go. Models like StarCoder and DeepSeek-Coder, on the other hand, are essentially just *fancy paperweights*, and shouldn't be used whatsoever.  

*Shoutout to Qwen2.5-Coder for making this mess.*