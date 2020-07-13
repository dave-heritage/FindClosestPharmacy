# FindClosestPharmacy

This is an API that outputs a users nearest pharmacy based on their inputted longitude and latitude.

## Technologies Used:
* AWS API Gateway
* AWS Lamda
* Nodejs

## Getting Set Up

You can use [Postman](https://www.postman.com/downloads/) or simply your default [browser](https://i6eb3w423j.execute-api.us-east-2.amazonaws.com/live/pharmacylocation?latitude=39.001423&longitude=-95.68695) to see the output of this API.

If you chose to use Postman you can download the [Postman Collection](https://github.com/davidhudsonheritage/FindClosestPharmacy/blob/master/RXSavingSolutions.postman_collection) and run the requests locally. 

If you would like to do this with your own endpoint you will have to create a new API Gateway on your AWS account, link a lamda function to your API Gateway and copy the code in [index.js](https://github.com/davidhudsonheritage/FindClosestPharmacy/blob/master/index.js) to your lamda function. Instructions on how to do that can be found [here](https://docs.aws.amazon.com/apigateway/latest/developerguide/apigateway-getting-started-with-rest-apis.html).

## Usage

Copy the following into a browser and input the desired latitude and longitude values.

https://i6eb3w423j.execute-api.us-east-2.amazonaws.com/live/pharmacylocation?latitude=**YourLatitudeValue**&longitude=**YourLongitudeValue**

