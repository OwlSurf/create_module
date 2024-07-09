# Create module script.

## This script creates two files:
    - Inc/file.h
```C
/**
 *\file file.h
 *\brief file_name module
 *\author Name Last_name
 *\copyright (c) Name Last_name
 *
 *\date created_date
 */

#ifndef INC_FILE_H_
#define INC_FILE_H_

#define _CRT_SECURE_NO_WARNINGS

#ifdef __cplusplus
extern  "C" {
#endif



#ifdef __cplusplus
}
#endif
#endif /* INC_FILE_H_ */ 
```
    - Src/file.c
```C
/**
 *\file file.c
 *\brief Name module
 *\author Name Last_name
 *\copyright (c) Name Last_name|
 *
 *\date created_date
 */

#include "file.h"
```
## How to use:
    ./cm module name author_name author_last_name
