
# Initialize AC: AC_INIT( package_name, version, bug_report_address )
AC_INIT([my_program], [0.1])

#Initiailize Automake
AM_INIT_AUTOMAKE

# AM stands for Automake, AC for autoconfigure


# We use libraries
AC_PROG_RANLIB

# Let's check for a c++ compiler
AC_LANG(C++)

# Let's set a c++ compiler
AC_PROG_CXX

# Let's specify where th makefiles should be produced. 
# Thes are the same locations as your Makefile.in's. but namesd as Makefile only
# We need to do this because both autoconf and automake read this file and produce makefiles from list.

AC_CONFIG_FILES([Makefile my_inc/Makefile src/Makefile])


#Finally, produce "configure" script
AC_OUTPUT