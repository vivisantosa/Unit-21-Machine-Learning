# Unit-21-Machine-Learning
<img src="/images/exoplanets.jpg" width="1080"><br>

Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.
To clasify this data, we create machine learning models to classify candidate exoplanets from the raw dataset.<br><br>



The modeling process began with the cleaning and selecting the raw data.<br>

<img align="right" src="/images/sample1.png" width="420"> <img align="right" src="/images/df2.png" width="300">  
We started with "Decision Tree Model", with all the features. we plotted the tree as seen below, After which we tuned it with less features (the best 10 and 4 features). 

We then we add "Random Forrest Model" and "Logistic Regression Model". After that we compare the models.<br>

The exploration of the models produce the results below

<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th>test</th>
      <th>model type</th>
      <th>file name</th>
      <th>features</th>
      <th>testing data score</th>
      <th>grid best params</th>
      <th>grid best score</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>1</th>
      <td>decision tree</td>
      <td>model_dt2</td>  
      <td>40</td>
      <td>0.8466819221967964</td>
      <td>{'C': 10, 'gamma': 0.0001}</td>
      <td>0.8714435412861394</td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <th>2</th>
      <td>decision tree</td>
      <td>model_dt2</td>  
      <td>10</td>     
      <td>0.852974828375286</td>
      <td>{'C': 10, 'gamma': 0.0001}</td>
      <td>0.8319639205641142</td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <th>3</th>
      <td>decision tree</td>
      <td>model_dt3</td>  
      <td>4</td>     
      <td>0.8243707093821511</td>
      <td>{'C': 5, 'gamma': 0.0001}}</td>
      <td>0.7547176882381621</td>
    </tr>
  </tbody> 
  <tbody>
    <tr>
      <th>4</th>
      <td>random forrest</td>
      <td>model_rf1</td>  
      <td>40</td>     
      <td>0.8981693363844394</td>
      <td>{'C': 10, 'gamma': 0.0001}</td>
      <td>0.8714435412861394</td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <th>5</th>
      <td>random forrest</td>
      <td>model_rf2</td>  
      <td>10</td>     
      <td>0.8895881006864989</td>
      <td>{'C': 10, 'gamma': 0.0001}</td>
      <td>0.8466485711582823</td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <th>6</th>
      <td>logistic regression</td>
      <td>model_lr1</td>  
      <td>40</td>     
      <td>0.8443935926773455</td>
      <td>{'C': 10, 'penalty': 'l2'}</td>
      <td>0.8683919254251595</td>
    </tr>
  </tbody>  
  <tbody>
    <tr>
      <th>7</th>
      <td>logistic regression</td>
      <td>model_lr2</td>  
      <td>10</td>     
      <td>0.7934782608695652</td>
      <td>{'C': 10, 'penalty': 'l2'}</td>
      <td>0.8504615446190119</td>
    </tr>
  </tbody>    
</table>


