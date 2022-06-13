# zoom-meet-host
-----------------------------
## Host a zoom meet with this python script 🤖
-----------------------------
### To use the zoom API 
1. Visit [Zoom API Marketplace](https://marketplace.zoom.us/) and either sign up or sign in with your zoom account. 
2. Now click Develop and then click on build app.

![image](https://user-images.githubusercontent.com/83634399/173336913-d2a8f69e-53c0-4b0b-a123-bc6e9f304583.png)

3. Click agree to Zoom’s API License and Terms of Use.
4. Choose the app type as JWT, because JWT is easy to use.

![image](https://user-images.githubusercontent.com/83634399/173337107-f5dd7344-50c8-431b-973b-02afd838fdca.png)

5. Enter the name of your app and click create.
6. Now fill in some mandatory details such as Your company name, Developer’s name, and email address, for company name you may enter your name, and after the completion click continue.
7. Now go to the App credential tab copy your API key and your API Secret and save it somewhere.

-----------------------------

### Before running the script
#### Run the following command to install all the requirements:
```
$ pip install -r requirements.txt
```

-----------------------------

#### Create a '.env' file and add the following:
```
APIKEY='YOUR_API_KEY'
APISEC='YOUR_SECRET_API_KEY'
```
-----------------------------

### Execution
Run the following command:
```
python create_meet.py
```

-----------------------------

> Thank you for using this repo! Feel free to contibute ❤️
