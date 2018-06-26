# K85-Protocol
GIGABYTE K85 protocol reverse engineering

## Set color
| Byte | Description / Value |
|------|---------------------|
| 0-3  | 3f 08 01 c8         |
| 4    | Red color value     |
| 5    | Green color value   |
| 6    | Blue color value    |
| 7-8  | 08 01               |
| 9-63 | Zeros               |

## Get firmware version
| Byte | Description / Value |
|------|---------------------|
| 0-6  | 3f 04 56 45 52 21   |
| 7-63 | Zeros               |