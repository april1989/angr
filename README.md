# angr

A tool to get you VEXed!

## Dependencies

- idalink
- pyvex

## Usage

You can use angr as follows:

	import angr
	b = angr.Binary("/path/to/binary")

	for f in b.functions.values():
		print f.vex_blocks

Something like that.

## Resources

Some interesting resources.

- http://osll.spb.ru/projects/llvm
- https://github.com/bitblaze-fuzzball/fuzzball/blob/master/libasmir/src/vex/Notes
