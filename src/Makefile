.PHONY: clean all

all: scene

Trees.o: Trees.cpp
	g++ -o Trees.o -c Trees.cpp

Textures.o: Textures.cpp
	g++ -o Textures.o -c Textures.cpp

Paluka-Infinite_Scene.o: Paluka-Infinite_Scene.cpp
	g++ -o Paluka-Infinite_Scene.o -c Paluka-Infinite_Scene.cpp
	
scene: Trees.o Textures.o Paluka-Infinite_Scene.o
	g++ -o scene Trees.o Textures.o Paluka-Infinite_Scene.o -lGL -lGLU -lglut

clean:
	rm -rf scene
	rm -rf *.o	
