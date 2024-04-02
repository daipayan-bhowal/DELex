# Daipayan's experimental lexer(DELex) for C programming language

![alt text](https://github.com/daipayan-bhowal/Lexer_in_C/blob/main/sample_files/DELex.jpg)

Lexer fetches all the tokens present in C programming language

List of all the values for token macros
/* Macro Values for Tokens */
#define ELIPPSIS 0x1000<br />
#define ADD_ASSIGN 0x1001<br />
#define INC_OP 0x1002<br />
#define SUB_ASSIGN 0x1003<br />
#define DEC_OP 0x1004<br />
#define DIV_ASSIGN 0x1005<br />
#define MUL_ASSIGN 0x1006<br />
#define MOD_ASSIGN 0x1007<br />
#define AND_ASSIGN 0x1008<br />
#define XOR_ASSIGN 0x1009<br />
#define OR_ASSIGN 0x1010<br />
#define NOT_ASSIGN 0x1011<br />
#define RIGHT_OP 0x1012<br />
#define LEFT_OP 0x1013<br />
#define EQ_EQ_COND 0x1014<br />
#define GRT_EQ_OP 0x1015<br />
#define LESR_EQ_OP 0x1016<br />

#define ID 0x2015<br />
#define STROBJ 0x2016<br />
#define INT_CONST 0x2017<br />
#define CHAR_CONST 0x2018<br />
#define F_CONST 0x2019<br />
#define OCTAL_CONST 0x2020<br />
#define USIGN_INT_CONST 0x2021<br />
#define LONG_INT_CONST 0x2021<br />
#define LONG_DOUBLE_CONST 0x2022<br />
#define E_F_CONST 0x2023 // extended float const<br />
#define ERR 0xff00<br />
#define NOT_FOUND 0xff01<br />

/* Keyword token */
#define AUTO 0<br />
#define BREAK 1<br />
#define CASE 2<br />
#define CHAR 3<br />
#define CONST 4<br />
#define CONTINUE 5<br />
#define DEFAULT 6<br />
#define DO 7<br />
#define DOUBLE 8<br />
#define ELSE 9<br />
#define ENUM 10<br />
#define EXTERN 11<br />
#define FLOAT 12<br />
#define FOR 13<br />
#define GOTO 14<br />
#define IF 15<br />
#define INT 16<br />
#define LONG 17<br />
#define REGISTER 18<br />
#define RETURN 19<br />
#define SHORT 20<br />
#define SIGNED 21<br />
#define SIZEOF 22<br />
#define STATIC 23<br />
#define STRUCT 24<br />
#define SWITCH 25<br />
#define TYPEDEF 26<br />
#define UNION 27<br />
#define UNSIGNED 28<br />
#define VOID 29<br />
#define VOLATILE 30<br />
#define WHILE 31<br />
