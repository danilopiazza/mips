# Instructions append

## Registers

| Register | Usage     | Type    | Description                                            |
| -------- | --------- | ------- | ------------------------------------------------------ |
| `$a0`    | input     | address | first color as null-terminated string                  |
| `$a1`    | input     | address | second color as null-terminated string                 |
| `$a2`    | input     | address | third color as null-terminated string (possibly empty) |
| `$v0`    | input     | integer | resistor value                                         |
| `$t0-9`  | temporary | any     | for temporary storage                                  |
