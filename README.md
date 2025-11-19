# Homework.2
1. Компіляція main.cpp у об'єктний файл
 	g++ -c main.cpp -o main.o
3. Компіляція std.cpp у об'єктний файл
  g++ -c std.cpp -o std.o
4. Лінкування об'єктних файлів у виконувану програму
  g++ main.o std.o -o my_program
