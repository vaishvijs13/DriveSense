# Hack the North 2023 Winner: Drive Sense

## Inspiration:
Our inspiration for this app comes from the critical need to improve road safety and assess driver performance in a world where distracted driving and hazardous road conditions claim thousands of lives every year. The alarming statistics on road accidents and fatalities, including those caused by distracted driving and poor road conditions, highlight the urgency of addressing this issue. We were inspired to build a solution that leverages technology to enhance driver competence and reduce accidents.

## What it does
Our app features a React-based frontend that connects to GPS signals, tracking a vehicle's acceleration and speed in real time. The frontend also includes an interactive map and a recording feature powered by Cohere's LLM, capable of detecting and alerting authorities in cases of violent or hateful speech related to road conditions.

On the backend, we use advanced algorithms and fine-tuned computer vision models based on YOLOv5 and YOLOv8. These models process camera feeds to analyze surrounding vehicles, detect traffic light colors, and measure the size of car plates ahead. By tracking car plates, we infer a vehicle's acceleration based on changes in their size, providing valuable insights into driver habits. By analyzing traffic light data and correlating it with GPS signals, the app evaluates reaction times and generates a comprehensive rating of the driver’s capabilities.

Additionally, an integrated eye-tracking model monitors the driver's focus and concentration on the road. Together with its interactive mobile app, our solution redefines traditional dashcams by offering advanced hazard detection and driver assessment, ensuring safety and protection against road hazards.

## Check it out:
* Demo at Hack the North Closing Ceremonies: https://www.youtube.com/live/7sVzflHqHAo?t=1941s
* Official Video: https://www.youtube.com/watch?v=G3tUnQWzXzw
* Devpost: https://devpost.com/software/drive-sense

![image](https://github.com/user-attachments/assets/f7b50e39-8187-4a2a-9c73-14afefb4776d)
