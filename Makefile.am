DB2MAN = docbook-to-man
RM = rm

bin_PROGRAMS = hellocross
hellocross_SOURCES = hellocross.c
man1_MANS = hellocross.1

hellocross.1: hellocross.sgml
	$(DB2MAN) $< >$@

clean-local:
	-$(RM) -f $(man1_MANS)
