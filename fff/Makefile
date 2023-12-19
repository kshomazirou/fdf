
NAME=test
OBJ=test.c

%.o: %.c
	$(CC) -Wall -Wextra -Werror -Imlx -c $< -o $@

$(NAME): $(OBJ)
	$(CC) $(OBJ)  -L./minilibx_macos -lmlx -framework OpenGL -framework AppKit -o $(NAME)