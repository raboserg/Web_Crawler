# -*- makefile -*-
#----------------------------------------------------------------------------
#       GNU ACE Workspace
#
# 
#
# This file was generated by MPC.  Any changes made directly to
# this file will be lost the next time it is generated.
#
# MPC Command:
# D:\library\ACE_TAO\ACE\bin\mwc.pl -type gnuace ../ACE.mwc
#
#----------------------------------------------------------------------------

MAKEFILE = GNUmakefile

ifeq ($(findstring k,$(MAKEFLAGS)),k)
  KEEP_GOING = -
endif

include $(ACE_ROOT)/include/makeinclude/macros.GNU

all: Web_Crawler

depend: Web_Crawler-depend

REMAINING_TARGETS := $(filter-out all depend,$(TARGETS_NESTED:.nested=)) $(CUSTOM_TARGETS)
.PHONY: $(REMAINING_TARGETS)

$(REMAINING_TARGETS):
	$(KEEP_GOING)@$(MAKE) -f GNUmakefile.Web_Crawler $(@)

.PHONY: Web_Crawler
Web_Crawler:
	$(KEEP_GOING)@$(MAKE) -f GNUmakefile.Web_Crawler all

.PHONY: Web_Crawler-depend
Web_Crawler-depend:
	$(KEEP_GOING)@$(MAKE) -f GNUmakefile.Web_Crawler depend

project_name_list:
	@echo Web_Crawler
