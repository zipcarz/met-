
...	...	@@ -11,7 +11,7 @@ dumpdecrypted.dylib: dumpdecrypted.o
11	11	 	$(GCC_UNIVERSAL) -dynamiclib -o $@ $^
12	12	 
13	13	 %.o: %.c
14		-	$(GCC_UNIVERSAL) -dynamiclib -c -o $@ $< 
14	+	$(GCC_UNIVERSAL) -c -o $@ $< 
15	15	 
16	16	 clean:
17	17	 	rm -f *.o dumpdecrypted.dylib
