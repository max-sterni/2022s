CFLAGS = -std=c11 -Wall -Wextra -Wpedantic -g #-fsanitize=address -Wconversion

.PHONY: all
all: game

.PHONY: clean
clean:
	$(RM) game *.pbm *.gif

game: game.c
	$(CC) $(CFLAGS) -o $@ $^
