This repository contains a web page with a detailed visualization of an exploit for vulnerability [CVE-2021-32471](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-32471)

This exploit demonstrates how carefully crafted input for a Turing machine (TM) which itself is simulated using Marvin Minsky's universal Turing machine (UTM) in fact entraps the UTM not to run the given TM (as intended) but instead to execute another TM hidden in the mentioned input.

Marvin Minsky's UTM is presented in "Minsky, Computation: Finite and infinite machines, 1967, Chapter 7".

The exploit is described in detail in [Pontus Johnson](https://www.kth.se/profile/pontusj)'s paper [Intrinsic Propensity for Vulnerability in Computers? Arbitrary Code Execution in the Universal Turing Machine](https://arxiv.org/abs/2105.02124) from 2021.

A Python implementation of UTM and exploit can be found at https://github.com/intrinsic-propensity/turing-machine

For an alternative re-implementation of the vulnerable Minsky Turing machine, check out [Andreas Rozek's specification](https://github.com/rozek/Universal-Turing-Machine) for [Martín Ugarte's Turing machine simulator](https://turingmachinesimulator.com).

## License ##

[MIT License](LICENSE)
