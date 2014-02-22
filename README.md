LLVM with AVR Target
========

LLVM 3.5 Bleeding-edge version of the avr-llvm project (http://sourceforge.net/projects/avr-llvm)

Directory structure (follows the LLVM source tree structure):

	LLVM/lib/Target/AVR
		* Contains the source for AVR code generation

	LLVM/test/CodeGen/AVR
		* Contains feature and regression tests for the AVR Target. These are intended to run quickly and cover a lot of territory *without being exhaustive*.

	LLVM patches for the following files:
		* autoconf/configure.ac.diff
		* cmake/config-ix.cmake.diff
		* CMakeLists.txt.diff
		* include/llvm/ADT/Triple.h.diff
		* include/llvm/IR/CallingConv.diff
		* lib/AsmParser/LLLexer.diff
		* lib/AsmParser/LLParser.diff
		* lib/AsmParser/LLToken.diff
		* lib/CodeGen/AsmPrinter/AsmPrinter.cpp.diff
		* lib/CodeGen/CalcSpillWeights.cpp.diff
		* lib/CodeGen/RegAllocGreedy.cpp.diff
		* lib/IR/AsmWriter.cpp.diff
		* lib/IR/DataLayout.cpp.diff
		* lib/Support/Triple.cpp.diff
		* lib/Target/LLVMBuild.txt.diff
		* projects/sample/autoconf/configure.ac.diff

