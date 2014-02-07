1) Copy tree in OmniROM  to /device directory
2) Run:
    . /build/envsetup.sh
    lunch omni_front-eng (for U9500 device) or lunch omni_viva-eng (for U9200 device)
    make -j5 recoveryimage (5 - number of processors plus one)
