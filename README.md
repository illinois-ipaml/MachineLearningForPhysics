# Intrumentation Physics Applications of Machine Learning (PHYS 503)

All instructions, including creating a simple book, and referenes can be found at https://jupyterbook.org

## Create a template book
`jupyter-book create IntroComputationalPhysics`

## Build the book to make the html
`cd IntroComputationalPhysics`
### For solutions version
`jupyter-book build --config _config.yml --toc _toc_wSoln.yml ./`
### For student version
`jupyter-book build --config _config.yml --toc _toc.yml ./`

## Clean the build
`jupyter-book clean ./`

## Copy to illinois course server (MacOS with course server mounted)
```
cd ~/repos/PHYS246/IntroComputationalPhysics`
cp -rp ./_build/html/* /Volumes/phys246/fa2022/secure/html/
```
