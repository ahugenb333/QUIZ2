all:
	collegemain.o	college.o	course.o

collegemain.o:	collegemain.cc
	g++	-Wall	-g	-c	collegemain.cc	-o	collegemain.o

college.o:	college.cc
	g++	-Wall	-g	-c	college.cc	-o	college.o

course.o:	course.cc
	g++	-Wall	-g	-c	course.cc	-o	course.o

clean:
	rm	college.o	course.o	collegemain.o	a.out