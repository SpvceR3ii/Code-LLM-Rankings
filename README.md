### Coding LLM Benchmarking

**Hey Guys! I got bored today and decided to create a documentation on which coder LLMs are the best under 3B parameters. This is a half-assed attempt, but I hope it helps you understand their capabilities. Let's dive into the rankings below!**

***PROMPT FOR EACH LLM***: "Make a Python script that asks 'Agree to the Terms' and repeats it until the input given is 'Yes'."

---

**RANKINGS**
---

1. **deepseek-coder:1.3b-instruct-q6_K**: **Rating**: 2.2 out of 5
   - **Recommendation**: Not recommended. The model generates excessively long comments, and requires extra prompting to produce any useful code.

2. **starcoder:3b**: **Rating**: 0 out of 5
   - **Recommendation**: Very bad. The model didn’t even generate code after numerous attempts. It hallucinated words, repeated phrases, and failed to follow instructions.

3. **yi-coder:1.5b**: **Rating**: 4 out of 5
   - **Recommendation**: A highly effective model with 1.5 billion parameters. It provided clear, concise, and documented code.

4. **qwen2.5-coder:3b**: **Rating**: 5 out of 5
   - **Recommendation**: Absolutely smashed my expectations! The model generated good code and added an option for selecting "No", which simply stated "You need to accept the terms to use this application."

5. **starcoder2:3b**: **Rating**: 1 out of 5
   - **Recommendation**: Sucks just as much as starcoder. It provided helpful insights but failed to generate actual code.

6. **granite-code:3b**: **Rating**: 2.5 out of 5
   - **Recommendation**: Ok, it didn’t do anything fancy. It added a "No" option but didn't provide specific values for it, making it marked as non-existent and declined as an option.

7. **granite3-dense:2b**: **Rating**: 4 out of 5
   - **Recommendation**: Better than granite-code. The model produced code to my expectations and didn’t stray off task or do anything fancy.

8. **stable-code:3b**: **Rating**: 3 out of 5
   - **Recommendation**: It's a good model, but it generated a weird tag that’s associated with Jupyter notebooks inside the input's quotation marks.

9. **opencoder:1.5b**: **Rating**: 5 out of 5
   - **Recommendation**: Produced a good code example and didn’t go off task. It documented it well and even added an "No" option.

---

## Conclusion

I think **Qwen2.5-Coder**, **OpenCoder**, and **Granite3-Dense** are great models. The rest, such as deepseek-coder, starcoder, and stable-code, are quite obsolete or function incorrectly. I hope this helps you make informed 
decisions about choosing a coder LLM for your coding projects!

*Yeah, much love to Qwen2.5-Coder for revamping this documentation...!*