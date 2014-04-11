Rapiro firmware
===============
##The difference between original  firmware and  this  firmware. 
 1. Motion No. is 2 digits #Mnn. (evilbluechickens-san ) 
 2. Added Servo off command #H. (evilbluechickens-san )
 3. Added Read Analog port. #An
 4. Added Version Info. #V
 5. Motion data moved to Flash.
 6. User trim data was separated into include file.

|       |Org    | This |
|-------|-------|------|
|STOP   | #M0   | #M00 |
|Foward | #M1   | #M01 |
|Back   | #M2   | #M02 |
|Left   | #M4   | #M04 |
|Right  | #M3   | #M03 |
|OFF    | -     | #H   |
|Analog | -     | #A6  |
|C      | -     | #C   |
|Q      | -     | #Q   |
|5      | #M5   | #M05 |
|M6     | #M6   | #M06 |
|M7     | #M7   | #M07 |
|M8     | #M8   | #M08 |
|M9     | #M9   | #M09 |
|M10    | -     | #M10 |
