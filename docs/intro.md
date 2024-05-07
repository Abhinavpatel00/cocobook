Imagine you have to go on a date with an alien. What do you need? You need to know their language, right? You need to communicate in a way she can understand; you don't want to say something she doesn't understand, or worse, something she misunderstands. When you need to communicate with someone, you need to know their language. Similarly, with electronic machines, communication happens through electric signals or a flow of electrons.

In the early days, programmers communicated with computers by writing sequences of high and low voltage signals, like 0101001010 (0 for low voltage and 1 for high). Even today, electrical engineers grapple with this method when designing circuits or processors, as every command must be meticulously crafted, akin to manually toggling each piece on or off. Writing even a simple program could take days, contingent on the hardware architecture. To ease this burden, they devised a system where specific instructions, represented by sequences of high and low voltages (0s and 1s), were assigned mnemonic codes, streamlining the process.

Assembly instructions could be anything one can think of; you can even create them. This process is called assembly, a basic translator to convert an assembly program (which is basically a program that is based on mnemonics given to machine code) to machine code.

There are Op codes (operation codes) which are machine language instructions(0 and 1) used by computer processors to perform various operations, such as arithmetic, logic, data movement, and control flow. Each instruction in machine language typically consists of an opcode, which specifies the operation to be performed, and may also include operands that provide additional information needed for the operation.


For example, in the instruction "ADD R1, R2, R3", the opcode "ADD" specifies the addition operation, and "R1", "R2", and "R3" are the operands, indicating the registers involved in the addition operation.

Op codes are fundamental to the execution of programs by the CPU, as they dictate the specific actions that the processor needs to perform at the most basic level. Higher-level programming languages are ultimately translated into machine language instructions, including op codes, by compilers or interpreters before they can be executed by the processor.

Primary memory is like your workspace where you keep things handy while working on them (like a desk), while secondary memory is more like storage where you keep things for later use (like a filing cabinet).

In primary memory, we have DRAMs, which are fast but lose data when the power is off. It's like a whiteboard where you can quickly jot down notes but they vanish when you erase them. In secondary memory, we have magnetic disks, which are slower but retain data even when the power is off.

if you want to understand more how these circuits are made i would recommend you to get some grasp on boolean algebra before reading ahead because life is too short to write machine language so i am not rewriting those boolean algebra logics again well its not necessarily needed if you just have enough brain and passion to reinvent the wheel like i tried to do but unfortunately i had passion but not e nough brain , anyway lets get ahead .

so  you all have heard that computers use binary numbers that on and off logic all the time and you are bored from listening that again and again and when you ask someone how it works people tells you dont have enough brain to write machine code, do you?

ignoring all that stuff come with me to talk with computers in their language.

the core of computation and computer is to compute and who does computation? and how its done ? the most basic answer is electrons with logic , what do we mean by logic here , logic is something that validates truth but in computer science logic have many forms like like programming etc .. 
to build logic from electrical circuit we need a system to take a input and give us correct output to get the output we want we use logic to implement logic gates with our illogical mind to give some logical output .

imagine we have to make a computer to add two digits ? only using our logic gates(0 and 1 ) , how will we do it, what i can imagine is that we have only 0 and 1 and to convert binary to decimal what do we do ?  
$$
\text{Decimal} = b_n \times 2^n + b_{n-1} \times 2^{n-1} + \cdots + b_1 \times 2^1 + b_0 \times 2^0
$$

excersise : - try implementing a boolean logic to add two numbers

once you are done with excersise you will have an idea about computation term how can we really compute something with just turning something on and off

A classification system for computer architectures based on information flow. It discusses four categories: SISD, SIMD, MISD, and MIMD, each characterized by their instruction and data streams.

so what the cpu is basically? central processing unit as the name suggests it is central(core) of most of processing that is done by computers cpu is basically a combinatoral circuit, every program you could write in c ,c++, rust , java ,python or any language is ultimately converted to the electrical signals that cpu is designed to process and execute , in theory you could write programs in binary too many people in past have done it but............. never try to do this at home .

cpu can read instructions from memory and write it back in x86 systems there are mainly three types of buses that helps cpu to do this  address,data,control
if you are reading this in 2024 you are probably using 64 bit cpu in future things might change that the innocent author is not responsible of ,that 64 bit in your cpu is the size of the data bus, it simply means the data bus in your system can access 64 bit = 8 byte at a time to suffle between things like cpu , memory etc.
thats why 64 bit cpus are faster than previous gen cpus , now a question in your head must be there like an earthworm why not 128 bit 512 bit 1024 bit and so on why cant we keep expanding like this , well in the current state of market and industry SIMD and AVX exists whichs helps us to achieve what 128,256.... can do  ,a simple reason that dont have fundamental cpus like that is that we dont actually need them for daily life tasks and for data centers like places extended word size (AVX , SIMD...) like things exists but i am pretty sure if human civilizations keeps on surving we will keep decreasing size of transistor and we migh have 1024 bit computer some day .

so the data bus helps to move data but to where should it move? that is answered by address bus, to avoild lose data or make computing better there is unique address assosiated to each memory element.
control bus is something which controls or provides us pathways to read and write data








