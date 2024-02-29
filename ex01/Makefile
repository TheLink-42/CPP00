# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: jbaeza-c <jbaeza-c@student.42madrid.com    +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2023/12/01 12:47:55 by jbaeza-c          #+#    #+#              #
#    Updated: 2023/12/01 18:38:00 by jbaeza-c         ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

NAME = phonebook

SRC_DIR = src/
SRC =	$(SRC_DIR)main.cpp		\
		$(SRC_DIR)Phonebook.cpp	\
		$(SRC_DIR)Contact.cpp	
OBJ_DIR = obj/
OBJ = $(SRC:$(SRC_DIR)%.cpp=$(OBJ_DIR)%.o)

CC = clang++
CPPFLAGS = -Wall -Wextra -Werror -std=c++98 -I inc
RM = rm -rf

#------------------------------------------------------------------------------#

all: $(NAME)

$(NAME): $(OBJ)
	@$(CC) $(CPPFLAGS) $(OBJ) -o $(NAME)
	@echo "$(NAME) compiled"

$(OBJ_DIR)%.o: $(SRC_DIR)%.cpp
	@mkdir -p $(@D)
	@$(CC) $(CPPFLAGS) -c $< -o $@

clean:
	@$(RM) $(OBJ_DIR)
	@echo "object files removed"

fclean: clean
	@$(RM) $(NAME)
	@echo "$(NAME) removed"

re: fclean all

.PHONY: all clean fclean re