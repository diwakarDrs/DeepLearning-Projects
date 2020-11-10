# flask based web app for malaria detection

## Demo



<p align='center'>
 
 <img src = "https://github.com/diwakarDrs/DeepLearning-Projects/blob/main/Malarial_cell_detection/ReadME/App.PNG" width = 600 alt="malaria">
 </p>

## About the app
> This project is a binary medical image classification model, based on convolutional neural network architecture.
The CNN has trained on the following malaria parasite image dataset  <a href="https://ceb.nlm.nih.gov/repositories/malaria-datasets/">National Library of Medicine</a>.
The trained model achieved accuracy of more than 95% on the test set and its weights have been saved in the Models folder (see file: my_model.h5). 



<ul>
<li>Inclusion of a procfile to serve the app with gunicorn on the Heroku server after upload (for uploading this python app to Heroku please follow Heroku documentation on how to use git with Heroku)</li>
<li>As per Heroku requirements for stability and reproducibility, versions of all required python environments were specified in the requirements.txt file</li>
<li>Inclusion of gunicorn to the requirements.txt file</li>
<li>Changed the app.py (flask app) file to adapt it to the required functionality according to the trained binary image classification model. The program was also modified to delete every uploaded image after providing the prediction. This will prevent exceeding capacity limits on Heroku servers. The last lines of the file have been modified to work with gunicorn. </li>
<li>The Index.html and base.html files have been modified accordingly to include references and information about the model</li>
<li>This README file has been adapted to provide instructions about heroku deployment. The part for customisation has been modified also</li>
</ul>

> To create a web app that runs locally follow instructions in the README file, to run the model locally. Gevent or gunicorn may be used for local deployment too.


### Use other pre-trained model

See [Keras applications](https://keras.io/applications/) for more available models such as DenseNet, MobilNet, NASNet, etc.


## Deployment
To deploy in cloud, we can upload this app on heroku or other python enabled server. 

## More resources

[Building a simple Keras + deep learning REST API](https://blog.keras.io/building-a-simple-keras-deep-learning-rest-api.html).

[How to deploy a Flask App to Heroku](https://progblog.io/How-to-deploy-a-Flask-App-to-Heroku/).

