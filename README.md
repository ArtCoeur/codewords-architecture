# codewords-architecture
Arch overviews of the system

# Functions / micro-services

# Events

_rename event names to 'ac.%'_

## names
* board.new
* word.new
* cell.new

## format
  
   {
      board: %board-id%,
      name: %event-name%,
      data: {
          body: %data%,
          type: %mime-type%
      }
    }
     
# Process flow
