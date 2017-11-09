# Week 5 Context

## Context awareness

**The definition of context:**
Who What When Why.
Relevant of interaction between user and application.

**Context**

* Context display ->GPS can show the location to user directly.
* Context augmentation -> Google album create the album based on where you take the picture.
* Context-aware configuration -> Auto configure: using printer, choose the closest computer.
* Context-triggered action -> lighting change
* Contextual adoption of the environment
* Contextual mediation
* Context-aware presentation -> phone models change when context change.

What the activity the user behaving

<br />

## Characters of HAR (Human active recognition)

#### Execution

Online -> give feedback at real time
Offline -> Analysis data latter

#### Generalisation

User independent -> training on huge user data and build model

User specific -> single user

Temporal -> combine


#### Recognition

Continuous

Segmented 分段的


#### Activities

Periodic 周期的

Sporadic 不定期的

Static


#### System model

stateless

stateful





## Choosing a Sensor

Limitations and opportunities, depending on specification context.

* what is it measuring 
* Performance: Accuracy and precision -> 
  * **Accuracy** ->The **distance** of the main value to **true value**. ->
  * **Precision**-> How **spitting** your value distribution.
* Range of the sensor 
  * resolution or sensitivity of the sensor
  * sampling rate or frame rate
* cost

<br />

#### Preprocessing

* Sampling Rate
  * Interpolation
  * Downsampling -> throw data away

### Segmentation

* Sliding Window
  * Non-overlapping sliding window
  * overlapping sliding window
* Energy Based ->threshholding: separate into several parts
* Additional Context Sources


### Feature Extraction

<br />


### Classification

Hidden Markov Models

Dynamic Time Wrapping

kNN

AdaBoost

Support Vector Machines

Random Forest


Evaluation



#### Training data set



#### Test data set



#### Cross-Validation



Precision of the sensors are totally different with precision of classifiers.

Precision: Number of TP/Total ladled(TP + FP).

Recall: TP/Total number of the activities (TP + FN) 

F1 Score

---

END