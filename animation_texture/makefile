CC = gcc
CFLAGS = -g -Wall -Wextra
LDFLAGS = -lm
OBJFILES = main.o util_sdl.o
SDL2FLAGS = -lSDL2 -lSDL2_gfx -lSDL2_image -lSDL2_ttf -lSDL2_mixer -lSDL2_net
TARGET = animtext_perso_apsire_trou_noir

all: $(TARGET)

$(TARGET) : $(OBJFILES)
	$(CC) $(CFLAGS) -o $(TARGET) $(OBJFILES) $(LDFLAGS) $(SDL2FLAGS)

clean:
	rm -f $(OBJFILES) $(TARGET)

