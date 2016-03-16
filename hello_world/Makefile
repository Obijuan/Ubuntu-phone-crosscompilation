
# -- For cross-compilation to an ubuntu phone
CC = arm-linux-gnueabihf-gcc

# -- Normal compilation in linux
#CC = gcc

NAME = hello_world

all: $(NAME)

$(NAME): $(NAME).c
	$(CC) $^ -o $@

#-- Clean the project
clean:
	rm -f $(NAME) *.o

.PHONY: all clean
