add_executable( XOR_Circuit XOR.cpp )
target_link_libraries( XOR_Circuit BooleanCircuitGenerator )

# ======

add_executable( AND_Circuit AND.cpp )
target_link_libraries( AND_Circuit BooleanCircuitGenerator )

# ======

add_executable( INV_Circuit INV.cpp )
target_link_libraries( INV_Circuit BooleanCircuitGenerator )

# ======

add_executable( OR_Circuit OR.cpp )
target_link_libraries( OR_Circuit BooleanCircuitGenerator )

# ======

add_executable( Addition_Circuit Addition.cpp )
target_link_libraries( Addition_Circuit BooleanCircuitGenerator )
