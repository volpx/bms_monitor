# Segment board

## Monitor selecction

### Requisites

- 12 cells
- isospi stackable
- balancing
- serial commandable
- isolation transformer
    - L primary > 60uH
    - L leakage < 2.5uH


### Differences

- LTC6803
    - -3 -4
        - kelvin connection on C0
    - -3
        stackable
    - -4
        stackable with external isolation interface
- LTC6804 ->
- LTC6811 pin compatible upgrade of LTC6804
    - see upgrade section
        - nothing worth noting
    - isoSPI
    - Also normal spi connection
    - -1
        - isoSPI A and B
        - deisy chaining
            ------> A|LTC|B ------> A|LTC|B ------->
    - -2
        - isoSPI A
        - address
            -------> A|LTC a:1
            -------> A|LTC a:2

## Components

- EPF8119S for LTC6803
- CMC on same board connection
    - ACT45B-101-2P-TL003
- iso transformer + CMC
    - TG110-AE050N5 double
    -
    

