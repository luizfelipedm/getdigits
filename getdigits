#include <stdio.h>
#include <stdlib.h>
#include <ctype.h>
long getDigits();

int main()
{
	
    getDigits();
    return 0;
}


long getDigits(){
    long val;
	char *string = "2x^2", *ptr = string;
	while (*ptr) {
		if (isdigit(*ptr)) {
			val = strtol(ptr, &ptr, 10);
			printf("%ld\n", val);
		} else {
			ptr++;
		}
	}
	return val;
}
