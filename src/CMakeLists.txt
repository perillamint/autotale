file(GLOB_RECURSE autotale_SOURCES "*.c")
file(GLOB_RECURSE autotale_HEADERS "*.h")

find_package(OpenCV REQUIRED)
find_package(Threads)

add_executable(autotale ${autotale_SOURCES})
