CC := gcc
CFLAGS := -Wall -Wextra -Werror -std=c11

UNITY_DIR := ../../assignment-autotest/Unity/src
UNITY_SRC := $(UNITY_DIR)/unity.c
UNITY_INC := -I $(UNITY_DIR)

TARGET := Test_validate_username

all: $(TARGET)

$(TARGET): Test_validate_username.c $(UNITY_SRC)
	$(CC) $(CFLAGS) $(UNITY_INC) Test_validate_username.c $(UNITY_SRC) -o $(TARGET)

clean:
	rm -f $(TARGET)

.PHONY: all clean
