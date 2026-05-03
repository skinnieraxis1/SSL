all:
	mkdir -p output
	gcc hello.c -o output/a.exe

run: all
	./output/a.exe >./output/output.txt

clean:
	rm -f output/a.exe