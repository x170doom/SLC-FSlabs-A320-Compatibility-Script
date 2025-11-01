this script mirrors the LVARS from the a320 to the correct FSUIPC offsets so that SLC can see the state of doors, lights and seatbelt signs
to install simply drop into "Documents>Prepar3D V5/6 add-ons>FSUIPC 6" then either bind a key in FSUIPC to the function "lua fslabsA320slc" or open your fsuipc.ini file and add a new section called "[Auto]" with the body text "1=lua fslabsA320slc"
the script shoulnt intefere with other aircraft as it is set to auto-terminate if it detects that the aircraft loaded isn't an fslabs a320
