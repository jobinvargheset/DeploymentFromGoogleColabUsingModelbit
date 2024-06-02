IDLE to be used: Google Colab
This project is for deploying the output from google colab directly through the browser using Modelbit. 
Once the deployment is made, the results can be accessed from any where or any other computer having the Modelbit. 
Modelbit is free for 30 days of deployment. Login to Modelbit is required for correct deployment. 
I deploy in one browser and will check whether this will work by running the code "!curl -s -XPOST "**https://jobinvarghese.app.modelbit.com/v1/predict_loan_default/latest" -d '{"data": [32, 821233, 689, 1, 10789]}' | json_pp** " in the other browser
The name changes with the user who is logging in modelbit, and also the dataset changes
