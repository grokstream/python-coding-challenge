## python-coding-challenge

Make sure that you have received access to a Grok instance, and that you can login to the webapp. Please also make sure that you have root access to a linux server on AWS of which we will give you. We will need your public ssh key. Once you confirm that you can ssh into the linux box, and that you have access to an instance of the webapp, you can begin the coding challenge. 

Under the Setup menu on the webapp you will find documentation for our API on this server. This API allows us to stream data into a Grok instance 1 datapoint at a time in 5 minute intervals.

# Part 1

The coding challenge will ask that you do this. Write a small python script that will continuously send data into this Grok instance.  It is your choice for the type of data you would like to send. It could be bitcoin prices at a given time, it could be the CPU utilization on the server at a given time, it could be temperature in your city at a given time. Keep in mind that this data will need to **keep running for a few days.** It is up to you where you want to get this data, whether you read from a csv, whether you make requests to another service to get this data. It doesn’t matter to us, but we will judge your creativity in this process. **We should receive 1 datapoint every 5 minutes.** Once it is streaming this data, leave it like this. This is why we have provided the server for you. We should be able to login to the server in a day or so and see that your service is still sending data.

# Part 2

Your script should include unit tests, or functional tests. We should be able to test your service programmatically. It is up to you what library you would like to do for this. Perhaps you will only have 1 test, perhaps you will have many. It depends how many functions you choose to write, but either way, we could like tests for your script. 

# Part 3

When you have finished Part 1,2 upload all your work to Github, and write a very brief summary on the type of data you are sending to Grok. 

*Note: Please use Python 2.7 for this task. The formats for the API requests can be found in under the Restful API documentation on the web app. By all means reach out to us if you have any questions, or if you encounter problems while using the API. Please make sure that your code follows PEP8 standards. Please make sure that you are doing things the ‘pythonic’ way, where relevant. There is no timelimit for this test. There is no constraint on libraries used.*
