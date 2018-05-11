# rl-study-notes
https://www.coursera.org/learn/practical-rl/
## Reinforement learing v.s. all
https://www.coursera.org/learn/practical-rl/lecture/KH2m3/reinforcement-learning-vs-all
### Interactive Transcript
Now, let's go a quick recap on how reinforcement learning compares to other demands machine learning. 

In supervised learning, you generally assume that you have a data set where you record not only observations but also 
the optimal answer that some kind of expert gave you.
And your main task is to get as close as possible to the opinion of this expert. 
Of course this means that you need this expertise to gather the data in the first place and if you don't have, you're more or less screwed. 

It is also very important to supervise learning can usually assumed that 
your training points are independent of one another. 
And this basically helps you a great deal if you apply say a stochastic gradient descent where you want to sample the data. 

Reinforcement learning however lacks all those assumptions. 
You have this, first you don't have a dataset, as you have already noticed. 
Instead, you have some kind of system from which you can sample data, but you don't get the reference answers, 
so there is no expert telling you what to do. 
Instead, you can try actions by yourself and there is some kind of critique that assigns you positive or negative feedback. 

In case of one advertisement, this feedback was denoted as basically the money you get for the clicks and
basically this implies that whatever algorithm you use for enforcement learning, 
you have to take care of exploring all the possible options, lest your risk to never try the optimal action and never learn it. 

The other problem with this reinforcement learning formulation is that your agents, your well, decision maker, 
basically affects his own observations. 
So whenever you, for example, whenever you try to ride the bicycle, 
if you always turn left on the first turn, 
you will never get data points where you ride on the part of the road which is on the right turn. 

Basically, you have to be very careful to explore the state space as well, otherwise, 
you risk misinterpretation there and failing to grasp the entirety of your problem. 


The other domains like unsupervised learning, also differ from reinforcement learning a great deal. 
Unsupervised learning tries to, it doesn't have expert as well, but it tries to do a different thing. 
Instead of trying to be an optimal strategy, it seemed to try to describe the data, 
find some underlying structure and this is very different from trying to find a strategy 
because sometimes it's much easier to ride the bicycle than to understand the structure of it, 
especially when it comes to not the bicycle but say a computer. 

Now finally, it's important to remember that although there are those kind of features and bullet points, 
there are no hard decision boundaries of what's unsupervised learning, 
what's supervised learning, what's reinforcement learning. 

Instead, if you're trying to solve any particular practical problem, 
you'll probably find yourself using it in some combination of supervised learning, 
inside of reinforcement learning, and unsupervised learning as a helper maybe. 
But reinforcement learning is more or less the most general area 
that can be treated as kind of the superset of full supervised non-supervised learning here.
