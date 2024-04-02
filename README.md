# Daipayan's experimental lexer(DELex) for C programming language

![alt text](https://github.com/daipayan-bhowal/Lexer_in_C/blob/main/sample_files/DELex.jpg)

Lexer fetches all the tokens present in C programming language

List of all the values for token macros
/* Macro Values for Tokens */
#define ELIPPSIS 0x1000
#define ADD_ASSIGN 0x1001
#define INC_OP 0x1002
#define SUB_ASSIGN 0x1003
#define DEC_OP 0x1004
#define DIV_ASSIGN 0x1005
#define MUL_ASSIGN 0x1006
#define MOD_ASSIGN 0x1007
#define AND_ASSIGN 0x1008
#define XOR_ASSIGN 0x1009
#define OR_ASSIGN 0x1010
#define NOT_ASSIGN 0x1011
#define RIGHT_OP 0x1012
#define LEFT_OP 0x1013
#define EQ_EQ_COND 0x1014
#define GRT_EQ_OP 0x1015
#define LESR_EQ_OP 0x1016

#define ID 0x2015
#define STROBJ 0x2016
#define INT_CONST 0x2017
#define CHAR_CONST 0x2018
#define F_CONST 0x2019
#define OCTAL_CONST 0x2020
#define USIGN_INT_CONST 0x2021
#define LONG_INT_CONST 0x2021
#define LONG_DOUBLE_CONST 0x2022
#define E_F_CONST 0x2023 // extended float const
#define ERR 0xff00
#define NOT_FOUND 0xff01

/* Keyword token */
#define AUTO 0
#define BREAK 1
#define CASE 2
#define CHAR 3
#define CONST 4
#define CONTINUE 5
#define DEFAULT 6
#define DO 7
#define DOUBLE 8
#define ELSE 9
#define ENUM 10
#define EXTERN 11
#define FLOAT 12
#define FOR 13
#define GOTO 14
#define IF 15
#define INT 16
#define LONG 17
#define REGISTER 18
#define RETURN 19
#define SHORT 20
#define SIGNED 21
#define SIZEOF 22
#define STATIC 23
#define STRUCT 24
#define SWITCH 25
#define TYPEDEF 26
#define UNION 27
#define UNSIGNED 28
#define VOID 29
#define VOLATILE 30
#define WHILE 31
