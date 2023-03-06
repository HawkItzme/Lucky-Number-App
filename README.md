# Lucky-Number-App
An android app to understand Intents(Explicit and Implicit intents).
## INTENTS
Intents in Android is a messaging object you can use to request an action from another app component. 
Although intents, facilitate communication between components in several ways, there are three fundamental
use cases for intents, starting an activity, starting a service or delivering a broadcast.

### Starting an activity
We use intents to start an activity or present a single screen in an app. You can start an instance of an activity by passing an intent to start activity method.
The intent describes the activity to start and carries any necessary data.

### Start a service
A service is a component that performs operation in the background without a user interface. 

### Deliver a broadcast
A broadcast is a message that any app can receive. The system delivers various broadcasts from system for system events, such as when the system boots
up or the device starts changing.

There are two types of Intents:-
1. Explicit Intents
2. Implicit intents

***Explicit intents*** specify which application will satisfy the intent by supplying either the target applications package name or a fully qualified component class name.

You will typically use an explicit intent to start a component in your application because you know the class name of the activity or service you want to start.
For example, you might start in your activity within your application in response to a user action or start a service to download a file in the background.

***Implicit intents*** do not name a specific component, but instead declare a general action to perform, which allows a component from another app to handle it.
For example, if we want to show the user a location on the map, you can use an implicit intent to request that another capable application show a specified location on a map.
Let's say, you can request from Google Maps, this is implicit intents.
