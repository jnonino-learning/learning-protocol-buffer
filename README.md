# Learning Protocol Buffer

Based on tutorial in https://developers.google.com/protocol-buffers/

## Installation

MacOS

        brew install protobuf

## Compiling Protocol Buffers

        protoc -I=. --python_out=. addressbook.proto

## Writing on Address Book

        python write.py ADDRESS_BOOK
        
## Read an Address Book

        python read.py ADDRESS_BOOK