# huawei2019
华为2019评判器开源

answer.txt格式为提交答案格式，但是注意不能有注释。
错误样例：
#****
(carId,plantime,route)
(carId,plantime,route)
(carId,plantime,route)
正例:
(carId,plantime,route)
(carId,plantime,route)
(carId,plantime,route)


运行
python3 simulator.py ../config_11/car.txt ../config_11/road.txt ../config_11/cross.txt ../config_11/answer.txt


class visualization 为可视化模块，输出图片位置在visualization.savePath。
class simulation 中有调用visualization。可注释simulation.simulate()中的 visualize.drawMap()以提高程序运行速度。
