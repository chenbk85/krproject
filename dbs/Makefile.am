SUBDIRS  = . dbs

noinst_LTLIBRARIES     = libdbsbas.la 
libdbsbas_la_SOURCES   = dbs_basopr.h \
                         dbs_basopr.c  
libdbsbas_la_CPPFLAGS  = 
libdbsbas_la_LDFLAGS   = -lodbc 
libdbsbas_la_LIBADD    = 

noinst_PROGRAMS        = rapodbc
rapodbc_SOURCES        = rapodbc.c
rapodbc_CPPFLAGS       = 
rapodbc_LDFLAGS        = -lodbc 
#rapodbc_CPPFLAGS       = @ODBC_INCLUDE@
#rapodbc_LDFLAGS        = -lodbc @ODBC_LDFLAGS@ @ODBC_LIBS@
