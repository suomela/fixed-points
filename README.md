# Periodic points in round elimination

Round elimination is a function "re" that turns a locally verifiable graph problem P into a new graph problem P' = re(P).

Sometimes round elimination leads to a fixed point, with P = re(P), or a periodic point, e.g., P = re(re(P)). Whenever this happens to a nontrivial problem P, we immediately get a lower bound for the distributed complexity of P. This repository is a catalog of such problems P.

Directory A-B-L:

- active degree A
- passive degree B
- L labels
- these problems are periodic points

Directory A-B-L-distance-D:

- active degree A
- passive degree B
- L labels
- D steps of round elimination leads to a periodic point


## References

- Round Eliminator tool: https://github.com/olidennis/round-eliminator


## Contact

- Jukka Suomela — https://jukkasuomela.fi/


## Contributors

- Alkida Balliu
- Dennis Olivetti
- Jukka Suomela


## License

The content in this repository is licensed under the Creative Commons Attribution 4.0 International (CC BY 4.0) license:
https://creativecommons.org/licenses/by-sa/4.0/

