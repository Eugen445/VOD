LFLAG=-L/usr/lib64/mysql -lmysqlclient -ljsoncpp -lpthread
main:main.cpp db.hpp
	g++ $^ -o $@ -std=c++11 $(LFLAG) 
