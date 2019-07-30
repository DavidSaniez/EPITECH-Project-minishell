##
## EPITECH PROJECT, 2017
## Makefile
## File description:
## SANIEZ David
##

NAME=		libmy.a

SRC=		my_getnbr.c			\
		my_putchar.c			\
		my_put_nbr.c			\
		my_putstr.c			\
		my_strlen.c			\
		my_swap.c			\
		str_to_int.c			\
		my_str_to_word_array.c

OBJ=		$(SRC:.c=.o)

all:		$(NAME)

$(NAME):	$(OBJ)
		ar rc $(NAME) $(OBJ)

clean:
		rm -f $(OBJ)

fclean:		clean
		rm -f $(NAME)

re:		fclean all
