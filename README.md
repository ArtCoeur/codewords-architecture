# codewords-architecture
Arch overviews of the system

# Functions / micro-services

# Events

_rename event names to 'ac.%'_

## names
* board.new
* word.new
* word.solved
* cell.new

## format
  
```
   {
      board: %board-id%,
      name: %event-name%,
      data: {
          body: %data%,
          type: %mime-type%
      }
   }
```

# Process flow


# Problems

* Stores state of boards in memory in a function - this disallows scaling that function/service

