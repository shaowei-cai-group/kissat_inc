all:
	$(MAKE) -C "/home/chenzh/solvers/L_SAT22/kissat_inc/sources/build"
kissat:
	$(MAKE) -C "/home/chenzh/solvers/L_SAT22/kissat_inc/sources/build" kissat
tissat:
	$(MAKE) -C "/home/chenzh/solvers/L_SAT22/kissat_inc/sources/build" tissat
clean:
	rm -f "/home/chenzh/solvers/L_SAT22/kissat_inc/sources"/makefile
	-$(MAKE) -C "/home/chenzh/solvers/L_SAT22/kissat_inc/sources/build" clean
	rm -rf "/home/chenzh/solvers/L_SAT22/kissat_inc/sources/build"
coverage:
	$(MAKE) -C "/home/chenzh/solvers/L_SAT22/kissat_inc/sources/build" coverage
indent:
	$(MAKE) -C "/home/chenzh/solvers/L_SAT22/kissat_inc/sources/build" indent
test:
	$(MAKE) -C "/home/chenzh/solvers/L_SAT22/kissat_inc/sources/build" test
.PHONY: all clean coverage indent kissat test tissat
