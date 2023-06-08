# Black Dash

Black Dash, your IoT Dashboard in minutes. With Black Dash you will not have to mess with code, all your IoT information can be displayed with almost no programming knowledge and the data is showed in real time.

![Black Dash Main page](/img/main.JPG)

<br />
The system has a settings panel where you can modify certain aspects of the platform. The things you can configure are:

- Administrator

- MQTT Connector

- MQTT Subscribers

- And the different ways you can login into the system (comming soon)

For example, for the broker cofiguration just add the url and the port:
<br />

<img src="/img/broker.JPG" alt="Broker" style="height: 540px; width:720px;"/>
<br />

Now that you have the broker configured, you just need to add the subscribers. Clic on **New subscriber**
<br />

![Black Dash Subscribers](/img/sub.JPG)
<br />

And then you will be able to add the subscriber by setting the MQTT **topic**, in that way, Black Dash is able to receive the data from the sensor. And as you can see, you will have the ability to set the units and the title of the values. Once you have captured the information, you save it and then you will have your new sensor on the dashboard.
![Black Dash Subscribers](/img/new_sub.JPG)

![Black Dash Subscribers](/img/new_sub_dash.jpg)
<br />

As you can see, the process is easy and no code required. In just a couple of minutes you can add your IoT devices, and not only that, but you can update or delete them. 

And by the way, we are aware of the importance of SSO in the industry, so Black Dash works with Microsoft Azure Active Directory. SSO works not only for the users, but also for the administrator of the platform. An administrator will have the option to access the system settings using a password or using Microsot SSO
![Black Dash Subscribers](/img/sso.JPG)

There are still some minor features to be added, for example:
- Give the administrator the ability to set a timer to know when a sensor is not sending data
- Allow the administrator to disable the username and password option

And there is still room for improvement, we are open to hear new ideas. 

For the moment those are the features the system has and we believe in its potential.
