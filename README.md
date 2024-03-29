# Promises-in-JavaScript-LWC

![image](https://user-images.githubusercontent.com/43552295/231123439-c13f70f4-01ca-480c-ad4c-03800dc4cd6e.png)

![image](https://user-images.githubusercontent.com/43552295/231128901-4412eb0c-3dc7-4b37-90cb-90980169bd65.png)


![image](https://user-images.githubusercontent.com/43552295/231123790-59d4b0a1-78da-4c9a-8d27-aae4ee1a1f7b.png)

![image](https://user-images.githubusercontent.com/43552295/231123917-0dd47db6-7c98-4d9f-90d0-19719b99deff.png)

![image](https://user-images.githubusercontent.com/43552295/231124079-efc6b63e-be40-41e4-93ad-bab72dca71d2.png)

![image](https://user-images.githubusercontent.com/43552295/231124310-d2c5d308-88ce-45e2-b976-cb9ef0413af3.png)

![image](https://user-images.githubusercontent.com/43552295/231127303-13d804f9-285a-477d-9d0c-aa70630724bb.png)

![image](https://user-images.githubusercontent.com/43552295/231127228-16b2c04c-39b4-48d4-b632-43c76a761197.png)

![image](https://user-images.githubusercontent.com/43552295/231128399-a8c56f35-f023-443e-b6bf-c791218e368a.png)

![image](https://user-images.githubusercontent.com/43552295/231128473-fd14d95d-5aec-4b9f-a86d-6ba239fbb00c.png)

![image](https://user-images.githubusercontent.com/43552295/231128681-148a4ace-2342-4a9d-8cd1-53f3b1a281e5.png)

//Finally will get executed every time whether the promise is success or failure.
![image](https://user-images.githubusercontent.com/43552295/231128719-8c50575e-ea90-4898-9be4-e698b4bbf67a.png)

//promise.reject
![image](https://user-images.githubusercontent.com/43552295/231133293-d9ca4bf7-dcbb-4587-8d09-634453a802c9.png)

![image](https://user-images.githubusercontent.com/43552295/231133445-20d08e95-62cd-408e-a408-f2dbb6cf2e0e.png)

//promise.resolve
![image](https://user-images.githubusercontent.com/43552295/231138869-e130320b-e0c4-4200-a2e0-64da30a2b078.png)

//promise.all - > Wait for all promises to be resolved or any promise to be rejected
![image](https://user-images.githubusercontent.com/43552295/231157115-7c600a34-23d2-4920-ab4d-f1f098b6f9a7.png)

![image](https://user-images.githubusercontent.com/43552295/231157507-c7163441-b578-4c92-9c06-6e0848111dfd.png)

//console.time(),console.timeLog(),console.timeEnd()   -->>   It will return the maximum time taken of all the promises. In below example maximum time taken by promise is 5 seconds
![image](https://user-images.githubusercontent.com/43552295/231175112-72f592a2-d5ce-41b8-a739-b75ee0d5a71e.png)

//promise.any -> returns the promise which is fulfilled first i.e it returns only one promise out of all promises which is completed first
![image](https://user-images.githubusercontent.com/43552295/231178442-ddededf6-410a-4f93-8c6e-b5610bb1821f.png)

//In the below image it is returning not retuning message of reject because promise.any returns promise which is first resolved 
![image](https://user-images.githubusercontent.com/43552295/231178738-86ea6e8c-c79b-4dcc-87ae-b1c475589129.png)

//promise.race -> returns any of the promise which is fulfilled or rejected first

Below Image is returning error car 3 has crashed because it is the first promise which got executed
![image](https://user-images.githubusercontent.com/43552295/231181968-97bb8ec8-cf15-4974-a569-455c20625f0f.png)

Below image is returning error car 3 has crashed and not Car 1 has completed the race  even the time is set to zero for that promise, because in the rejected promise setTimeout is not given and preference is given to the promise without setTimeOut.
![image](https://user-images.githubusercontent.com/43552295/231182681-ba396ad2-5edb-4305-81e0-323c09788331.png)

Below image is returning car 1 has completed the race even though setTimeout for promise2 is also 0. Because the promise for ar 1 has completed the race is before promise2 and gets executed earlier than promise2.
![image](https://user-images.githubusercontent.com/43552295/231187049-2ca8bb66-08ff-411b-bc5a-2cc1a2cbb480.png)

//promise.allSettled ->> gets executed after every promise goes to settled state.Promises in reject or fulfilled state will always go to settled state in the end.
In below image all promises will go to settled state in the end, so it is printing all the messages.
![image](https://user-images.githubusercontent.com/43552295/231194317-b436e7e0-ecba-423a-b31e-758dd7f0b67a.png)

//Chaining in Promises


![image](https://user-images.githubusercontent.com/43552295/232278143-ac61d314-42c7-4c3e-864c-6a5da2c376b0.png)


