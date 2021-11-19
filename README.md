# Overcooked Human-AI Experiment Demo

## To build the experiment application (an npm app)
Make sure that the [overcooked-js](https://github.com/markkho/overcooked-js) package is linked as `overcooked`.

Go to `static/js/task/` and run:

```
npm install
npm link overcooked
npm run build
```

## How to run psiturk app locally
- Set up a virtual environment with [psiturk](https://psiturk.org/)
(python 3.8+). E.g., with anaconda, run
```
conda create -n psiturk_test_env python=3.8
conda activate psiturk_test_env
pip install psiturk
```
- Go into the main folder and run `psiturk`.
- Start the server, `server on`
- Start a debug session, `debug`.

For additional information see the psiturk website.

## Hosting the experiments for MTurk

Refer to the instructions on the [psiturk](https://psiturk.readthedocs.io/) website.
