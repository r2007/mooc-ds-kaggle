#Kaggle比赛介绍
##2015

###玩法：
* kaggle参赛可以个人参赛或者组队参赛，好像单打独斗的可以随时组队或者直接加入某队，一般的比赛team和team之间也可合并成一个大的team（具体可以查看每个比赛的详细规则）。每天可以提交结果的次数有上限，按人头算的，人数多的队提交次数也多。

* 大家可以根据个人情况选择合适的比赛，先注册账号参赛，随时欢迎群内讨论，鼓励组队提升合作能力和实战能力。

* 注意：根据kaggle规则，组内人员可以share数据和代码，不同组的不能，所以在群内只能讨论算法了，不能晒代码。
* 关于是否保留计算过程，由于本人未曾拿到那么高的名次，情况不详，建议最好保留模型，以便能再次重现你的提交答案。

###正在进行的比赛：
1. [**Random Acts of Pizza**](http://www.kaggle.com/c/random-acts-of-pizza)

  截止日：6月1日

  类型：二元分类（含文本数据和统计数据）  数据量：中等  特征数量：中等

  根据用户的申请（里面有统计数据，也有文本数据），判断是否拿到披萨。

  评估标准：ROC（不是很懂）


2. [**Digit Recognizer**](http://www.kaggle.com/c/digit-recognizer)

  截止日：12月31日
  
  类型：监督学习－多元分类  数据量：中等  特征数量：中等

  用28 x 28的手写数字灰度图像  识别数字0-9
  
  n张训练图像

  2800张测试图像
  
  评估标准：准确率
  
  目前第一名： 1（已封顶）


3. [**Facial Keypoints Detection**](https://www.kaggle.com/c/facial-keypoints-detection)

  截止日：12月31日

  类型：监督学习－回归  数据量：中等  特征数量：中等

  对每个96x96的0-255灰度人脸图像 预测出指定的15个关键点坐标 这15个关键点有（左右眼中心点，鼻子尖，嘴角等等）。

  具体是：left_eye_center, right_eye_center, left_eye_inner_corner, left_eye_outer_corner, right_eye_inner_corner, right_eye_outer_corner, left_eyebrow_inner_end, left_eyebrow_outer_end, right_eyebrow_inner_end, right_eyebrow_outer_end, nose_tip, mouth_left_corner, mouth_right_corner, mouth_center_top_lip, mouth_center_bottom_lip

  7049张训练图像

  1783张测试图像

  评估标准： Root Mean Squared Error

  目前为止LB第一名：1.74158

4. [**Bag of Words Meets Bags of Popcorn**](http://www.kaggle.com/c/word2vec-nlp-tutorial)

  截止日：6月30日

  类型：NLP 二元分类 数据量：中等  特征数量：NA

  根据IMDB里面对电影的文字评论，判别是好评还是差评。

  评估标准：ROC（http://en.wikipedia.org/wiki/Receiver_operating_characteristic）

5. [**Titanic: Machine Learning from Disaster**](http://www.kaggle.com/c/titanic-gettingStarted)

  截止日：12月31日

  （没搞懂欢迎补充）
  
  补充：据群主和群友告知，这个不太好玩。

6. [**Bike Sharing Demand**](https://www.kaggle.com/c/bike-sharing-demand)

  截止日：5月29日
  
  类型：监督学习－回归  数据量：少  特征数量：少

  给出某月前19天的自行车租赁数据，预测这个月余下天数里每小时的租车数量

  评估标准：Root Mean Squared Logarithmic Error (RMSLE)
