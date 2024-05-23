

# 1a
*__Prompt__: State one fundamental difference between flip flops and latches.*

- Flip flops are edge triggered latches while latches are level triggered.
- Flip flops *always* have a clock signal latch and can but don't need one.
- Latches *can* have a clock signal but don't need one.
# 1b
*__Prompt__: State 1 advantage of __DRAM__ over __SRAM__ technology*
- __DRAM__: Cheaper
- __SRAM__: Better for High-demand devices

# 1c
*__Prompt__: Is ANNA load-share architecture?*
Yes, load/share architecture means it only loads and shares access memory.
# 1d
*__Prompt__: What is the range of signed bits*

$$
-(2^{(n-1)}) \rightarrow (2^{(n-1)}-1)
$$
# 1E
*__Prompt__: Why do we need to link object files?*

- Object files do not have startup information on their own
	- The linker turns them into an __EXE__ which does
- Line number addresses need to be moved in a multi-file program.

___
# 2B
*__Prompt__: ANNA machine code to ANNA assembly.*

1. Convert from __hex__ to __binary__.
2. __1st part__ is the code for the `action` `add`, `sub`, etc.
3. Look at instruction formats. If `rd` the number is `d`

# 2C
*__Prompt__: ANNA Assembly to ANNA Machine language*

Take the __opcode__, the __number__ of registers, and he __immediate__ number substitute into instruction format.
# 3
*__Prompt__: Microarchitecture __Single__ & __Multi__.*

## __A.__ Single:
- Cycle time $\times$ instructions.
## __B.__ Multi:
- Cycle time $\times$ number of cycles $\times$ specific number of instructions
___
# 5A
*__Prompt__: 3 Different examples of how sharing delays in computer systems can be improved*

- Faster Processors
- Using parallel cores or multiple CPUs
- Higher bandwidth
- Increase size of memory
- Parallel servers
- Higher bandwidth
- Faster buses
# 5B
*__Prompt__: Multi-Computer __vs__ Multi-Processor*
## Points
- The difference is memory & address space is not shared in __multi-computers__.
- Scalability is easier with multiple a __Multi-Computer__ setup.
## Explanation
Google needs both of these as they use multiple data centers. This makes searching quicker with more locality.

# 5C
*__Prompt__: Speedup Formula*

`n = num processors`
`p = portion can be parallelized`

$$
\frac{1}{(1-p)+\frac{p}{n}}
$$



