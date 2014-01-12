REMOTE_URL = hostgator:domains/web-cpan/public_html/downloads
DEST = dest

RSYNC = rsync -a --progress -v --inplace

all:

download:
	$(RSYNC) $(REMOTE_URL)/ $(DEST)

upload:
	$(RSYNC) $(DEST)/ $(REMOTE_URL)
