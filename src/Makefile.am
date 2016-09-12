# Our binary is produced here
bin_PROGRAMS = main
main_SOURCES = main.cpp


# main binary will be installe into the default directory

# noinst_: assures that this library is not installed to the user's computer.
# libBLAH.a is a *nix convention. If you noticed, we replaced . with _ in SOURCES line.
noinst_LIBRARIES = libhelper.a
libhelper_a_SOURCES = helper.cpp

#LDADD specifies which libraries to compile into "main". We have two libraries. 
#libhelper comes from this directory and libmayadd comes from my_inc directory.
main_LDADD = libhelper.a my_inc/libmyadd.a