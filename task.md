-> Git Repository name : mera-payment ( local / remote repo)
-> master   -> commit : 3
    > README.md
    > App.java
   > src/App.config

> create branch : develpement  -> from master
      > commit : 3 
      > src/Maker.java
      > src/Breaker.java
       > create branch feature-x
               > commit : 3
               > src/config/app.config
               > src/config/maker.config
               > src/config/breaker.config

        > push featurex, development and mster
        > create merge request from feature-x to development
     
      > create feature-y from feature-x 
              commit : 5
              src/com/fluid.java
              src/com/train.java
              src/com/brain.java
     >> push feature-y
     > create merge request from feature-y to feature-x
     > create merge request from feature-y to dev
