![Teaser](https://user-images.githubusercontent.com/94784611/170231686-6433104d-4ce2-43d5-9bb7-5461ad25f6a8.jpg)
_Andreas Panayiotou, Theodoros Kyriakou,_
<a href="https://marilenalemonari.github.io/" style="color: black; text-decoration: none;text-decoration-style: none;">_Marilena Lemonari_</a>,
<a href="http://www.cs.ucy.ac.cy/~yiorgos/" style="color: black; text-decoration: none;text-decoration-style: none;">_Yiorgos Chrysanthou_</a>,
<a href="https://totis77.github.io/" style="color: black; text-decoration: none;text-decoration-style: none;">_Panayiotis Charalambous_</a>.
_2022. CCP: Configurable Crowd Profiles. In Special Interest Group on Computer Graphics and Interactive Techniques Conference Proceedings (SIGGRAPH ’22 Conference  Proceedings), August 7–11, 2022, Vancouver, BC, Canada. ACM, New York, NY, USA, 10 pages._ [doi](https://doi.org/10.1145/3528233.3530712)

### Abstract:
Diversity among agents' behaviors and heterogeneity in virtual crowds in general, is an important aspect of crowd simulation as it is crucial to the perceived realism and plausibility of the resulting simulations.  Heterogeneous crowds constitute the pillar in creating numerous real-life scenarios such as museum exhibitions, which require variety in agent behaviors, from basic collision avoidance to more complex interactions both among agents and with environmental features. Most of the existing systems optimize for specific behaviors such as goal seeking, and neglect to take into account other behaviors and how these interact together to form diverse agent profiles.In this paper, we present a RL-based framework for learning multiple agent behaviors concurrently. We optimize the agent policy by varying the importance of the selected behaviors (goal seeking, collision avoidance, interaction with environment, and grouping) while training; essentially we have a reward function that changes dynamically during training. The importance of each separate sub-behavior is added as input to the policy, resulting in the development of a single model capable of capturing as well as enabling dynamic run-time manipulation of agent profiles; thus allowing configurable profiles. Through a series of experiments, we verify that our system provides users with the ability to design virtual scenes; control and mix agent behaviors thus creating personality profiles, and assign different profiles to groups of agents. Moreover, we demonstrate that interestingly the proposed model generalizes to situations not seen in the training data such as a) crowds with higher density, b) behavior weights that are outside the training intervals and c) to scenes with more intricate environment layouts.

<!---
<img src="https://user-images.githubusercontent.com/94784611/170267247-57bd33e3-7a24-433a-96be-ccdc246857ab.png" width="100" height="100" />
<img src="https://user-images.githubusercontent.com/94784611/170267225-8aeb314d-1739-4e25-8f90-2be8f0b6931b.png" width="100" height="100" />
<img src="https://user-images.githubusercontent.com/94784611/170267262-6eb88fec-2b60-486a-9eb8-b28570e3829b.jpg" width="100" height="100" />
--->

### Materials:
<img src="https://user-images.githubusercontent.com/94784611/170232148-224a3d29-5b06-4116-a323-8d5aecf2326f.png" width="20" height="20" /> [Video](https://www.youtube.com/watch?v=k5SAOnisBas)  
<img src="https://user-images.githubusercontent.com/94784611/170232148-224a3d29-5b06-4116-a323-8d5aecf2326f.png" width="20" height="20" /> [Fast Forward](https://www.youtube.com/watch?v=VkHZQYRP0w4&ab_channel=AndreasPanayiotou)\
<img src="https://user-images.githubusercontent.com/94784611/170233045-f2d31fd8-15d7-402c-a522-121523110928.png" width="20" height="20" /> [Code/Data/Trained Policies](https://github.com/veupnea/CCP)

### News:
- [CYENS blog](https://www.cyens.org.cy/en-gb/media/blog/may-2022/new-learning-based-method-to-model-crowd-behaviour/?page=7)
