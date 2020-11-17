cmake_minimum_required(VERSION 3.16)
project(geofences)

set(CMAKE_CXX_STANDARD 17)

add_executable(geofences main.cpp geofenceEntities/Placemarks/placemark.cpp geofenceEntities/Placemarks/placemark.h geofenceEntities/Placemarks/road.cpp geofenceEntities/Placemarks/road.h geofenceEntities/Placemarks/polygon.cpp geofenceEntities/Placemarks/polygon.h geofenceEntities/sector.cpp geofenceEntities/sector.h geofenceEntities/point.cpp geofenceEntities/point.h storage/reader.cpp storage/reader.h storage/writer.cpp storage/writer.h storage/fileSystem/reader.cpp storage/fileSystem/reader.h storage/fileSystem/writer.cpp storage/fileSystem/writer.h placemarkParser.cpp placemarkParser.h treeBuilder.cpp treeBuilder.h pointFinder.cpp pointFinder.h)