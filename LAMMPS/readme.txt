1. Both files for particle-wall contact and particle-particle contact is modified
2. Normal spring stiffness expression for particle-wall collision is modified in the file "fix_wall_gran.cpp" at line 1149 and modified stiffness is used to calculate normal spring force at line 1199
3. Normal spring stiffness expression for inter-particle collision is modified in the file "pair_granular.cpp" at line 1023, where the correction is implemented at line 1535
