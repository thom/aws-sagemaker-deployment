# Udacity Deep Learning Nanodegree Program - Project: Deploying a Sentiment Analysis Model

The notebook and Python files provided here, once completed, result in a simple
web app which interacts with a deployed recurrent neural network performing
sentiment analysis on movie reviews.

## Setup Instructions

### Log in to the AWS console and create a notebook instance

Log in to the AWS console and go to the SageMaker dashboard. Click on "Create
notebook instance". The notebook name can be anything and using ml.t2.medium is
a good idea as it is covered under the free tier. For the role, creating a new
role works fine. Using the default options is also okay. Important to note that
you need the notebook instance to have access to S3 resources, which it does by
default. In particular, any S3 bucket or object with "sagemaker" in the name is
available to the notebook.

### Use git to clone the repository into the notebook instance

Once the instance has been started and is accessible, click on "Open" to get the
Jupyter notebook main page. We will begin by cloning the SageMaker Deployment
GitHub repository into the notebook instance. Note that we want to make sure to
clone this into the appropriate directory so that the data will be preserved
between sessions.

Click on the "New" dropdown menu and select "Terminal". By default, the working
directory of the terminal instance is the home directory, however, the Jupyter
notebook hub's root directory is under "SageMaker". Enter the appropriate
directory and clone the repository as follows:

```bash
cd SageMaker
git clone https://github.com/thom/aws-sagemaker-deployment.git
exit
```

After you have finished, close the terminal window and open and run the
"SageMaker Project.ipynb" notebook.

## Requirements

Graded according to the [Project Rubric](https://review.udacity.com/#!/rubrics/2262/view).

## License

- **[MIT license](http://opensource.org/licenses/mit-license.php)**
- Copyright 2021 © [Thomas Weibel](https://github.com/thom).
