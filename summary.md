# Summary

## Multitasking During Remote meeting

To explore attendees’ multitasking behavior during remote meetings and such multitasking’s influence on them, the researchers adopted a mixed-methods approach. They analyzed data by using regression analysis for Microsoft's large-scale telementary datasets and by using the open coding method for personal diaries. They have concluded that the multitasking behaviors during the remote meetings are common, and they have related multitasking behavior frequency, and some consequences with factors like meeting’s duration, meeting size, etc. Finally, based on these results, they provided some design suggestions for remote meeting apps and some guidelines for holding remote meetings.

In my opinion, as a research topicing on human-centered computing, it follows a standard process of investigating and also additionally provides suggestions based on the results. The advantage of this paper is that it endeavored to collect a large dataset to conduct a quantitative study, which is not easy for this topic. However, because of the need to protect privacy, lots of inconvenience and vagueness have been brought about, which can lead to untenable arguments. For example, the paper classified all the file editing behavior as multitasking but should taking notes of the meeting be classfied as another task? Also, I think they can do much with what they have gotten from the data. For example, they can use unsupervised learning to cluster file-editing time to make some predictions on when they may multitask. For the diary part, I think the researchers have done well.

## Adversarial Attack On GNN

In this paper, the authors emphasized a more practical setting of adversarial attacks on GNN. Specifically, the author constraint the attack to only some number of nodes that are not top. Under this condition, the authors generalized the white-box attack to the black-box setting by utilizing the gradient and an important score called RWSC. However, by doing node selection based on this score, the authors detected that the loss indeed increased by a lot, but the misclassification rate did not increase the misclassification rate significantly. This is caused by the strong structural inductive biases of the GNN models. Therefore, the author again proposed GC-RWSC, which can compensate for the diminishing-return effect. One of the biggest advantages of this method is that it does not require any information on the structure of the GNN model.

## OPENKE

The paper mainly discussed a toolkit for knowledge embedding which is developed by the authors. Since the present implementation of KE approaches are scattered and unsystematic, the researcheres develop an flexible an dalso unified interface for quick development on the KE models. OpenKE support both GPU learning and parallel learning, and also has pre-trained some embeddings of some learge-scale knowledge graphs.

## Emoji on Github

The research mainly utilized the data of emoji on Github to study if the emoji usage can be used to predict developers' work-related activities. The researchers first collected the data on the usage of emojis on Github, grouping Emoji by their programming language, and type of emoji posts. Then, by using the regression analysis, the researchers used these data to examine emoji usage’s relation with developers’ working status and successfully selected some highly collinear variables. Later, the paper further points out that non-emoji users are more likely to dropouts which indicates the possibility of using emoji usage to predict future dropouts. Finally, they utilize emojis to predict future dropouts of developers. The researchers have shown the possibility of extending such investigation into other contexts.

## GraphWorld

Because the natural datasets for GNN model training are so limited and biased, it is well accepted that the GNN’s development has been affected by such drawbacks in GNN datasets. In this situation, the researchers develop Graphworld, which can generate statistically diverse datasets for the GNN model automatically. Graphworld solves the problems of bias within natural graph datasets, the overfitting phenomenon of present models on old datasets, and the weak accessibility of average researchers to the large graph. By experimenting with GNN models on Graphworld with different tasks, the researchers showed that Graphworld can efficiently sample a useful part of any graph world to do hyperparameter tuning and inference for various GNN models. The researchers also used Graphworld to show that assessing the performance of GNN does not require natural and society-scale graph data, which provides a promising conclusion that the GNN test can cost lower resources than present.

## Learning-to-Rank

The researchers mainly apply the Plackeet-Luce-based litewise learning-to-rank method into the scope of data with partitioned preference. By assuming the noise follows a Gumbel Distribution, the researcher successfully fit the N independent Gubmel variables into the PL model. Later, after developing the probability of a corrected ordering between two partitions (proposition 1), the researchers were able to extend the proposition and efficiently calculate the likelihood and the gradients by numerical integral. By conducting the simulation experiment, the researchers further showed that the proposed PL-Partition method has a better ability to scale for large-scale applications while out-performs other baseline methods.

