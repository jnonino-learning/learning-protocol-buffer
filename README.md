# Learning Protocol Buffer

[![](https://img.shields.io/github/license/jnonino/learning-protocol-buffer)](https://github.com/jnonino/learning-protocol-buffer)
[![](https://img.shields.io/github/issues/jnonino/learning-protocol-buffer)](https://github.com/jnonino/learning-protocol-buffer)
[![](https://img.shields.io/github/issues-closed/jnonino/learning-protocol-buffer)](https://github.com/jnonino/learning-protocol-buffer)
[![](https://img.shields.io/github/languages/code-size/jnonino/learning-protocol-buffer)](https://github.com/jnonino/learning-protocol-buffer)
[![](https://img.shields.io/github/repo-size/jnonino/learning-protocol-buffer)](https://github.com/jnonino/learning-protocol-buffer)

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
