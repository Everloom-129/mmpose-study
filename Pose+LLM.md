# Pose detection and its practice value to merge in LLM
Basically, mmpose seems to provide a good robust people bone structure generation
And the key question of using it is whether should I adopt it in my project. 

This question is basically based on performance consideration, my project should include only meaningful combination for improvement, instead of simple connection.

Pose can gather: the direction people is looking for
but I need to make sure what should be generate into text:
the people 0 is looking people 1,sidewalk 0?
the people 1 is looking people 2?

We should concentrate on LLM agent's receving ability
How should it learn more from the text?

What would it takes for him to do the COT?
- [ ] ask GPT4 what will happen after providing pose estimation
- [ ] config the openai api environment
