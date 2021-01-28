
SUBDIRS = finter

bin_PROGRAMS = merge_files_for_globus.out

AM_CXXFLAGS = -I$(srcdir)/finter -I$(srcdir)/finter/include $(BOOST_CPPFLAGS) -ggdb -Wall -std=c++17

merge_files_for_globus_out_SOURCES = merge_files_for_globus/main.cc
merge_files_for_globus_out_LDADD = $(BOOST_LDFLAGS) finter/lib/libfinter.la -lz -lbz2
dist_doc_DATA = README
ACLOCAL_AMFLAGS = -I m4
