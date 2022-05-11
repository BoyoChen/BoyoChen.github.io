Boyo is a Ph.D. student in University of Tokyo working with [Naoto Yokoya](https://naotoyokoya.com). He broadly studies foundational topics in machine learning. His previous researches mainly focus on building up a reliable system for disaster management using computer vision techniques. He received his BS and MS in Computer Science from [National Taiwan University](https://www.csie.ntu.edu.tw/main.php) in 2016 and 2018, respectively, advised by [Hsuan-Tien Lin](https://www.csie.ntu.edu.tw/~htlin/). Before leaving for ph.D., in 2019, he worked at [Appier](https://www.appier.com/) for about one year to acquire experiences in the industry, where he developed a data-intensive API server, handling large-scale data with graphQL.


## <i class="fa fa-chevron-right"></i> Education

<table class="table table-hover">
  <tr>
    <td class="col-md-3">April 2021 - present</td>
    <td>
        <strong>Ph.D.</strong> in Complexity Science and Engineering
        <br>
      The University of Tokyo, Tokyo, Japan
    </td>
  </tr>
  <tr>
    <td class="col-md-3">September 2016 - July 2018</td>
    <td>
        <strong>M.S.</strong> in Computer Science and Information Engineering
        <br>
      National Taiwan University, Taipei, Taiwan
    </td>
  </tr>
  <tr>
    <td class="col-md-3">September 2012 - July 2016</td>
    <td>
        <strong>B.S.</strong> in Computer Science and Information Engineering
        <br>
      National Taiwan University, Taipei, Taiwan
    </td>
  </tr>
</table>


## <i class="fa fa-chevron-right"></i> Working Experience
<table class="table table-hover">
  <tr>
    <td class='col-md-5'>December 2019 - March 2021</td>
    <td>
      <strong>National Taiwan University</strong>, reasearch assistant
    </td>
  </tr>
  <tr>
    <td class='col-md-5'>January 2019 - November 2019</td>
    <td>
      <strong>Appier</strong>, Taipei, Taiwan, Software Engineer
    </td>
  </tr>
  <tr>
    <td class='col-md-5'>September 2018 - December 2018</td>
    <td>Military Service in Taiwan.</td>
  </tr>
  <tr>
    <td class='col-md-5'>July 2017 - August 2017</td>
    <td><strong>Yahoo</strong>, Taipei, Taiwan, Software Engineer Intern</td>
  </tr>
</table>


## <i class="fa fa-chevron-right"></i> Publications

<table class="table table-hover">
  <tr>
  <td class="col-md-3"><img src="images/publications/chen2018rotation.png"/></td>
  <td>
      <strong>Rotation-blended CNNs on a new open dataset for tropical cyclone image-to-intensity regression</strong><br>
      <strong>Boyo Chen</strong>, Buo-Fu Chen, Hsuan-Tien Lin<br>
      KDD 2018<br>
      
  [<a href='javascript:;'
      onclick='$("#abs_chen2018rotation").toggle()'>abs</a>] [<a href='https://www.csie.ntu.edu.tw/~htlin/paper/doc/kdd18tcir.pdf' target='_blank'>pdf</a>] <br>
      
  <div id="abs_chen2018rotation" style="text-align: justify; display: none" markdown="1">
  Tropical cyclone (TC) is a type of severe weather systems that occur in tropical regions. Accurate estimation of TC intensity is crucial for disaster management. Moreover, the intensity estimation task is the key to understand and forecast the behavior of TCs better. Recently, the task has begun to attract attention from not only meteorologists but also data scientists. Nevertheless, it is hard to stimulate joint research between both types of scholars without a benchmark dataset to work on together. In this work, we release a such a benchmark dataset, which is a new open dataset collected from satellite remote sensing, for the TC-image-to-intensity estimation task. We also propose a novel model to solve this task based on the convolutional neural network (CNN). We discover that the usual CNN, which is mature for object recognition, requires several modifications when being used for the intensity estimation task. Furthermore, we combine the domain knowledge of meteorologists, such as the rotation- invariance of TCs, into our model design to reach better performance. Experimental results on the released benchmark dataset verify that the proposed model is among the most accurate models that can be used for TC intensity estimation, while being relatively more stable across all situations. The results demonstrate the potential of applying data science for meteorology study.
  </div>

  In this work, we apply <strong>specialized</strong> CNN to tropical cyclone intensity regression tasks, set up a remarkable benchmark for disaster management of tropical cyclones. The proposed framework is used for forecasting in <a href="https://www.cwb.gov.tw/eng/">Central Weather Bureau, Taiwan</a>.
  </td>
  </tr>

  <tr>
  <td class="col-md-3"><img src="images/publications/chen2019estimating.png"/></td>
  <td>
      <strong>Estimating Tropical Cyclone Intensity by Satellite Imagery Utilizing Convolutional Neural Networks</strong><br>
      Buo-Fu Chen, <strong>Boyo Chen</strong>, Hsuan-Tien Lin, Russell L. Elsberry<br>
      Weather and Forecasting 34 (2), 447-465<br>
      
  [<a href='javascript:;'
      onclick='$("#abs_chen2019estimating").toggle()'>abs</a>] [<a href='https://journals.ametsoc.org/waf/article/34/2/447/291' target='_blank'>pdf</a>] <br>
      
  <div id="abs_chen2019estimating" style="text-align: justify; display: none" markdown="1">
  Accurately estimating tropical cyclone (TC) intensity is one of the most critical steps in TC forecasting and disaster warning/management. For over 40 years, the Dvorak technique (and several improved versions) has been applied for estimating TC intensity by forecasters worldwide. However, the operational Dvorak techniques primarily used in various agencies have several deficiencies, such as inherent subjectivity leading to inconsistent intensity estimates within various basins. This collaborative study between meteorologists and data scientists has developed a deep-learning model using satellite imagery to estimate TC intensity. The conventional convolutional neural network (CNN), which is a mature technology for object classification, requires several modifications when being used for directly estimating TC intensity (a regression task). Compared to the Dvorak technique, the CNN model proposed here is objective and consistent among various basins; it has been trained with satellite infrared brightness temperature and microwave rain-rate data from 1097 global TCs during 2003–14 and optimized with data from 188 TCs during 2015–16. This paper also introduces an upgraded version that further improves the accuracy by using additional TC information (i.e., basin, day of year, local time, longitude, and latitude) and applying a postsmoothing procedure. An independent testing dataset of 94 global TCs during 2017 has been used to evaluate the model performance. A root-mean-square intensity difference of 8.39 kt (1 kt ≈ 0.51 m s−1) is achieved relative to the best track intensities. For a subset of 482 samples analyzed with reconnaissance observations, a root-mean-square intensity difference of 8.79 kt is achieved.
  </div>

  In this journal work, we verified and concluded our work in 2018. The report was published by <strong>Weather and Forecasting</strong>, the best journal in the related field.
  </td>
  </tr>

  <tr>
  <td class="col-md-3"><img src="images/publications/chen2021real.gif"/></td>
  <td>
      <strong>Real-time Tropical Cyclone Intensity Estimation by Handling Temporally Heterogeneous Satellite Data</strong><br>
      <strong>Boyo Chen</strong>, Buo-Fu Chen, Yun-Nung Chen<br>
      AAAI 2021<br>
      
  [<a href='javascript:;'
      onclick='$("#abs_chen2021real").toggle()'>abs</a>] [<a href='https://arxiv.org/abs/2010.14977' target='_blank'>pdf</a>] <br>
      
  <div id="abs_chen2021real" style="text-align: justify; display: none" markdown="1">
  Analyzing big geophysical observational data collected by multiple advanced sensors on various satellite platforms promotes our understanding of the geophysical system. For instance, convolutional neural networks (CNN) have achieved great success in estimating tropical cyclone (TC) intensity based on satellite data with fixed temporal frequency (e.g., 3 h). However, to achieve more timely (under 30 min) and accurate TC intensity estimates, a deep learning model is demanded to handle temporally-heterogeneous satellite observations. Specifically, infrared (IR1) and water vapor (WV) images are available under every 15 minutes, while passive microwave rain rate (PMW) is available for about every 3 hours. Meanwhile, the visible (VIS) channel is severely affected by noise and sunlight intensity, making it difficult to be utilized. Therefore, we propose a novel framework that combines generative adversarial network (GAN) with CNN. The model utilizes all data, including VIS and PMW information, during the training phase and eventually uses only the high-frequent IR1 and WV data for providing intensity estimates during the predicting phase. Experimental results demonstrate that the hybrid GAN-CNN framework achieves comparable precision to the state-of-the-art models, while possessing the capability of increasing the maximum estimation frequency from 3 hours to less than 15 minutes.
  </div>
  Due to the limitation of satellites, the previous work of estimating Tropical Cyclone(TC) intensity can only obtain data once every 3 hours. In this work, we use <strong>Generative Adversarial Networks</strong> to handle missing data. As a result, the frequency for estimating the TC intensity improved from once per <strong>3 hours</strong> to once per <strong>15 minutes</strong>.
  </td>
  </tr>

  <tr>
  <td class="col-md-3"><img src="images/publications/chen2021cnn.gif"/></td>
  <td>
      <strong>CNN Profiler on Polar Coordinate Images for Tropical Cyclone Structure Analysis</strong><br>
      <strong>Boyo Chen</strong>, Buo-Fu Chen, Chun-Min Hsiao<br>
      AAAI 2021<br>
      
  [<a href='javascript:;'
      onclick='$("#abs_chen2021cnn").toggle()'>abs</a>] [<a href='https://arxiv.org/abs/2010.15158' target='_blank'>pdf</a>] <br>
      
  <div id="abs_chen2021cnn" style="text-align: justify; display: none" markdown="1">
  Convolutional neural networks (CNN) have achieved great success in analyzing tropical cyclones (TC) with satellite images in several tasks, such as TC intensity estimation. In contrast, TC structure, which is conventionally described by a few parameters estimated subjectively by meteorology specialists, is still hard to be profiled objectively and routinely. This study applies CNN on satellite images to create the entire TC structure profiles, covering all the structural parameters. By utilizing the meteorological domain knowledge to construct TC wind profiles based on historical structure parameters, we provide valuable labels for training in our newly released benchmark dataset. With such a dataset, we hope to attract more attention to this crucial issue among data scientists. Meanwhile, a baseline is established with a specialized convolutional model operating on polar-coordinates. We discovered that it is more feasible and physically reasonable to extract structural information on polar-coordinates, instead of Cartesian coordinates, according to a TC's rotational and spiral natures. Experimental results on the released benchmark dataset verified the robustness of the proposed model and demonstrated the potential for applying deep learning techniques for this barely developed yet important topic.
  </div>
  Besides the intensity, the <strong>size</strong> of a Tropical Cyclone(TC) is another critical factor for disaster management. We aim to set up a benchmark for objectively and routinely analyzing the TC structure profile, which comprises both intensity and size information. According to a TC's rotational and spiral natures, a specialized convolutional model operating on <strong>polar-coordinates</strong>, instead of <strong>Cartesian coordinates</strong>, is proposed.
  </td>
  </tr>

  <tr>
  <td class="col-md-3"><img src="images/publications/ashesh2021accurate.png"/></td>
  <td>
      <strong>Accurate and Clear Quantitative Precipitation Nowcasting based on a Deep Learning Model with Consecutive Attention and Rainmap Discrimination</strong><br>
      Ashesh, Chia-Tung Chang, Buo-Fu Chen, Hsuan-Tien Lin, <strong>Boyo Chen</strong>, Treng-Shi Huang<br>
      AIES 2022<br>
      
  [<a href='javascript:;'
      onclick='$("#abs_ashesh2021accurate").toggle()'>abs</a>] [<a href='https://arxiv.org/abs/2102.08175' target='_blank'>pdf</a>] <br>
      
  <div id="abs_ashesh2021accurate" style="text-align: justify; display: none" markdown="1">
  Precipitation nowcasting is an important task for weather forecasting. Many recent works aim to predict the high rainfall events more accurately with the help of deep learning techniques, but such events are relatively rare. The rarity is often addressed by formulations that re-weight the rare events. Somehow such a formulation carries a side effect of making "blurry" predictions in low rainfall regions and cannot convince meteorologists to trust its practical usability. We fix the trust issue by introducing a discriminator that encourages the prediction model to generate realistic rain-maps without sacrificing predictive accuracy. Furthermore, we extend the nowcasting time frame from one hour to three hours to further address the needs from meteorologists. The extension is based on consecutive attentions across different hours. We propose a new deep learning model for precipitation nowcasting that includes both the discrimination and attention techniques. The model is examined on a newly-built benchmark dataset that contains both radar data and actual rain data. The benchmark, which will be publicly released, not only establishes the superiority of the proposed model, but also is expected to encourage future research on precipitation nowcasting.
  </div>
  We propose a new deep learning model for precipitation nowcasting that includes both the discrimination and attention techniques. The model is examined on a newly-built benchmark dataset that contains both radar data and actual rain data.
  </td>
  </tr>
</table>


## <i class="fa fa-chevron-right"></i> Teaching Experience

<table class="table table-hover">
  <tr>
    <td class='col-md-2'>2016 fall</td>
    <td>
      <strong>Machine Learning Foundations</strong>, TA<br>
      About 100 students, <a href="https://www.csie.ntu.edu.tw/~htlin/course/mlfound16fall">course link</a>
    </td>
  </tr>
  <tr>
    <td class='col-md-2'>2017 spring</td>
    <td>
      <strong>Machine Learning Techniques</strong>, TA<br>
      About 130 students, <a href="https://www.csie.ntu.edu.tw/~htlin/course/mltech17spring">course link</a>
    </td>
  </tr>
  <tr>
    <td class='col-md-2'>2017 fall</td>
    <td>
      <strong>Machine Learning Foundations</strong>, TA<br>
      About 260 students, <a href="https://www.csie.ntu.edu.tw/~htlin/course/mlfound17fall">course link</a>
    </td>
  </tr>
  <tr>
    <td class='col-md-2'>2018 spring</td>
    <td>
      <strong>Machine Learning Techniques</strong>, TA<br>
      About 200 students, <a href="https://www.csie.ntu.edu.tw/~htlin/course/mltech18spring">course link</a>
    </td>
  </tr>
</table>


## <i class="fa fa-chevron-right"></i> Skills

<table class="table table-hover">
  <tr>
    <td class='col-md-3'>Proficient</td>
    <td>
      Python programming.<br>
      Machine learning algorithms and applications.<br>
      Data-intensive applications.
    </td>
  </tr>
  <tr>
    <td class='col-md-3'>Intermediate</td>
    <td>
      C/C++ programing.<br>
      Document-oriented databases, such as MongDB.<br>
      Build and maintain Restful API and GraphQL API.<br>
      Distributed computing with Apache Spark.
    </td>
  </tr>
  <tr>
    <td class='col-md-3'>With Primary Knowledge</td>
    <td>
      CICD: Jenkins, Docker, Kubernates.<br>
      Relation-oriented databases such as PostgreSQL and MySQL.<br>
      Object-oriented programming using Java, Android.
    </td>
  </tr>
</table>


## <i class="fa fa-chevron-right"></i> Life

<table class="table table-hover">
  <tr>
    <td class='col-md-3'>I married my wife on July 27, 2018.</td>
    <td class='col-md-1'>
      <a href="/images/wedding_large.png">
        <img src="images/wedding.png"/>
      </a>
    </td>
  </tr>
  <tr>
    <td class='col-md-3'>My daughter was born on December 6, 2020.</td>
    <td class='col-md-1'>
      <a href="/images/kuri_large.png">
        <img src="images/kuri.png"/>
      </a>
    </td>
  </tr>
  <tr>
    <td class='col-md-3'>We have two cats, <a href="https://www.instagram.com/chichibolo_ig/">ChiChi and Bolo</a>.</td>
    <td class='col-md-1'>
      <img src="images/chichi&bolo.png"/>  
    </td>
  </tr>
</table>
