#
#  Makefile - nsim project source compilation
#
#  Copyright (C) 2014 Collins Assisi, Collins Assisi Lab, IISER, Pune
#  Copyright (C) 2014 Pranav Kulkarni, Collins Assisi Lab, IISER, Pune <pranavcode@gmail.com>
#
#  This program is free software: you can redistribute it and/or modify
#  it under the terms of the GNU General Public License as published by
#  the Free Software Foundation, either version 3 of the License, or
#  (at your option) any later version.
#
#  This program is distributed in the hope that it will be useful,
#  but WITHOUT ANY WARRANTY; without even the implied warranty of
#  MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
#  GNU General Public License for more details.
#
#  You should have received a copy of the GNU General Public License
#  along with this program.  If not, see <http://www.gnu.org/licenses/>.
#

# Source files
SOURCE = main.cpp

# Target excutables
TARGET = insilico.out

# Compiler to use
CC = g++

# Flags to specify the compilation startegy
CFLAGS = -O3 -pthread -std=c++11 -Wall -I. -o

all: $(TARGET)

$(TARGET):
	$(CC) $(CFLAGS) $(TARGET) $(SOURCE)
