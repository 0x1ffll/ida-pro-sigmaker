PROC=f2mc
CONFIGS=f2mc16l.cfg f2mc16lx.cfg
ifndef NOTEAMS

endif

include ../module.mak

# MAKEDEP dependency list ------------------
$(F)ana$(O)     : $(I)auto.hpp $(I)bitrange.hpp $(I)bytes.hpp               \
                  $(I)config.hpp  $(I)diskio.hpp               \
                  $(I)entry.hpp $(I)fpro.h $(I)funcs.hpp $(I)ida.hpp        \
                  $(I)idp.hpp $(I)ieee.h $(I)kernwin.hpp $(I)lines.hpp      \
                  $(I)llong.hpp $(I)loader.hpp                 \
                   $(I)nalt.hpp $(I)name.hpp                \
                  $(I)netnode.hpp $(I)offset.hpp $(I)pro.h                  \
                  $(I)problems.hpp $(I)range.hpp $(I)segment.hpp            \
                  $(I)segregs.hpp $(I)ua.hpp $(I)xref.hpp ../idaidp.hpp     \
                  ../iohandler.hpp ana.cpp f2mc.hpp ins.hpp
$(F)emu$(O)     : $(I)auto.hpp $(I)bitrange.hpp $(I)bytes.hpp               \
                  $(I)config.hpp  $(I)diskio.hpp               \
                  $(I)entry.hpp $(I)fpro.h $(I)frame.hpp $(I)funcs.hpp      \
                  $(I)ida.hpp $(I)idp.hpp $(I)ieee.h $(I)kernwin.hpp        \
                  $(I)lines.hpp $(I)llong.hpp $(I)loader.hpp   \
                   $(I)nalt.hpp $(I)name.hpp                \
                  $(I)netnode.hpp $(I)offset.hpp $(I)pro.h                  \
                  $(I)problems.hpp $(I)range.hpp $(I)segment.hpp            \
                  $(I)segregs.hpp $(I)ua.hpp $(I)xref.hpp ../idaidp.hpp     \
                  ../iohandler.hpp emu.cpp f2mc.hpp ins.hpp
$(F)ins$(O)     : $(I)auto.hpp $(I)bitrange.hpp $(I)bytes.hpp               \
                  $(I)config.hpp  $(I)diskio.hpp               \
                  $(I)entry.hpp $(I)fpro.h $(I)funcs.hpp $(I)ida.hpp        \
                  $(I)idp.hpp $(I)ieee.h $(I)kernwin.hpp $(I)lines.hpp      \
                  $(I)llong.hpp $(I)loader.hpp                 \
                   $(I)nalt.hpp $(I)name.hpp                \
                  $(I)netnode.hpp $(I)offset.hpp $(I)pro.h                  \
                  $(I)problems.hpp $(I)range.hpp $(I)segment.hpp            \
                  $(I)segregs.hpp $(I)ua.hpp $(I)xref.hpp ../idaidp.hpp     \
                  ../iohandler.hpp f2mc.hpp ins.cpp ins.hpp
$(F)out$(O)     : $(I)auto.hpp $(I)bitrange.hpp $(I)bytes.hpp               \
                  $(I)config.hpp  $(I)diskio.hpp               \
                  $(I)entry.hpp $(I)fpro.h $(I)frame.hpp $(I)funcs.hpp      \
                  $(I)ida.hpp $(I)idp.hpp $(I)ieee.h $(I)kernwin.hpp        \
                  $(I)lines.hpp $(I)llong.hpp $(I)loader.hpp   \
                   $(I)nalt.hpp $(I)name.hpp                \
                  $(I)netnode.hpp $(I)offset.hpp $(I)pro.h                  \
                  $(I)problems.hpp $(I)range.hpp $(I)segment.hpp            \
                  $(I)segregs.hpp $(I)ua.hpp $(I)xref.hpp ../idaidp.hpp     \
                  ../iohandler.hpp f2mc.hpp ins.hpp out.cpp
$(F)reg$(O)     : $(I)auto.hpp $(I)bitrange.hpp $(I)bytes.hpp               \
                  $(I)config.hpp $(I)cvt64.hpp                 \
                  $(I)diskio.hpp $(I)entry.hpp $(I)fpro.h $(I)funcs.hpp     \
                  $(I)ida.hpp $(I)idp.hpp $(I)ieee.h $(I)kernwin.hpp        \
                  $(I)lines.hpp $(I)llong.hpp $(I)loader.hpp   \
                   $(I)nalt.hpp $(I)name.hpp                \
                  $(I)netnode.hpp $(I)offset.hpp $(I)pro.h                  \
                  $(I)problems.hpp $(I)range.hpp $(I)segment.hpp            \
                  $(I)segregs.hpp $(I)ua.hpp $(I)xref.hpp ../idaidp.hpp     \
                  ../iohandler.hpp f2mc.hpp ins.hpp reg.cpp
