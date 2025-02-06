<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

my-new-project
Building AI course project

AI Accident Investigation
Final project for the Building AI course

Summary
The operationalisation of AI/Machine Learning in transportation and other industries has grown faster than the maturity of testing and risk management. Current accident investigation techniques are based on understanding deterministic models and may be inadequate for understanding non-deterministic machine behaviour.

Background
The operationalisation of AI/Machine Learning in transportation and other industries has grown faster than the maturity of testing and risk management. Current accident investigation techniques are based on understanding deterministic models and may be inadequate for understanding non-deterministic machine behaviour.

This is how you make a list, if you need one:

problem 1 Need to understand how AI/Machine Learning was implemented.
problem 2 Need a structured process for personnel to follow to build a model of the function, purpose and developemt of the AI/Machine Learning.
problem 3 What is our understanding of how risk emerges in a learning system?
problem 4 How do we apply controls in a learning system to prevent unwanted learning, while not restricting performance improvement and adaptation.
How is it used?
The solution should encapsulate a process that could be employed to provide independence accident investigation findings and recommendations.

Data sources and AI methods
To develop a process would require input from the AI community / software and sensor developers to understand how to interogate the software to understand the strengths and weaknesses of it as a controller.

Challenges
Access to IP for vehicle software control systems.

What next?
Project would need input from vehicle control systems employing AI/Machine Learning

Images will make your README look nice!
Once you upload an image to your repository, you can link link to it like this (replace the URL with file path, if you've uploaded an image to Github.)
![Cat](https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg)

If you need to resize images, you have to use an HTML tag, like this:
<img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg" width="300">

This is how you create code examples:
```
def main():
   countries = ['Denmark', 'Finland', 'Iceland', 'Norway', 'Sweden']
   pop = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   fishers = [1891, 2652, 3800, 11611, 1757]

   totPop = sum(pop)
   totFish = sum(fishers)

   # write your solution here

   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%

main()
```
