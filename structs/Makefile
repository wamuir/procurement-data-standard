XSLTPROC=	xsltproc
SCHEMA	=	../schema.xsd
GEN_GO	=	go/structs.go

all: $(GEN_GO)

%.go: %.xslt $(SCHEMA)
	$(XSLTPROC) -o $@ $^
