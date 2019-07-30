##
## EPITECH PROJECT, 2018
## Makefile
## File description:
## SANIEZ David
##

NAME	=	mysh

SRC	=	src/main.c

LIB_DIR	=	$(realpath ./lib/my)

LIB	=	my

OBJ	=	$(SRC:.c=.o)

GCC_ARG	=		-L$(LIB_DIR) -l$(LIB) -I$(INC_DIR)
GCC_ARG_DEBUG	=	-L$(LIB_DIR) -l$(LIB) -I$(INC_DIR) -g
CFLAGS	=		-g -L$(LIB_DIR) -l$(LIB) -W -Wall -Wextra -Iinclude/

all:		$(NAME)

$(NAME):
		make -C $(LIB_DIR)
		gcc -o $(NAME) $(SRC) $(CFLAGS)

clean:
		make clean -C $(LIB_DIR)
		rm -f $(OBJ)

fclean:		clean
		rm -f $(NAME)
		make fclean -C $(LIB_DIR)

re:		fclean all
