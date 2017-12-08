# k-prototypes
  Our project is on the application of an existing algorithm, clustering, to a novel dataset, the Top 100 Instagram accounts. The benefit of this application is to provide insight into the underlying clusters across top accounts on one of the most influential sffocial networks, and also has business and content consumption impacts. The main stumbling blocks are collecting and coding the data, and clustering appropriately for the mixture of numerical and categorical attributes. Scale and timeline is controlled by limiting analysis to the top 100 accounts.
## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

```
Python 3.6
matplotlib
Pyqt5
numpy
scipy
scikit-learn
networkx
```

### Installing

```
pip3 install matplotlib
pip3 install pyqt5
pip3 install -U numpy scipy scikit-learn
pip3 install kmodes
pip3 install numpy 
```

## Running the code

Run gui.py in Data folder, A window will appear to your screen.<br />
In this window, you can view the origin dataset, run k-prototypes algorithm with our data, 
view cluster membership and centroid information.<br />
To view the origin dataset, click *Show origin dataset* button. Instagram.csv file will open.<br />
To run k-prototyps algorithm, input cluster number you want and click *Run algorithm* button, A 3d scatter graph will pop up.<br />
To view cluster membership and centroid information, click *Show cluster membership* and *Show centroid information* button. (**Note.** You must run algorithm before click these two button.)




## Authors

* **Hao Liu**
* **Deeptanshu Singh**
* **Amanda Kwok**
