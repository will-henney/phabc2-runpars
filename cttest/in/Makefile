###
### Rules for shipping the parameter files around
###

TARGETDIR=Fabio/C2Ray/runs/cttest/in

all: ship2robbie ship2pinga ship2kanbalam

ship2robbie:
	rsync -avzP *.pars Makefile \
              robbie:/fs/robbie/other0/will/$(TARGETDIR)

ship2pinga:
	rsync -avzP *.pars Makefile \
              pinga:/fs/pinga/other0/will/$(TARGETDIR)

ship2kanbalam:
	rsync -avzP *.pars Makefile \
              kanbalam:/global/home/whenney_g/whenney/$(TARGETDIR)
