NAME = push_swap

SRC = $(wildcard *.c)

OBJ = $(SRC:%.c=%.o)

all: $(NAME)

$(NAME): $(OBJ)
	gcc -o $(NAME) $(OBJ)

clean:
	rm -f $(OBJ)

fclean: clean
	rm -f $(NAME)

re: fclean all

flemme: re
	make clean

.PHONY: clean fclean all re
