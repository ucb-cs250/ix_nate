# ix_nate
Nate's interconnect

Designs for connection boxes on very rich vertical wires

Custom layout of a small transmission gate is in "transmission_gate/alpha/transgate.mag". Extractions are in transgate.ext and transgate.spice.

Methodology for building: start with a single diffusion and a single polysilicon gate; then expand everything to meet critical dimensions through liberal application of the "drc why" command.

Actual used transmission gate is in "transmission_gate/from_inv"; nwell and metal1 positioning was copied from the size-2 skywater high density inverter, and necessary LEF and GDS properties were added back.
