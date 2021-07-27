## OBJECTIVE:
To deploy a twitter bot that keeps updating the current number of followers of the account.


## In GitHub:

    Create a repository with the above three files.

    main_bot.py is the main code containing the working of the twitter bot.

    requirements.txt file contains the required library i.e, “tweepy” which is a python library to access Twitter API.

    Procfile is the root of the application with the main worker being main_bot.py.

## In Heroku:

    Create a new app with a valid name.

At Deploy:

    Choose an appropriate deployment method, in our case GitHub (authorize your account and add the above repository, repository containing the above three files) and connect.

    Enable automatic deploys (any changes in the master will deploy a new version of this app).

At Settings:

    Go to “config vars” and at “Reveal config vars”, save the required API keys and access tokens with the help of the keys provided by the app created at “twitter developer account” and store these keys along the correct variables as mentioned in the code in main_bot.py.

At Resource:

    Turn on the worker dynos.
  
At Overview:

    You can view your “latest activities” where you can see if your build is succeeded.
  
    To check the steps in details or to check for any errors, go to “view build log” and at “view log” you can see the errors(if any) and rectify it or you can see if your build is succeeded and the intermediate steps to the working.
  
    If “Build succeeded”. This implies that the app is working and on checking your twitter account you will find your follower count and the count changes if any changes occur on the follower count in your twitter account.

## WORKING

    Click on your account to check the follower count.

