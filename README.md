# Rust Port Scanner

## Description

This is just a simple port scanner command line application written in Rust.
This is not particularly good or efficient, but it does have concurrency.
This was done as a beginner project, trying to learn Rust and Networking.

## Usage

Compile to file.
Run the file for further instructions.

Then run the file to enter interactive commandline
Supported arguments are:

<ol>
  <li>target: Required, IP Address to scan</li>
  <li>--concurrency/-c: Amount of concurrency</li>
  <li>--verbose/-v: Whether to show more output</li>
  <li>--full/-full: Scan all 65535 ports</li>
  <li>--timeout/-t: Change the timeout time in ms</li>
</ol>
