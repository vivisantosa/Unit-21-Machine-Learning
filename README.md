# Unit-21-Machine-Learning
Creating classification models of Exoplanets


The queries in [sql_epilogue.sql](https://github.com/vivisantosa/Unit-09-SQL-challenge/blob/master/sql_epilogue.sql) produce this result

<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th>test</th>
      <th>model type</th>
      <th>file name</th>
      <th># of features</th>
      <th>testing data score</th>
      <th>grid best params</th>
      <th>grid best score</th>
      <th>notes</th>
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
      <td>-</td>
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
      <td>-</td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <th>3</th>
      <td>random forrest</td>
      <td>model_rf1</td>  
      <td>40</td>     
      <td>0.8981693363844394</td>
      <td>{'C': 10, 'gamma': 0.0001}</td>
      <td>0.8714435412861394</td>
      <td>-</td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <th>4</th>
      <td>random forrest</td>
      <td>model_rf2</td>  
      <td>10</td>     
      <td>0.8895881006864989</td>
      <td>{'C': 10, 'gamma': 0.0001}</td>
      <td>0.8466485711582823</td>
      <td>-</td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <th>5</th>
      <td>logistic regression</td>
      <td>model_lr1</td>  
      <td>40</td>     
      <td>0.8443935926773455</td>
      <td>{'C': 10, 'penalty': 'l2'}</td>
      <td>0.8683919254251595</td>
      <td>-</td>
    </tr>
  </tbody>  
  <tbody>
    <tr>
      <th>6</th>
      <td>logistic regression</td>
      <td>model_lr2</td>  
      <td>10</td>     
      <td>0.7934782608695652</td>
      <td>{'C': 10, 'penalty': 'l2'}</td>
      <td>0.8504615446190119</td>
      <td>-</td>
    </tr>
  </tbody>    
</table>


