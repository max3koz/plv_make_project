Project Setup
===============

To setup and install this project, please follow the instructions below:

Initialize Autotools:

```
aclocal
autoconf
```

Add Missing Automake Files:

```
automake
```

Configure the Project:

```
./configure
```

Build the Project:

```
make
```

Install the Project:

```
sudo make install
```

Clean All Build Files: 
If you need to remove all build artifacts and delete the binary file 
from /usr/local/bin/ and header file from /usr/local/include/ 
installed by this program in the system:

```
sudo make clean-all
```

