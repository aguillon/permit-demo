# Permit demo

A quick technical demo of the [Permit pattern (TZIP
17)](https://tzip.tezosagora.org/proposal/tzip-17/). See [permit-demo.ipynb](./permit-demo.ipynb).

To reproduce, clone the repository with the `--recurse-submodules` option to get the Ligo libraries.
The notebook is written for a local network (e.g., with Flextesa) but can run on Ghostnet by
changing the address of the RPC node.

The notebook requires recent versions of PyTezos and Jupyter (see `requirements.txt`) as well as
the Ligo compiler, available as a `ligo` command.
