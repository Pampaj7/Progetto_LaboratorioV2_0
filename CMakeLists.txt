cmake_minimum_required(VERSION 3.20)
project(Progetto_LaboratorioV2_0)

set(CMAKE_CXX_STANDARD 14)

add_executable(Progetto_LaboratorioV2_0 main.cpp Activities.cpp Activities.h MyApp.cpp MyApp.h MyFrame.cpp MyFrame.h Register.cpp Register.h test/ActivitiesTest.cpp test/RegisterLists.cpp test/runAllTests.cpp test/runAllTests.h)
