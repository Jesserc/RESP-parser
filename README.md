# Minimal RESP Parser for Redis

## Overview

This is a basic implementation of a RESP (Redis Serialization Protocol) parser in Go. The parser is designed to handle RESP commands and bulk strings only. It does not cover the full Redis serialization protocol.

## Features

- Parse RESP commands from a buffered reader
- Extract and return command and arguments as a slice
- Basic support for RESP array of bulk strings
