cmake_minimum_required(VERSION 3.16)

project(DPExamples)

include_directories(include)
add_executable(ClimbingStairs climbing_stairs.cpp)
target_compile_options(ClimbingStairs PRIVATE -g -O3 -Werror -Wall)
add_executable(HouseRobber house_robber.cpp)
target_compile_options(HouseRobber PRIVATE -g -O3 -Werror -Wall)
add_executable(GasStation gas_station.cpp)
target_compile_options(GasStation PRIVATE -g -O3 -Werror -Wall)
add_executable(TrappingWater1 trapping_water1.cpp)
target_compile_options(TrappingWater1 PRIVATE -g -O3 -Werror -Wall)
add_executable(TargetSumWays target_sum.cpp)
target_compile_options(TargetSumWays PRIVATE -g -O3 -Werror -Wall)
add_executable(MinCostTickets minimum_cost_tickets.cpp)
target_compile_options(MinCostTickets PRIVATE -g -O3 -Werror -Wall)
add_executable(MinCoinChanges minimum_coin_change.cpp)
target_compile_options(MinCoinChanges PRIVATE -g -O3 -Werror -Wall)
add_executable(MinCoinChanges2 minimum_coin_change2.cpp)
target_compile_options(MinCoinChanges2 PRIVATE -g -O3 -Werror -Wall)
add_executable(LCS1 longest_common_subsequence.cpp) 
target_compile_options(LCS1 PRIVATE -g -O3 -Werror -Wall)
add_executable(LIS1 longest_increase_subsequence.cpp) 
target_compile_options(LIS1 PRIVATE -g -O3 -Werror -Wall)
add_executable(EditDistance minimum_edit_distance.cpp) 
target_compile_options(EditDistance PRIVATE -g -O3 -Werror -Wall)
