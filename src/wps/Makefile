CC=gcc
INC=-I../utils -I ../

all: wps_attr_build.o wps_attr_parse.o wps_attr_process.o wps.o wps_common.o wps_dev_attr.o wps_enrollee.o wps_registrar.o wps_ufd.o

wps_attr_build.o:
	$(CC) $(INC) wps_attr_build.c -c

wps_attr_parse.o:
	$(CC) $(INC) wps_attr_parse.c -c

wps_attr_process.o:
	$(CC) $(INC) wps_attr_process.c -c

wps.o:
	$(CC) $(INC) wps.c -c

wps_common.o:
	$(CC) $(INC) wps_common.c -c

wps_dev_attr.o:
	$(CC) $(INC) wps_dev_attr.c -c

wps_enrollee.o:
	$(CC) $(INC) wps_enrollee.c -c

wps_registrar.o:
	$(CC) $(INC) wps_registrar.c -c

wps_ufd.o:
	$(CC) $(INC) wps_ufd.c -c

clean:
	rm -f *.o
