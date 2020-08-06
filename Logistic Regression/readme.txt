Task Definition:
Our aim is to develop a framework for the classification of webpages on SHC websites as Contraception related or not. 
We have designed this problem as a binary classification problem where we classify a given webpage into the ‘Contraception’ class or the ‘Other’ class.

Challenges in Task formulation:
i. SHC webpages contain sparse information. In order to train a model with contraception related features, we need rich textual content in this domain. SHC webpages do not serve as an appropriate source of content-rich text for generating training data. 
ii. The model needs to be appropriately trained and engineered to help it classify a page that briefly mentions contraceptive methods as a page related to contraception or not.
iii. The other challenge was to define the ‘Other class’ for classification. The other class includes any and all pages except those having contraception related information. We wanted to restrict the pages from the other class to the domain of health-care and to student health center webpages. 

Algorithmic Design:
Classification of a webpage as a contraception related page depends on the presence or absence of certain signals on that page. The signals could include specific terms, phrases, styles of writing, etc.  These signals should be learnt from those pages that are already known to have content on Contraception. Signals act as ‘features’ for a particular class. When documents related to a single topic are placed in one class, the class becomes representative of features specific to that class. In a binary classification problem like ours where the goal is to classify a given webpage as contraception related or not, we need appropriate training data for both the classes so that the classification model can learn features peculiar to both classes. For our classification problem, the other class includes any page on the SHC website that does not have content on contraception. Thus, our training data for the other class has webpages that are health-related but do not have information on contraception, whereas the training data for the contraception class has pages that are contraception specific.

