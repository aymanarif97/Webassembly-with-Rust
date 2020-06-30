# Programming Webassembly with Rust Book Notes
1. [Book Link](https://learning.oreilly.com/library/view/programming-webassembly-with/9781680506846/)


# Part I. Building a Foundation

## 1. WebAssembly Fundamentals

### Introducing WebAssembly
### Understanding WebAssembly Architecture
### Building a WebAssembly Application

## 2. Building WebAssembly Checkers
### Playing Checkers, the Board Game
### Coping with Data Structure Constraints
### Implementing Game Rules
### Moving Players
### Testing Wasm Checkers

# Part II. Interacting with JavaScript

## 3. Wading into WebAssembly with Rust

### Introducing Rust
### Installing Rust
### Building Hello WebAssembly in Rust
### Creating Rusty Checkers
### Coding the Rusty Checkers WebAssembly Interface
### Playing Rusty Checkers in JavaScript

## 4. Integrating WebAssembly with JavaScript

### Creating a Better “Hello, World”
### Building the Rogue WebAssembly Game
### Experimenting Further

## 5. Advanced JavaScript Integration with Yew

Getting Started with Yew
Building a Live Chat Application

# Part III. Working with Non-Web Hosts

## 6. Hosting Modules Outside the Browser
### How to Be a Good Host
### Interpreting WebAssembly Modules with Rust
### Building a Console Host Checkers Player

## 7. Exploring the Internet of WebAssembly Things

### Overview of the Generic Indicator Module
### Creating Indicator Modules
### Building Rust Applications for ARM Devices
### Hosting Indicator Modules on a Raspberry Pi
### Hardware Shopping List
### Endless Possibilities

## 8. Building WARoS
### An Homage to Crobots
### Designing the WARoS API
### Building the WARoS Match Engine
### Creating WebAssembly Robots
### Robots in the Cloud


# Appendix

## A1. WebAssembly and Serverless
### Serverless 101
- It strips away boiler-plate code and just deploys Business Logic which is either consumed by:
  1. RPC
  2. REST
  3. Some pub/sub mechanism

- Can be thought of as purely reactive; stripped away from onion of bolier-plate code which:
  1. Awaits an event → Performs a task → Gets out of way by deleting its deployment unit itself.
  
### Intersection of WebAssembly and Serverless
### WebAssembly in the Cloud
### Serverless WebAssembly in the Wild
### Integration with OpenFaaS
## A2. Securing WebAssembly Modules
### General Security Concerns
### Browser-Based Attack Vectors
### Signing and Encrypting WebAssembly Modules

