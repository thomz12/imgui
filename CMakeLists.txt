cmake_minimum_required(VERSION 3.12)

project(imgui)

add_library(imgui)

include_directories(${CMAKE_CURRENT_SOURCE_DIR})

# ImGUI sources
target_sources(imgui PRIVATE
	imconfig.h
	imgui.cpp
	imgui.h
	imgui_demo.cpp
	imgui_draw.cpp
	imgui_internal.h
	imgui_tables.cpp
	imgui_widgets.cpp
	imstb_rectpack.h
	imstb_textedit.h
	imstb_truetype.h
)