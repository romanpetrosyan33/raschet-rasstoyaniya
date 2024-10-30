# raschet-rasstoyaniya
Моя тема проекта. Программа которая рассчитывает расстояние между городами.
Эту программу я написал на языке Python.
import math

def euclidean_distance(lat1, lon1, lat2, lon2):
    # Преобразование координат в радианы не требуется для простого евклидова расстояния
    return math.sqrt((lat2 - lat1)**2 + (lon2 - lon1)**2)

# Ввод координат
city1_lat = float(input("Введите широту первого города: "))
city1_lon = float(input("Введите долготу первого города: "))
city2_lat = float(input("Введите широту второго города: "))
city2_lon = float(input("Введите долготу второго города: "))

# Вычисление расстояния
distance = euclidean_distance(city1_lat, city1_lon, city2_lat, city2_lon)
print(f"Расстояние между городами: {distance:.2f} км")
Ответ предоставлен в фотографии ![image](https://github.com/user-attachments/assets/6d444ef0-177a-4a8f-9feb-c50aaa989f53)

