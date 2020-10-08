# The FakeReviews-RestaurantDataset Repository
# Restaurant Fake Reviews Dataset
The Restaurant Dataset consists of 110 reviews in total of which 55 are fake and 55 are geniune reviews for three hypothetical indian restaurants. The dataset is also balanced in terms of negative and positive reviews. 

# Citing this Dataset:

* * *Faranak Abri, Luis Felipe Gutiérrez, Akbar Siami Namin, Keith S. Jones, and David R. W. Sears, Linguistic Features for Detecting Fake Reviews. International Conference on Machine Learning Applications (ICMLA) 2020, December 2020, Miami - Florida, US.*


# Meta Data about the Dataset

The reviews are about three real Indian restaurants. We changed the names to imaginary ones.
If the Reviewer value=0 it means the review was extracted reviews from legitimate users about the restaurants from online resources. Other values show the review is a fake one written by a specific reviewer with the given ID, There were four different reviewers.

The excel file contains 19 columns as follows:

1. **Restaurant**: The name of the fictionized restaurant. 

2. **Review**: The textual description of review given by a reviewer

3. **Real**: This column shows if the review is fake (value=0) or real (value=1)

4. **Reviewer**: The ID of the reviewer. If the value=0 it means the review is legitimate and real. If the value <> 0, the value shows the identify of the reviewer.

5. **F1-AWL**: Average word length.

6. **F2-PAU**: Pausality.

7. **F3-ANP**: Average noun-phrase length.

8. **F4-ASL**: Average sentence length

9. **F5-NCL**: Number of clauses.


Thanks to Pritish Ayer, Sagar Lamichhane, Omer Qureshi, and Pranaya Sharma for contributions to the Restaurant datasetcreation. This research work is supported by National Science Foundation under Grant No: 1723765.

10. **F6-NWO**: Number of words.

11. **F7-NVB**: Number of verbs.

12. **F8-NAJ**: Number of adjectives.

13. **F9-NPV**: Number of passive voice.

14. **F10-EMO**: Emotiveness.

15. **F11-CDV**: Content diversity.

16. **F12-RED**: Redundancy.

17. **F13-LXD**: Lexical diversity.

18. **F14-NMV**: Number of modal verbs.

19. **F15-NTY**: Number of typos.



# Contributors to Data Generation:

* Pritish Ayer
* Sagar Lamichhane
* Omer Qureshi
* Pranaya Sharma

# Acknowledgment:

This research work is supported by National Science Foundation under Grant No: 1723765.
