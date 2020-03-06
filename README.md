# mesa-13.0.4_V3_source_by_Griggorii_tutorial_patent_compilation_omx , gallium , nine , pipe
mesa-13.0.4 , V3 , source_by , Griggorii_tutorial , patent , compilation , omx , gallium , nine , pipe

Source readme https://github.com/Griggorii/mesa-13.0.4_V2_source_by_Griggorii_tutorial_patent_compilation 

Download my portage tool https://github.com/Griggorii/mesa-19.0.1_source_griggorii_mit_patent_llvm-7

-------------------------------------------------

$ sudo apt update && sudo apt --reinstall install libomxil-bellagio-dev libwayland-egl-backend-dev libunwind-dev libegl1-mesa-dev mesa-common-dev libgles2-mesa-dev libosmesa6-dev libglu1-mesa-dev valgrind valgrind-dbg libxvmc-dev libxcb-dri2-0-dev libxcb-dri3-dev libxcb-glx0-dev libxcb-randr0-dev libxcb-render0-dev libxcb-shape0-dev libxcb-sync-dev libxcb-xfixes0-dev libxcb1-dev libxine2-dev libxatracker-dev -y && sudo apt libmesa-dev -y && sudo apt install libd3dadapter9-mesa-dev -y

-------------------------------------------------------------------------
$ sudo apt update && sudo apt --reinstall install libgcrypt20-dev , libxcb-dri3-dev , libxcb-present-dev , python-mako , libxshmfence-dev , libxext-dev , libxdamage-dev , libx11-xcb-dev , libxcb-glx0-dev , libxcb-dri2-0-dev , libexpat1-dev , libxxf86vm-dev , libxvmc-dev , libomxil-bellagio-dev , libva-dev , libclc-dev , libdrm-dev , libegl-dev , libegl1-mesa-dev , libgbm-dev , libgl-dev , libgl1-mesa-dev , libgles-dev , libgles2-mesa-dev , libglvnd-dev , libglx-dev , libopengl-dev , libosmesa6-dev , libpthread-stubs0-dev , libvdpau-dev , libvkd3d-dev , libvkd3d-utils1 , libvulkan-dev , libx11-dev , libxau-dev , libxcb1-dev , libxdmcp-dev , mesa-common-dev , mesa-opencl-icd , nvidia-cg-dev

$ sudo cp r300_pci_ids.h  /usr/include && sudo cp xlocale.h /usr/include

New command terminal: llvm-3.8

$ ./autogen.sh

$ ./configure --prefix=/usr --includedir=${prefix}/include --mandir=${prefix}/share/man --infodir=${prefix}/share/info --sysconfdir=/etc --localstatedir=/var --libdir=${prefix}/lib/x86_64-linux-gnu --libexecdir=${prefix}/lib/x86_64-linux-gnu --enable-dependency-tracking --enable-silent-rules --enable-dri --with-dri-driverdir=/usr/lib/x86_64-linux-gnu/dri --with-dri-searchpath=/usr/lib/x86_64-linux-gnu/dri:\$${ORIGIN}/dri:/usr/lib/dri --enable-osmesa --enable-glx-tls --enable-shared-glapi --enable-texture-float --enable-xvmc --enable-omx --enable-driglx-direct --enable-dri3 --with-egl-platforms=x11 --enable-xa --enable-opencl --enable-opencl-icd --enable-gallium-llvm ac_cv_path_LLVM_CONFIG=llvm-config-3.8 --enable-vdpau --enable-va --enable-gles1 --enable-gles2 --no-create --no-recursion

---------------------------------------------------------------------------------------------------------------

Example если llvm 9 --enable-gallium-llvm ac_cv_path_LLVM_CONFIG=llvm-config-9

$ ./autogen.sh

$ ./configure --prefix=/usr --includedir=${prefix}/include --mandir=${prefix}/share/man --infodir=${prefix}/share/info --sysconfdir=/etc --localstatedir=/var --libdir=${prefix}/lib/x86_64-linux-gnu --libexecdir=${prefix}/lib/x86_64-linux-gnu --enable-dependency-tracking --enable-silent-rules --enable-dri --with-dri-driverdir=/usr/lib/x86_64-linux-gnu/dri --with-dri-searchpath=/usr/lib/x86_64-linux-gnu/dri:\$${ORIGIN}/dri:/usr/lib/dri --enable-osmesa --enable-glx-tls --enable-shared-glapi --enable-texture-float --enable-xvmc --enable-omx --enable-driglx-direct --enable-dri3 --with-egl-platforms=x11 --enable-xa --enable-opencl --enable-opencl-icd --enable-gallium-llvm ac_cv_path_LLVM_CONFIG=llvm-config-9 --enable-vdpau --enable-va --enable-gles1 --enable-gles2 --no-create --no-recursion



Ремонт графического стека в мировом масштабе , знайте что графический стек на сегодня сломан я постараюсь в скором времени посмотреть что можно ещё сделать что бы вернуть стек по производительности на уровень графического стека который был ранее в убунту 16.04 еще до того времени как образовались всякие псевдо вулканы.
