# Projekt_AIR-2023-KG_RK_DP
Projekt - Śledzenie ruchomego znacznika "Marker Follower"
zakres projektu:
- realizacja w środowisku symulacyjnym 
- zachowanie zadanego dystansu od znacznika 
- sterownie pozycyjne

Celem projektu było stworzenie symulacji w środowisku Gazebo, w której została wykorzystana funkcja Marker Follower. Funkcja ta polega na podążaniu za obiektem. 
Dron może poruszać się w zadanej odlegości podążajćego obiektu. 

Uruchomienie pliku:
1.Utworzyć przestrzeń roboczą
2.Importować plik tello_tracker.py
3.uruchomić program z terminala 

funcjonalność programu zralizowana:
- Uruchomienie drona w programie Gazebo
- Możliwość ustawienia parametrów lotu drona
- Wyświetlanie kamery

funkcjonalność nie zrealizowana:
- Ustalanie odpowiedniej odległości od obiektu 
- Podążenie za obiektem 

W programie zostały wykorzystane biblioteki :
-import rclpy
-from rclpy.node import Node
-from sensor_msgs.msg import Image
-from cv_bridge import CvBridge
-import cv2
-import numpy as np
-from geometry_msgs.msg import Twist
-from tello_msgs.srv import TelloAction

