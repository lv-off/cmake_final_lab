cmake_minimum_required(VERSION 3.15) 
									 
									 

set(PROJECT_NAME Cat_0.1)				 		 
project("${PROJECT_NAME}")


set(CMAKE_CXX_STANDARD 17)			
set(CMAKE_CXX_EXTENSIONS OFF)
set(CMAKE_CXX_STANDARD_REQUIRED TRUE)

include_directories("inc/")

add_executable("${PROJECT_NAME}" main.cpp
				 engine.cpp
				 engine.h
				 gameobjects.h
				 gameobjects.cpp
				 input.cpp
				 draw.cpp
				 update.cpp
				 tree.png
				 soloplayer.png
				 player.png
				 house.png
				 end.png
				 emptytree.png
				 meow.ogg
				 newemptytree.png
				 player.png
				 shop.png
				 background.jpg
   				 cat.png
)