# ICoCo SWIG Baltik

This project defines an ICoCo SWIG wrapper that can be used for any BALTIK project based on the TRUST platform 🔥🔥🔥.

All you have to do is to clone this git repository and modify the **dependencies** in the project.cfg file so that you can add in it your desired project.

By default, the application used is the balti TrioCFD (see project.cfg). Do not hesitate to modify this behavior and adapt it for your own BALTIK 🍻🍻🍻.

# How to start

```bash
# Clone the repo
git clone git@github.com:eliesaikali/swig_baltik.git

# Move to the cloned folder
cd swig_baltik

# Initialize TRUST environment
source [YOUR_PATH_TO_TRUST]/env_TRUST.sh

# Build the project
baltik_build_configure -execute && make swig

# Initialize the  python's environment (MEDCoupling, swig and ICoCo python)
source ./env_for_python.sh
```

Enjoy TRUST 🍻🍻
