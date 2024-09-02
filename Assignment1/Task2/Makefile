all:
	multiply_numbers

multiply_numbers:
	multiply_numbers.cpp
	g++ -o multiply_numbers.exe multiply_numbers.cpp

dump:
	multiply_numbers
	objdump -d multiply_numbers.exe > multiply_numbers.asm
clean:
	del -f multiply_numbers.exe multiply_numbers.asm
run:
	multiply_numbers
	multiply_numbers.exe