cmake_minimum_required(VERSION 3.21)
project(HugeNumberCalculator_release_stub C)

set(CMAKE_C_STANDARD 11)

include_directories(HugeNumberCalculator/DataTypes)
include_directories(HugeNumberCalculator/IHMHugeNumber)
include_directories(HugeNumberCalculator/UseHugeNumber/Operator)
include_directories(HugeNumberCalculator/UseHugeNumber/Type)

add_executable(HugeNumberCalculator_release_stub
        HugeNumberCalculator/DataTypes/DoublyLinkedList.c
        HugeNumberCalculator/DataTypes/DoublyLinkedList.h
        HugeNumberCalculator/IHMHugeNumber/ScanHugeNumber.c
        HugeNumberCalculator/IHMHugeNumber/ScanHugeNumber.h
        HugeNumberCalculator/IHMHugeNumber/ShowHugeNumber.c
        HugeNumberCalculator/IHMHugeNumber/ShowHugeNumber.h
        HugeNumberCalculator/UseHugeNumber/Operator/HugeFloatOperator.c
        HugeNumberCalculator/UseHugeNumber/Operator/HugeFloatOperator.h
        HugeNumberCalculator/UseHugeNumber/Operator/HugeIntOperator.c
        HugeNumberCalculator/UseHugeNumber/Operator/HugeIntOperator.h
        HugeNumberCalculator/UseHugeNumber/Operator/HugeUnsignedIntOperator.c
        HugeNumberCalculator/UseHugeNumber/Operator/HugeUnsignedIntOperator.h
        HugeNumberCalculator/UseHugeNumber/Type/HugeFloat.c
        HugeNumberCalculator/UseHugeNumber/Type/HugeFloat.h
        HugeNumberCalculator/UseHugeNumber/Type/HugeInt.c
        HugeNumberCalculator/UseHugeNumber/Type/HugeInt.h
        HugeNumberCalculator/UseHugeNumber/Type/HugeUnsignedInt.c
        HugeNumberCalculator/UseHugeNumber/Type/HugeUnsignedInt.h
        HugeNumberCalculator/main.c)
