# LinkedIn Analysis


The goal is to visualize a persons LinkedIn network data in order to show the main patterns in connections 
(companies and roles, etc). This is done using a treemap structure, as well as a networkx graph (in the latter
case after clustering on cosine similarities of the TFIDF vector representations of the company names). 

```bash
# Example usage: 
$ pip install -r requirements.txt
$ jupyter notebook 
```

![relative path 1](/Network_treemap.jpeg?raw=true "Network_treemap.jpeg")
![relative path 2](/Interactive_graph.jpeg?raw=true "Interactive_graph.jpeg")


# Extending and reusing the basic idea from these sources:
* https://medium.com/@tavish.gobindram/visualizing-my-linkedin-network-c4b232ab2ad0
* https://docs.bokeh.org/en/latest/docs/user_guide/graph.html



