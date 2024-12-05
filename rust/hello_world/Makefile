GREEN = \033[0;32m
RED = \033[0;31m
RESET = \033[0m

all :
	@rustc main.rs
	@echo -e "${GREEN}--- Compiled main.rs ---${RESET}"

cr :
	@rustc main.rs
	@echo -e "${GREEN}--- Running compiled program ---${RESET}"
	@./main

clean :
	@rm -f main
	@echo -e "${RED}--- Removed compiled program  ---${RESET}"

.PHONY : all cr clean
