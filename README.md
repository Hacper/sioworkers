# INSTALLATION

bash skladniki.sh - requirements
python setup.py install - installation
configuration in config folder

# TESTS

### to run all tests ###
`tox`
in main directory

### to run twisted tests (python2) ###
run:
trial sio.sioworkersd.twisted_t
in the directory of installation

### to run twisted tests (python3) ###
run:
trial sio/sioworkersd/twisted_t
in the directory of installation
