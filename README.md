
<h1>Real-Time Table Tennis Judge</h1>
<p>This project is designed to analyze and score table tennis games in real-time. Using advanced computer vision techniques, the system can track various game elements, including the ball, table, net, and players' hands. It can determine various game events such as bounces and points.</p>
<h2>Features</h2>
<ul>
  <li><strong>Real-Time Analysis:</strong> The system captures and processes video frames in real-time to provide immediate feedback on game events.</li>
  <li><strong>YOLOv8 Model:</strong> A YOLOv8 model trained specifically for table tennis is used to detect and track object relevant to the game.</li>
  <li><strong>Multi-Object Detection:</strong> The model is trained to detect not only the ball but also other relevant objects such as hands, table, net, etc.</li>
  <li><strong>CUDA Acceleration:</strong> The use of CUDA technology ensures fast processing, allowing for seamless real-time performance.</li>
  <li><strong>Game Event Detection:</strong> The system detects key events such as bounces on the table, double bounces, and when the ball hits the floor.</li>
  <li><strong>Player Scoring:</strong> Automatically updates and displays the score based on the detected events.</li>




![image](https://github.com/DanielSInger1/Ping-Pong-Judge/assets/118116425/a5b5f8ea-c3bb-4cba-b500-9e38005b50b4)


  
</ul>
<h2>Future Enhancements</h2>
<p>We are currently working on adding a web client-side to this project. The web interface will provide users with a friendly and intuitive way to interact with the analysis results, making it easier to understand and utilize the insights gained from the game analysis.</p>
