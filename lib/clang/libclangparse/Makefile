# $FreeBSD$

.include <bsd.own.mk>

LIB=	clangparse

SRCDIR=	tools/clang/lib/Parse
SRCS=	ParseAST.cpp \
	ParseCXXInlineMethods.cpp \
	ParseDecl.cpp \
	ParseDeclCXX.cpp \
	ParseExpr.cpp \
	ParseExprCXX.cpp \
	ParseInit.cpp \
	ParseObjc.cpp \
	ParseOpenMP.cpp \
	ParsePragma.cpp \
	ParseStmt.cpp \
	ParseTemplate.cpp \
	ParseTentative.cpp \
	Parser.cpp

TGHDRS=	AttrIdentifierArg \
	AttrLateParsed \
	AttrList \
	AttrParsedAttrList \
	AttrTypeArg \
	Attrs \
	CommentCommandList \
	CommentNodes \
	DeclNodes \
	DiagnosticCommonKinds \
	DiagnosticParseKinds \
	DiagnosticSemaKinds \
	StmtNodes

.include "../clang.lib.mk"
