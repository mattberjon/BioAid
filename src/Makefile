# Makefile for Bioaid project
#
# author: matthieu berjon
# license: see the README file of the project

CXX = g++
CXXFLAGS = -g -Wall
LIBS = -lboost_thread -lboost_system -lpthread
OBJS = main.o
TARGET = bioaid

all: $(OBJS)
	$(CXX) $(CXXFLAGS) -o $(TARGET) $(OBJS) $(LIBS)

clean: rm $(TARGET) $(OBJS)

