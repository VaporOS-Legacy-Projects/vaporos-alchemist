# VaporOS-mod
This is the new format of VaporOS, a Stephenson's Rocket mod.

To build VaporOS you'll need to first clone Stephenson's rocket's git repo:

    git clone --depth=1 https://github.com/steamos-community/stephensons-rocket.git --branch alchemist

After you've done that move into the newly created directory and clone this repo like this:

    cd stephensons-rocket
    git clone https://github.com/sharkwouter/vaporos-mod.git

Now you can build VaporOS like this:

    cd ..
    ./gen.sh -n "VaporOS" vaporos-mod

That's it, good luck!

VaporOS still has all the features found in the last version, but now you also get support for older hardware like found in Stephenson's Rocket. You'll also get new additions to Stephenson's Rocket through updates.
