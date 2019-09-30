# midwest_OF_2019 - CAD parametrization using Onshape's API

Working cases for midwest 2019-OF meeting
https://sites.google.com/view/mofug2019v1/home



The case works with OpenFOAM 7.


To run the CAD parametrization cases using onshape you will need to install the API
https://github.com/onshape-public/apikey

We recommend to install the python API
https://github.com/onshape-public/apikey/tree/master/python

To install the API follow the instructions in the link (they are straightforward)
You can also follow our instructions.  You will find them in the directory API_installation


In the directory support_files of each case look for the file creds.json and add your credentials
To generate the API key go to https://dev-portal.onshape.com/keys

*********************************
{
    "https://cad.onshape.com": {
        "access_key": "YOUR ACCESS KEY",
        "secret_key": "YOUR SECRET KEY"
    }
}
*********************************

