#--------------------------------------------------------------
#               OpenLinux
#
#--------------------------------------------------------------

.PHONY: default
default:
	$(MAKE) TemplateMethod

#---------------------
# Include definition
#---------------------
INC_DIR=-I ./ 

#---------------------
# Source code files
#---------------------
LOCAL_SRC_FILES_TemplateMethod = main.cpp

# Library definition
#---------------------

#---------------------
# Compilation options
#---------------------
LOCAL_C_FLAGS += -std=c++11



TemplateMethod:
	g++  $(LOCAL_SRC_FILES_TemplateMethod) -s -o $@ $(LOCAL_C_FLAGS)

clean:
	rm -rf  TemplateMethod *.o
