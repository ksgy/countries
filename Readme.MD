Countries
=========

A small js object to deal with country codes and names.
	countries.getA2('HUN')
	// "HU"

	countries.getA2('hungary')
	// "HU"

	countries.getA2('348')
	// "HU"

	countries.getA3('348')
	// "HUN"

	countries.getA3('HU')
	// "HUN"

	countries.getA3('HUNGARY')
	// "HUN"

	countries.getNum('HUNGARY')
	// "348"

	countries.getNum('HU')
	// "348"

	countries.getNum('HUN')
	// "348"

	countries.getCountry('HUN')
	// "HUNGARY"

	countries.getCountry('HU')
	// "HUNGARY"

	countries.getCountry('348')
	// "HUNGARY"


