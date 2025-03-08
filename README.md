Rust Learning - Day 1

Introduction

This repository contains my first Rust program from Day 1 of learning Rust. The program demonstrates basic conditional statements using boolean variables.

Code Overview

The program initializes two boolean variables:

is_male (set to false)

is_adult (set to false)

It then checks different conditions using if, else if, and else statements to print appropriate messages based on the values of is_male and is_adult.

Code

fn main() {
    let is_male: bool = false;
    let is_adult: bool = false;
    
    if is_male && is_adult {
        print!("He is male and adult");
    } else if !is_male && is_adult {
        print!("He is not male but adult");
    } else {
        print!("He is not male and adult");
    }
}
How to Run

Install Rust from rust-lang.org

Save the code in a file, e.g., main.rs

Open a terminal and navigate to the directory containing main.rs

Run the program using:

rustc main.rs && ./main

Learning Outcome

Declaring and using boolean variables in Rust

Implementing conditional statements (if, else if, else)

Basic syntax and structure of a Rust program

Future Learning

Exploring user input

Implementing loops and functions

Working with Rust's data types and ownership model

Contributions

Feel free to fork this repository, suggest improvements, or add new Rust exercises!

License

This project is open-source and available under the MIT License.
