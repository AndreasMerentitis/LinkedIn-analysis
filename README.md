# LinkedIn data analysis

The goal is to visualize a person's LinkedIn network data in order to show the main patterns in their connections 
(companies and roles, etc). This is done using a treemap structure, as well as a networkx graph (in the latter
case after clustering on cosine similarities of the TFIDF vector representations of the company names). 

The example was tested using python 3.6 natively and 3.8 in the docker version. You can run the demo either 
directly (natively) or use repo2docker to configure and run in docker respectively.


```bash
# Example usage (natively): 
$ pip install -r requirements.txt
$ jupyter notebook 
```

```bash
# Example usage (in docker): 
$ sudo service docker restart
$ jupyter-repo2docker https://github.com/AndreasMerentitis/LinkedIn-analysis
```

![relative path 1](/Network_treemap.jpeg?raw=true "Network_treemap.jpeg")
![relative path 2](/Interactive_graph.jpeg?raw=true "Interactive_graph.jpeg")


# Extending and reusing the basic idea from these sources:
* https://medium.com/@tavish.gobindram/visualizing-my-linkedin-network-c4b232ab2ad0
* https://docs.bokeh.org/en/latest/docs/user_guide/graph.html



