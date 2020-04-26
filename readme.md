I am telling about GIT
# Heading 1
- I am representing it in the bullet line
> hfbvhfbfgnfknuf
`````
#include <stdio.h>
#include <stdlib.h>
#include <time.h>
#include "CArray.h"

void swap(CArray *array, int position1, int position2);

CArray * getCArray(int size)
{
	CArray *array = (CArray *) malloc(sizeof(CArray));
	array->array = (int *) malloc(sizeof(int) * size);
	array->size = size;
	int i;
	for (i = 0; i < size; i++) {
		array->array[i] = 0;
	}
	return array;
}

int insertValueCArray(CArray *array, int position, int value)
{
	if (position >= 0 && position < array->size) {
		if (array->array[position] == 0) {
			array->array[position] = value;
			return SUCCESS;
`````
