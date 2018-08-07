# Bootstrap Desktop

This is the process by which I initially kit out an Ubuntu-based computer.

It's designed to be run as soon after a fresh install as possible. The only prerequisites are git and an Internet connection.

## Steps

1. Install Ubuntu 18.04 (any major flavor should work).
2. Login and open your terminal application.
3. Install git. (`sudo apt install git`)
4. Checkout this repository.
5. Run the bootstrap script (`sudo ./bootstrap.sh desktop`)

Note that in step 5, you can pass either "desktop" (for a full desktop experience) or "work" (for an experience tailored to work/client machines).

You will need to override the `primary_user` var with whatever your username is.