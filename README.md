Stichting Full Reserve
======================

Website van Stichting Full Reserve (readonly archief)

Archiveer log
-------------

	# 2020-07-20 Initiele versie van dit archief
	# Downloaden
	wget --recursive --adjust-extension http\://fullreserve.nl # output in INPUT_LOG
	# Testen
	cd fullreserve.nl; python3 -m http.server
	# wget plakt querystring aan bestandsnaam vast. Deze handmatig verwijderen...
	find . -regex '.*[?].*'
	# handmatig html-extentie toevoegen aan links in editor met search/replace (index.html hoeft niet)
	find . -name "*.html"
	# als laatste de inhoud van de map `fullreserve.nl` verplaatst naar de root van repo, en de lege map verwijderen
