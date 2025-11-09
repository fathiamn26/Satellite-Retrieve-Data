For this project, we are using satellite data to track location, humidity, temperature, and sound (noise) from user's location along with user's health data from ECG sensor. We will integrate these datas to get personalized exercise or hang out location based on their health condition, classifying whether the user has normal or crticical heart condition. We use Grove Beginner Kit, Kineis receiver, and Movesense ECG sensor for the hardware. The user does not always need to use Movesense ECG sensor, they can use whatever wearable things or just their mobile phone health application (Apple Health, Samsung Health, Xiaomi Health, etc.) to get the personalized recommendations. Here are several important things about the github file. 
1. basiccode is containing main code you could use for retrieve satellite info
2. Lead I is an ECG data from Movesense Sensor. There is also a ready-to-use CSV data for Lead I
3. Apple-data is exported heat beat (BPM) data from apple watch. it's not ECG graph, just a value of BPM per day
4. Satellite data is retrieved in satellite.csv
5. You can check the flowchart in the hackathon.jpg
