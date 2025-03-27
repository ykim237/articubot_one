## articubot mobile control

ros2 launch rosbridge_server rosbridge_websocket_launch.xml address:=0.0.0.0 port:=9090 debug:=true

python3 -m http.server 8080

ros2 launch articubot_one launch_sim.launch.py
