
./bomb:     file format elf64-x86-64


Disassembly of section .init:

0000000000001000 <_init>:
    1000:	f3 0f 1e fa          	endbr64
    1004:	48 83 ec 08          	sub    $0x8,%rsp
    1008:	48 8b 05 d9 3f 00 00 	mov    0x3fd9(%rip),%rax        # 4fe8 <__gmon_start__>
    100f:	48 85 c0             	test   %rax,%rax
    1012:	74 02                	je     1016 <_init+0x16>
    1014:	ff d0                	call   *%rax
    1016:	48 83 c4 08          	add    $0x8,%rsp
    101a:	c3                   	ret

Disassembly of section .plt:

0000000000001020 <getenv@plt-0x10>:
    1020:	ff 35 e2 3f 00 00    	push   0x3fe2(%rip)        # 5008 <_GLOBAL_OFFSET_TABLE_+0x8>
    1026:	ff 25 e4 3f 00 00    	jmp    *0x3fe4(%rip)        # 5010 <_GLOBAL_OFFSET_TABLE_+0x10>
    102c:	0f 1f 40 00          	nopl   0x0(%rax)

0000000000001030 <getenv@plt>:
    1030:	ff 25 e2 3f 00 00    	jmp    *0x3fe2(%rip)        # 5018 <getenv@GLIBC_2.2.5>
    1036:	68 00 00 00 00       	push   $0x0
    103b:	e9 e0 ff ff ff       	jmp    1020 <_init+0x20>

0000000000001040 <strcasecmp@plt>:
    1040:	ff 25 da 3f 00 00    	jmp    *0x3fda(%rip)        # 5020 <strcasecmp@GLIBC_2.2.5>
    1046:	68 01 00 00 00       	push   $0x1
    104b:	e9 d0 ff ff ff       	jmp    1020 <_init+0x20>

0000000000001050 <__errno_location@plt>:
    1050:	ff 25 d2 3f 00 00    	jmp    *0x3fd2(%rip)        # 5028 <__errno_location@GLIBC_2.2.5>
    1056:	68 02 00 00 00       	push   $0x2
    105b:	e9 c0 ff ff ff       	jmp    1020 <_init+0x20>

0000000000001060 <strcpy@plt>:
    1060:	ff 25 ca 3f 00 00    	jmp    *0x3fca(%rip)        # 5030 <strcpy@GLIBC_2.2.5>
    1066:	68 03 00 00 00       	push   $0x3
    106b:	e9 b0 ff ff ff       	jmp    1020 <_init+0x20>

0000000000001070 <puts@plt>:
    1070:	ff 25 c2 3f 00 00    	jmp    *0x3fc2(%rip)        # 5038 <puts@GLIBC_2.2.5>
    1076:	68 04 00 00 00       	push   $0x4
    107b:	e9 a0 ff ff ff       	jmp    1020 <_init+0x20>

0000000000001080 <write@plt>:
    1080:	ff 25 ba 3f 00 00    	jmp    *0x3fba(%rip)        # 5040 <write@GLIBC_2.2.5>
    1086:	68 05 00 00 00       	push   $0x5
    108b:	e9 90 ff ff ff       	jmp    1020 <_init+0x20>

0000000000001090 <strlen@plt>:
    1090:	ff 25 b2 3f 00 00    	jmp    *0x3fb2(%rip)        # 5048 <strlen@GLIBC_2.2.5>
    1096:	68 06 00 00 00       	push   $0x6
    109b:	e9 80 ff ff ff       	jmp    1020 <_init+0x20>

00000000000010a0 <__stack_chk_fail@plt>:
    10a0:	ff 25 aa 3f 00 00    	jmp    *0x3faa(%rip)        # 5050 <__stack_chk_fail@GLIBC_2.4>
    10a6:	68 07 00 00 00       	push   $0x7
    10ab:	e9 70 ff ff ff       	jmp    1020 <_init+0x20>

00000000000010b0 <printf@plt>:
    10b0:	ff 25 a2 3f 00 00    	jmp    *0x3fa2(%rip)        # 5058 <printf@GLIBC_2.2.5>
    10b6:	68 08 00 00 00       	push   $0x8
    10bb:	e9 60 ff ff ff       	jmp    1020 <_init+0x20>

00000000000010c0 <alarm@plt>:
    10c0:	ff 25 9a 3f 00 00    	jmp    *0x3f9a(%rip)        # 5060 <alarm@GLIBC_2.2.5>
    10c6:	68 09 00 00 00       	push   $0x9
    10cb:	e9 50 ff ff ff       	jmp    1020 <_init+0x20>

00000000000010d0 <close@plt>:
    10d0:	ff 25 92 3f 00 00    	jmp    *0x3f92(%rip)        # 5068 <close@GLIBC_2.2.5>
    10d6:	68 0a 00 00 00       	push   $0xa
    10db:	e9 40 ff ff ff       	jmp    1020 <_init+0x20>

00000000000010e0 <read@plt>:
    10e0:	ff 25 8a 3f 00 00    	jmp    *0x3f8a(%rip)        # 5070 <read@GLIBC_2.2.5>
    10e6:	68 0b 00 00 00       	push   $0xb
    10eb:	e9 30 ff ff ff       	jmp    1020 <_init+0x20>

00000000000010f0 <fgets@plt>:
    10f0:	ff 25 82 3f 00 00    	jmp    *0x3f82(%rip)        # 5078 <fgets@GLIBC_2.2.5>
    10f6:	68 0c 00 00 00       	push   $0xc
    10fb:	e9 20 ff ff ff       	jmp    1020 <_init+0x20>

0000000000001100 <strcmp@plt>:
    1100:	ff 25 7a 3f 00 00    	jmp    *0x3f7a(%rip)        # 5080 <strcmp@GLIBC_2.2.5>
    1106:	68 0d 00 00 00       	push   $0xd
    110b:	e9 10 ff ff ff       	jmp    1020 <_init+0x20>

0000000000001110 <signal@plt>:
    1110:	ff 25 72 3f 00 00    	jmp    *0x3f72(%rip)        # 5088 <signal@GLIBC_2.2.5>
    1116:	68 0e 00 00 00       	push   $0xe
    111b:	e9 00 ff ff ff       	jmp    1020 <_init+0x20>

0000000000001120 <gethostbyname@plt>:
    1120:	ff 25 6a 3f 00 00    	jmp    *0x3f6a(%rip)        # 5090 <gethostbyname@GLIBC_2.2.5>
    1126:	68 0f 00 00 00       	push   $0xf
    112b:	e9 f0 fe ff ff       	jmp    1020 <_init+0x20>

0000000000001130 <fprintf@plt>:
    1130:	ff 25 62 3f 00 00    	jmp    *0x3f62(%rip)        # 5098 <fprintf@GLIBC_2.2.5>
    1136:	68 10 00 00 00       	push   $0x10
    113b:	e9 e0 fe ff ff       	jmp    1020 <_init+0x20>

0000000000001140 <fflush@plt>:
    1140:	ff 25 5a 3f 00 00    	jmp    *0x3f5a(%rip)        # 50a0 <fflush@GLIBC_2.2.5>
    1146:	68 11 00 00 00       	push   $0x11
    114b:	e9 d0 fe ff ff       	jmp    1020 <_init+0x20>

0000000000001150 <__isoc99_sscanf@plt>:
    1150:	ff 25 52 3f 00 00    	jmp    *0x3f52(%rip)        # 50a8 <__isoc99_sscanf@GLIBC_2.7>
    1156:	68 12 00 00 00       	push   $0x12
    115b:	e9 c0 fe ff ff       	jmp    1020 <_init+0x20>

0000000000001160 <memmove@plt>:
    1160:	ff 25 4a 3f 00 00    	jmp    *0x3f4a(%rip)        # 50b0 <memmove@GLIBC_2.2.5>
    1166:	68 13 00 00 00       	push   $0x13
    116b:	e9 b0 fe ff ff       	jmp    1020 <_init+0x20>

0000000000001170 <fopen@plt>:
    1170:	ff 25 42 3f 00 00    	jmp    *0x3f42(%rip)        # 50b8 <fopen@GLIBC_2.2.5>
    1176:	68 14 00 00 00       	push   $0x14
    117b:	e9 a0 fe ff ff       	jmp    1020 <_init+0x20>

0000000000001180 <sprintf@plt>:
    1180:	ff 25 3a 3f 00 00    	jmp    *0x3f3a(%rip)        # 50c0 <sprintf@GLIBC_2.2.5>
    1186:	68 15 00 00 00       	push   $0x15
    118b:	e9 90 fe ff ff       	jmp    1020 <_init+0x20>

0000000000001190 <exit@plt>:
    1190:	ff 25 32 3f 00 00    	jmp    *0x3f32(%rip)        # 50c8 <exit@GLIBC_2.2.5>
    1196:	68 16 00 00 00       	push   $0x16
    119b:	e9 80 fe ff ff       	jmp    1020 <_init+0x20>

00000000000011a0 <connect@plt>:
    11a0:	ff 25 2a 3f 00 00    	jmp    *0x3f2a(%rip)        # 50d0 <connect@GLIBC_2.2.5>
    11a6:	68 17 00 00 00       	push   $0x17
    11ab:	e9 70 fe ff ff       	jmp    1020 <_init+0x20>

00000000000011b0 <sleep@plt>:
    11b0:	ff 25 22 3f 00 00    	jmp    *0x3f22(%rip)        # 50d8 <sleep@GLIBC_2.2.5>
    11b6:	68 18 00 00 00       	push   $0x18
    11bb:	e9 60 fe ff ff       	jmp    1020 <_init+0x20>

00000000000011c0 <__ctype_b_loc@plt>:
    11c0:	ff 25 1a 3f 00 00    	jmp    *0x3f1a(%rip)        # 50e0 <__ctype_b_loc@GLIBC_2.3>
    11c6:	68 19 00 00 00       	push   $0x19
    11cb:	e9 50 fe ff ff       	jmp    1020 <_init+0x20>

00000000000011d0 <socket@plt>:
    11d0:	ff 25 12 3f 00 00    	jmp    *0x3f12(%rip)        # 50e8 <socket@GLIBC_2.2.5>
    11d6:	68 1a 00 00 00       	push   $0x1a
    11db:	e9 40 fe ff ff       	jmp    1020 <_init+0x20>

Disassembly of section .text:

00000000000011e0 <_start>:
    11e0:	f3 0f 1e fa          	endbr64
    11e4:	31 ed                	xor    %ebp,%ebp
    11e6:	49 89 d1             	mov    %rdx,%r9
    11e9:	5e                   	pop    %rsi
    11ea:	48 89 e2             	mov    %rsp,%rdx
    11ed:	48 83 e4 f0          	and    $0xfffffffffffffff0,%rsp
    11f1:	50                   	push   %rax
    11f2:	54                   	push   %rsp
    11f3:	4c 8d 05 46 1c 00 00 	lea    0x1c46(%rip),%r8        # 2e40 <__libc_csu_fini>
    11fa:	48 8d 0d cf 1b 00 00 	lea    0x1bcf(%rip),%rcx        # 2dd0 <__libc_csu_init>
    1201:	48 8d 3d d1 00 00 00 	lea    0xd1(%rip),%rdi        # 12d9 <main>
    1208:	ff 15 d2 3d 00 00    	call   *0x3dd2(%rip)        # 4fe0 <__libc_start_main@GLIBC_2.2.5>
    120e:	f4                   	hlt
    120f:	90                   	nop

0000000000001210 <deregister_tm_clones>:
    1210:	48 8d 3d 49 44 00 00 	lea    0x4449(%rip),%rdi        # 5660 <stdout@GLIBC_2.2.5>
    1217:	48 8d 05 42 44 00 00 	lea    0x4442(%rip),%rax        # 5660 <stdout@GLIBC_2.2.5>
    121e:	48 39 f8             	cmp    %rdi,%rax
    1221:	74 15                	je     1238 <deregister_tm_clones+0x28>
    1223:	48 8b 05 ae 3d 00 00 	mov    0x3dae(%rip),%rax        # 4fd8 <_ITM_deregisterTMCloneTable>
    122a:	48 85 c0             	test   %rax,%rax
    122d:	74 09                	je     1238 <deregister_tm_clones+0x28>
    122f:	ff e0                	jmp    *%rax
    1231:	0f 1f 80 00 00 00 00 	nopl   0x0(%rax)
    1238:	c3                   	ret
    1239:	0f 1f 80 00 00 00 00 	nopl   0x0(%rax)

0000000000001240 <register_tm_clones>:
    1240:	48 8d 3d 19 44 00 00 	lea    0x4419(%rip),%rdi        # 5660 <stdout@GLIBC_2.2.5>
    1247:	48 8d 35 12 44 00 00 	lea    0x4412(%rip),%rsi        # 5660 <stdout@GLIBC_2.2.5>
    124e:	48 29 fe             	sub    %rdi,%rsi
    1251:	48 89 f0             	mov    %rsi,%rax
    1254:	48 c1 ee 3f          	shr    $0x3f,%rsi
    1258:	48 c1 f8 03          	sar    $0x3,%rax
    125c:	48 01 c6             	add    %rax,%rsi
    125f:	48 d1 fe             	sar    $1,%rsi
    1262:	74 14                	je     1278 <register_tm_clones+0x38>
    1264:	48 8b 05 85 3d 00 00 	mov    0x3d85(%rip),%rax        # 4ff0 <_ITM_registerTMCloneTable>
    126b:	48 85 c0             	test   %rax,%rax
    126e:	74 08                	je     1278 <register_tm_clones+0x38>
    1270:	ff e0                	jmp    *%rax
    1272:	66 0f 1f 44 00 00    	nopw   0x0(%rax,%rax,1)
    1278:	c3                   	ret
    1279:	0f 1f 80 00 00 00 00 	nopl   0x0(%rax)

0000000000001280 <__do_global_dtors_aux>:
    1280:	f3 0f 1e fa          	endbr64
    1284:	80 3d fd 43 00 00 00 	cmpb   $0x0,0x43fd(%rip)        # 5688 <completed.0>
    128b:	75 33                	jne    12c0 <__do_global_dtors_aux+0x40>
    128d:	55                   	push   %rbp
    128e:	48 83 3d 62 3d 00 00 	cmpq   $0x0,0x3d62(%rip)        # 4ff8 <__cxa_finalize@GLIBC_2.2.5>
    1295:	00 
    1296:	48 89 e5             	mov    %rsp,%rbp
    1299:	74 0d                	je     12a8 <__do_global_dtors_aux+0x28>
    129b:	48 8b 3d 66 3e 00 00 	mov    0x3e66(%rip),%rdi        # 5108 <__dso_handle>
    12a2:	ff 15 50 3d 00 00    	call   *0x3d50(%rip)        # 4ff8 <__cxa_finalize@GLIBC_2.2.5>
    12a8:	e8 63 ff ff ff       	call   1210 <deregister_tm_clones>
    12ad:	c6 05 d4 43 00 00 01 	movb   $0x1,0x43d4(%rip)        # 5688 <completed.0>
    12b4:	5d                   	pop    %rbp
    12b5:	c3                   	ret
    12b6:	66 2e 0f 1f 84 00 00 	cs nopw 0x0(%rax,%rax,1)
    12bd:	00 00 00 
    12c0:	c3                   	ret
    12c1:	66 66 2e 0f 1f 84 00 	data16 cs nopw 0x0(%rax,%rax,1)
    12c8:	00 00 00 00 
    12cc:	0f 1f 40 00          	nopl   0x0(%rax)

00000000000012d0 <frame_dummy>:
    12d0:	f3 0f 1e fa          	endbr64
    12d4:	e9 67 ff ff ff       	jmp    1240 <register_tm_clones>

00000000000012d9 <main>:
    12d9:	53                   	push   %rbx
    12da:	83 ff 01             	cmp    $0x1,%edi
    12dd:	0f 84 04 01 00 00    	je     13e7 <main+0x10e>
    12e3:	48 89 f3             	mov    %rsi,%rbx
    12e6:	83 ff 02             	cmp    $0x2,%edi
    12e9:	0f 85 28 01 00 00    	jne    1417 <main+0x13e>
    12ef:	48 8b 7e 08          	mov    0x8(%rsi),%rdi
    12f3:	48 8d 35 0a 1d 00 00 	lea    0x1d0a(%rip),%rsi        # 3004 <_IO_stdin_used+0x4>
    12fa:	e8 71 fe ff ff       	call   1170 <fopen@plt>
    12ff:	48 89 05 8a 43 00 00 	mov    %rax,0x438a(%rip)        # 5690 <infile>
    1306:	48 85 c0             	test   %rax,%rax
    1309:	0f 84 eb 00 00 00    	je     13fa <main+0x121>
    130f:	e8 c4 09 00 00       	call   1cd8 <initialize_bomb>
    1314:	48 8d 3d 65 1d 00 00 	lea    0x1d65(%rip),%rdi        # 3080 <_IO_stdin_used+0x80>
    131b:	e8 50 fd ff ff       	call   1070 <puts@plt>
    1320:	48 8d 3d 99 1d 00 00 	lea    0x1d99(%rip),%rdi        # 30c0 <_IO_stdin_used+0xc0>
    1327:	e8 44 fd ff ff       	call   1070 <puts@plt>
    132c:	e8 b1 0c 00 00       	call   1fe2 <read_line>
    1331:	48 89 c7             	mov    %rax,%rdi
    1334:	e8 fc 00 00 00       	call   1435 <phase_1>
    1339:	e8 de 0d 00 00       	call   211c <phase_defused>
    133e:	48 8d 3d ab 1d 00 00 	lea    0x1dab(%rip),%rdi        # 30f0 <_IO_stdin_used+0xf0>
    1345:	e8 26 fd ff ff       	call   1070 <puts@plt>
    134a:	e8 93 0c 00 00       	call   1fe2 <read_line>
    134f:	48 89 c7             	mov    %rax,%rdi
    1352:	e8 fe 00 00 00       	call   1455 <phase_2>
    1357:	e8 c0 0d 00 00       	call   211c <phase_defused>
    135c:	48 8d 3d da 1c 00 00 	lea    0x1cda(%rip),%rdi        # 303d <_IO_stdin_used+0x3d>
    1363:	e8 08 fd ff ff       	call   1070 <puts@plt>
    1368:	e8 75 0c 00 00       	call   1fe2 <read_line>
    136d:	48 89 c7             	mov    %rax,%rdi
    1370:	e8 cf 01 00 00       	call   1544 <phase_3>
    1375:	e8 a2 0d 00 00       	call   211c <phase_defused>
    137a:	48 8d 3d cd 1c 00 00 	lea    0x1ccd(%rip),%rdi        # 304e <_IO_stdin_used+0x4e>
    1381:	e8 ea fc ff ff       	call   1070 <puts@plt>
    1386:	48 8d 3d 93 1d 00 00 	lea    0x1d93(%rip),%rdi        # 3120 <_IO_stdin_used+0x120>
    138d:	e8 de fc ff ff       	call   1070 <puts@plt>
    1392:	e8 4b 0c 00 00       	call   1fe2 <read_line>
    1397:	48 89 c7             	mov    %rax,%rdi
    139a:	e8 53 03 00 00       	call   16f2 <phase_4>
    139f:	e8 78 0d 00 00       	call   211c <phase_defused>
    13a4:	48 8d 3d ad 1d 00 00 	lea    0x1dad(%rip),%rdi        # 3158 <_IO_stdin_used+0x158>
    13ab:	e8 c0 fc ff ff       	call   1070 <puts@plt>
    13b0:	e8 2d 0c 00 00       	call   1fe2 <read_line>
    13b5:	48 89 c7             	mov    %rax,%rdi
    13b8:	e8 f3 03 00 00       	call   17b0 <phase_5>
    13bd:	e8 5a 0d 00 00       	call   211c <phase_defused>
    13c2:	48 8d 3d 94 1c 00 00 	lea    0x1c94(%rip),%rdi        # 305d <_IO_stdin_used+0x5d>
    13c9:	e8 a2 fc ff ff       	call   1070 <puts@plt>
    13ce:	e8 0f 0c 00 00       	call   1fe2 <read_line>
    13d3:	48 89 c7             	mov    %rax,%rdi
    13d6:	e8 62 04 00 00       	call   183d <phase_6>
    13db:	e8 3c 0d 00 00       	call   211c <phase_defused>
    13e0:	b8 00 00 00 00       	mov    $0x0,%eax
    13e5:	5b                   	pop    %rbx
    13e6:	c3                   	ret
    13e7:	48 8b 05 82 42 00 00 	mov    0x4282(%rip),%rax        # 5670 <stdin@GLIBC_2.2.5>
    13ee:	48 89 05 9b 42 00 00 	mov    %rax,0x429b(%rip)        # 5690 <infile>
    13f5:	e9 15 ff ff ff       	jmp    130f <main+0x36>
    13fa:	48 8b 53 08          	mov    0x8(%rbx),%rdx
    13fe:	48 8b 33             	mov    (%rbx),%rsi
    1401:	48 8d 3d fe 1b 00 00 	lea    0x1bfe(%rip),%rdi        # 3006 <_IO_stdin_used+0x6>
    1408:	e8 a3 fc ff ff       	call   10b0 <printf@plt>
    140d:	bf 08 00 00 00       	mov    $0x8,%edi
    1412:	e8 79 fd ff ff       	call   1190 <exit@plt>
    1417:	48 8b 36             	mov    (%rsi),%rsi
    141a:	48 8d 3d 02 1c 00 00 	lea    0x1c02(%rip),%rdi        # 3023 <_IO_stdin_used+0x23>
    1421:	b8 00 00 00 00       	mov    $0x0,%eax
    1426:	e8 85 fc ff ff       	call   10b0 <printf@plt>
    142b:	bf 08 00 00 00       	mov    $0x8,%edi
    1430:	e8 5b fd ff ff       	call   1190 <exit@plt>

0000000000001435 <phase_1>:
    1435:	48 83 ec 08          	sub    $0x8,%rsp
    1439:	48 8d 35 40 1d 00 00 	lea    0x1d40(%rip),%rsi        # 3180 <_IO_stdin_used+0x180>
    1440:	e8 37 08 00 00       	call   1c7c <strings_not_equal>
    1445:	85 c0                	test   %eax,%eax
    1447:	75 05                	jne    144e <phase_1+0x19>
    1449:	48 83 c4 08          	add    $0x8,%rsp
    144d:	c3                   	ret
    144e:	e8 8e 0a 00 00       	call   1ee1 <explode_bomb>
    1453:	eb f4                	jmp    1449 <phase_1+0x14>

0000000000001455 <phase_2>:
    1455:	55                   	push   %rbp
    1456:	53                   	push   %rbx
    1457:	48 83 ec 38          	sub    $0x38,%rsp
    145b:	64 48 8b 04 25 28 00 	mov    %fs:0x28,%rax
    1462:	00 00 
    1464:	48 89 44 24 28       	mov    %rax,0x28(%rsp)
    1469:	31 c0                	xor    %eax,%eax
    146b:	48 89 e2             	mov    %rsp,%rdx
    146e:	48 8d 4c 24 04       	lea    0x4(%rsp),%rcx
    1473:	4c 8d 4c 24 0c       	lea    0xc(%rsp),%r9
    1478:	4c 8d 44 24 08       	lea    0x8(%rsp),%r8
    147d:	48 8d 35 1d 21 00 00 	lea    0x211d(%rip),%rsi        # 35a1 <array.0+0x361>
    1484:	e8 c7 fc ff ff       	call   1150 <__isoc99_sscanf@plt>
    1489:	83 f8 04             	cmp    $0x4,%eax
    148c:	75 14                	jne    14a2 <phase_2+0x4d>
    148e:	48 8d 3d 9b 3c 00 00 	lea    0x3c9b(%rip),%rdi        # 5130 <matA.2>
    1495:	48 8d 5c 24 10       	lea    0x10(%rsp),%rbx
    149a:	41 bb 00 00 00 00    	mov    $0x0,%r11d
    14a0:	eb 19                	jmp    14bb <phase_2+0x66>
    14a2:	e8 3a 0a 00 00       	call   1ee1 <explode_bomb>
    14a7:	eb e5                	jmp    148e <phase_2+0x39>
    14a9:	41 83 c3 01          	add    $0x1,%r11d
    14ad:	48 83 c7 0c          	add    $0xc,%rdi
    14b1:	48 83 c3 08          	add    $0x8,%rbx
    14b5:	41 83 fb 02          	cmp    $0x2,%r11d
    14b9:	74 47                	je     1502 <phase_2+0xad>
    14bb:	48 8d 35 4e 3c 00 00 	lea    0x3c4e(%rip),%rsi        # 5110 <matB.1>
    14c2:	49 89 d9             	mov    %rbx,%r9
    14c5:	41 b8 00 00 00 00    	mov    $0x0,%r8d
    14cb:	4d 89 ca             	mov    %r9,%r10
    14ce:	b8 00 00 00 00       	mov    $0x0,%eax
    14d3:	b9 00 00 00 00       	mov    $0x0,%ecx
    14d8:	8b 14 87             	mov    (%rdi,%rax,4),%edx
    14db:	0f af 14 c6          	imul   (%rsi,%rax,8),%edx
    14df:	01 d1                	add    %edx,%ecx
    14e1:	48 83 c0 01          	add    $0x1,%rax
    14e5:	48 83 f8 03          	cmp    $0x3,%rax
    14e9:	75 ed                	jne    14d8 <phase_2+0x83>
    14eb:	41 89 0a             	mov    %ecx,(%r10)
    14ee:	41 83 c0 01          	add    $0x1,%r8d
    14f2:	49 83 c1 04          	add    $0x4,%r9
    14f6:	48 83 c6 04          	add    $0x4,%rsi
    14fa:	41 83 f8 02          	cmp    $0x2,%r8d
    14fe:	75 cb                	jne    14cb <phase_2+0x76>
    1500:	eb a7                	jmp    14a9 <phase_2+0x54>
    1502:	bb 00 00 00 00       	mov    $0x0,%ebx
    1507:	48 8d 6c 24 10       	lea    0x10(%rsp),%rbp
    150c:	eb 0a                	jmp    1518 <phase_2+0xc3>
    150e:	48 83 c3 04          	add    $0x4,%rbx
    1512:	48 83 fb 10          	cmp    $0x10,%rbx
    1516:	74 10                	je     1528 <phase_2+0xd3>
    1518:	8b 44 1d 00          	mov    0x0(%rbp,%rbx,1),%eax
    151c:	39 04 1c             	cmp    %eax,(%rsp,%rbx,1)
    151f:	74 ed                	je     150e <phase_2+0xb9>
    1521:	e8 bb 09 00 00       	call   1ee1 <explode_bomb>
    1526:	eb e6                	jmp    150e <phase_2+0xb9>
    1528:	48 8b 44 24 28       	mov    0x28(%rsp),%rax
    152d:	64 48 2b 04 25 28 00 	sub    %fs:0x28,%rax
    1534:	00 00 
    1536:	75 07                	jne    153f <phase_2+0xea>
    1538:	48 83 c4 38          	add    $0x38,%rsp
    153c:	5b                   	pop    %rbx
    153d:	5d                   	pop    %rbp
    153e:	c3                   	ret
    153f:	e8 5c fb ff ff       	call   10a0 <__stack_chk_fail@plt>

0000000000001544 <phase_3>:
    1544:	53                   	push   %rbx
    1545:	48 83 ec 10          	sub    $0x10,%rsp
    1549:	64 48 8b 04 25 28 00 	mov    %fs:0x28,%rax
    1550:	00 00 
    1552:	48 89 44 24 08       	mov    %rax,0x8(%rsp)
    1557:	31 c0                	xor    %eax,%eax
    1559:	48 8d 4c 24 04       	lea    0x4(%rsp),%rcx
    155e:	48 89 e2             	mov    %rsp,%rdx
    1561:	48 8d 35 3f 20 00 00 	lea    0x203f(%rip),%rsi        # 35a7 <array.0+0x367>
    1568:	e8 e3 fb ff ff       	call   1150 <__isoc99_sscanf@plt>
    156d:	83 f8 01             	cmp    $0x1,%eax
    1570:	7e 07                	jle    1579 <phase_3+0x35>
    1572:	83 7c 24 04 00       	cmpl   $0x0,0x4(%rsp)
    1577:	78 05                	js     157e <phase_3+0x3a>
    1579:	e8 63 09 00 00       	call   1ee1 <explode_bomb>
    157e:	83 3c 24 07          	cmpl   $0x7,(%rsp)
    1582:	0f 87 9a 00 00 00    	ja     1622 <phase_3+0xde>
    1588:	8b 04 24             	mov    (%rsp),%eax
    158b:	48 8d 15 8e 1c 00 00 	lea    0x1c8e(%rip),%rdx        # 3220 <_IO_stdin_used+0x220>
    1592:	48 63 04 82          	movslq (%rdx,%rax,4),%rax
    1596:	48 01 d0             	add    %rdx,%rax
    1599:	ff e0                	jmp    *%rax
    159b:	b8 e8 00 00 00       	mov    $0xe8,%eax
    15a0:	2d dd 03 00 00       	sub    $0x3dd,%eax
    15a5:	05 de 03 00 00       	add    $0x3de,%eax
    15aa:	8d 98 60 fc ff ff    	lea    -0x3a0(%rax),%ebx
    15b0:	e8 2c 09 00 00       	call   1ee1 <explode_bomb>
    15b5:	8d 83 a0 03 00 00    	lea    0x3a0(%rbx),%eax
    15bb:	2d a0 03 00 00       	sub    $0x3a0,%eax
    15c0:	05 a0 03 00 00       	add    $0x3a0,%eax
    15c5:	2d a0 03 00 00       	sub    $0x3a0,%eax
    15ca:	83 3c 24 05          	cmpl   $0x5,(%rsp)
    15ce:	7f 06                	jg     15d6 <phase_3+0x92>
    15d0:	39 44 24 04          	cmp    %eax,0x4(%rsp)
    15d4:	74 05                	je     15db <phase_3+0x97>
    15d6:	e8 06 09 00 00       	call   1ee1 <explode_bomb>
    15db:	48 8b 44 24 08       	mov    0x8(%rsp),%rax
    15e0:	64 48 2b 04 25 28 00 	sub    %fs:0x28,%rax
    15e7:	00 00 
    15e9:	75 43                	jne    162e <phase_3+0xea>
    15eb:	48 83 c4 10          	add    $0x10,%rsp
    15ef:	5b                   	pop    %rbx
    15f0:	c3                   	ret
    15f1:	b8 00 00 00 00       	mov    $0x0,%eax
    15f6:	eb a8                	jmp    15a0 <phase_3+0x5c>
    15f8:	b8 00 00 00 00       	mov    $0x0,%eax
    15fd:	eb a6                	jmp    15a5 <phase_3+0x61>
    15ff:	b8 00 00 00 00       	mov    $0x0,%eax
    1604:	eb a4                	jmp    15aa <phase_3+0x66>
    1606:	bb 00 00 00 00       	mov    $0x0,%ebx
    160b:	eb a8                	jmp    15b5 <phase_3+0x71>
    160d:	b8 00 00 00 00       	mov    $0x0,%eax
    1612:	eb a7                	jmp    15bb <phase_3+0x77>
    1614:	b8 00 00 00 00       	mov    $0x0,%eax
    1619:	eb a5                	jmp    15c0 <phase_3+0x7c>
    161b:	b8 00 00 00 00       	mov    $0x0,%eax
    1620:	eb a3                	jmp    15c5 <phase_3+0x81>
    1622:	e8 ba 08 00 00       	call   1ee1 <explode_bomb>
    1627:	b8 00 00 00 00       	mov    $0x0,%eax
    162c:	eb 9c                	jmp    15ca <phase_3+0x86>
    162e:	e8 6d fa ff ff       	call   10a0 <__stack_chk_fail@plt>

0000000000001633 <func4_1>:
    1633:	b8 00 00 00 00       	mov    $0x0,%eax
    1638:	85 ff                	test   %edi,%edi
    163a:	7e 1c                	jle    1658 <func4_1+0x25>
    163c:	89 f8                	mov    %edi,%eax
    163e:	83 ff 01             	cmp    $0x1,%edi
    1641:	74 15                	je     1658 <func4_1+0x25>
    1643:	48 83 ec 08          	sub    $0x8,%rsp
    1647:	83 ef 01             	sub    $0x1,%edi
    164a:	e8 e4 ff ff ff       	call   1633 <func4_1>
    164f:	8d 44 00 01          	lea    0x1(%rax,%rax,1),%eax
    1653:	48 83 c4 08          	add    $0x8,%rsp
    1657:	c3                   	ret
    1658:	c3                   	ret

0000000000001659 <func4_2>:
    1659:	41 57                	push   %r15
    165b:	41 56                	push   %r14
    165d:	41 55                	push   %r13
    165f:	41 54                	push   %r12
    1661:	55                   	push   %rbp
    1662:	53                   	push   %rbx
    1663:	48 83 ec 08          	sub    $0x8,%rsp
    1667:	41 89 d4             	mov    %edx,%r12d
    166a:	41 89 cd             	mov    %ecx,%r13d
    166d:	4c 89 cd             	mov    %r9,%rbp
    1670:	83 ff 01             	cmp    $0x1,%edi
    1673:	74 2a                	je     169f <func4_2+0x46>
    1675:	89 f3                	mov    %esi,%ebx
    1677:	45 89 c6             	mov    %r8d,%r14d
    167a:	44 8d 7f ff          	lea    -0x1(%rdi),%r15d
    167e:	44 89 ff             	mov    %r15d,%edi
    1681:	e8 ad ff ff ff       	call   1633 <func4_1>
    1686:	39 d8                	cmp    %ebx,%eax
    1688:	7d 2f                	jge    16b9 <func4_2+0x60>
    168a:	8d 50 01             	lea    0x1(%rax),%edx
    168d:	39 da                	cmp    %ebx,%edx
    168f:	75 43                	jne    16d4 <func4_2+0x7b>
    1691:	44 88 65 00          	mov    %r12b,0x0(%rbp)
    1695:	44 88 6d 01          	mov    %r13b,0x1(%rbp)
    1699:	c6 45 02 00          	movb   $0x0,0x2(%rbp)
    169d:	eb 0b                	jmp    16aa <func4_2+0x51>
    169f:	88 55 00             	mov    %dl,0x0(%rbp)
    16a2:	88 4d 01             	mov    %cl,0x1(%rbp)
    16a5:	41 c6 41 02 00       	movb   $0x0,0x2(%r9)
    16aa:	48 83 c4 08          	add    $0x8,%rsp
    16ae:	5b                   	pop    %rbx
    16af:	5d                   	pop    %rbp
    16b0:	41 5c                	pop    %r12
    16b2:	41 5d                	pop    %r13
    16b4:	41 5e                	pop    %r14
    16b6:	41 5f                	pop    %r15
    16b8:	c3                   	ret
    16b9:	41 0f be ce          	movsbl %r14b,%ecx
    16bd:	41 0f be d4          	movsbl %r12b,%edx
    16c1:	49 89 e9             	mov    %rbp,%r9
    16c4:	45 0f be c5          	movsbl %r13b,%r8d
    16c8:	89 de                	mov    %ebx,%esi
    16ca:	44 89 ff             	mov    %r15d,%edi
    16cd:	e8 87 ff ff ff       	call   1659 <func4_2>
    16d2:	eb d6                	jmp    16aa <func4_2+0x51>
    16d4:	41 0f be cd          	movsbl %r13b,%ecx
    16d8:	41 0f be d6          	movsbl %r14b,%edx
    16dc:	29 c3                	sub    %eax,%ebx
    16de:	8d 73 ff             	lea    -0x1(%rbx),%esi
    16e1:	49 89 e9             	mov    %rbp,%r9
    16e4:	45 0f be c4          	movsbl %r12b,%r8d
    16e8:	44 89 ff             	mov    %r15d,%edi
    16eb:	e8 69 ff ff ff       	call   1659 <func4_2>
    16f0:	eb b8                	jmp    16aa <func4_2+0x51>

00000000000016f2 <phase_4>:
    16f2:	53                   	push   %rbx
    16f3:	48 83 ec 20          	sub    $0x20,%rsp
    16f7:	64 48 8b 04 25 28 00 	mov    %fs:0x28,%rax
    16fe:	00 00 
    1700:	48 89 44 24 18       	mov    %rax,0x18(%rsp)
    1705:	31 c0                	xor    %eax,%eax
    1707:	48 8d 4c 24 10       	lea    0x10(%rsp),%rcx
    170c:	48 8d 54 24 0c       	lea    0xc(%rsp),%rdx
    1711:	48 8d 35 d5 1a 00 00 	lea    0x1ad5(%rip),%rsi        # 31ed <_IO_stdin_used+0x1ed>
    1718:	e8 33 fa ff ff       	call   1150 <__isoc99_sscanf@plt>
    171d:	83 f8 02             	cmp    $0x2,%eax
    1720:	75 6d                	jne    178f <phase_4+0x9d>
    1722:	bf 05 00 00 00       	mov    $0x5,%edi
    1727:	e8 07 ff ff ff       	call   1633 <func4_1>
    172c:	39 44 24 0c          	cmp    %eax,0xc(%rsp)
    1730:	75 64                	jne    1796 <phase_4+0xa4>
    1732:	48 8d 7c 24 10       	lea    0x10(%rsp),%rdi
    1737:	e8 23 05 00 00       	call   1c5f <string_length>
    173c:	83 f8 02             	cmp    $0x2,%eax
    173f:	75 5c                	jne    179d <phase_4+0xab>
    1741:	48 8d 5c 24 14       	lea    0x14(%rsp),%rbx
    1746:	49 89 d9             	mov    %rbx,%r9
    1749:	41 b8 42 00 00 00    	mov    $0x42,%r8d
    174f:	b9 43 00 00 00       	mov    $0x43,%ecx
    1754:	ba 41 00 00 00       	mov    $0x41,%edx
    1759:	be 16 00 00 00       	mov    $0x16,%esi
    175e:	bf 05 00 00 00       	mov    $0x5,%edi
    1763:	e8 f1 fe ff ff       	call   1659 <func4_2>
    1768:	48 8d 7c 24 10       	lea    0x10(%rsp),%rdi
    176d:	48 89 de             	mov    %rbx,%rsi
    1770:	e8 07 05 00 00       	call   1c7c <strings_not_equal>
    1775:	85 c0                	test   %eax,%eax
    1777:	75 2b                	jne    17a4 <phase_4+0xb2>
    1779:	48 8b 44 24 18       	mov    0x18(%rsp),%rax
    177e:	64 48 2b 04 25 28 00 	sub    %fs:0x28,%rax
    1785:	00 00 
    1787:	75 22                	jne    17ab <phase_4+0xb9>
    1789:	48 83 c4 20          	add    $0x20,%rsp
    178d:	5b                   	pop    %rbx
    178e:	c3                   	ret
    178f:	e8 4d 07 00 00       	call   1ee1 <explode_bomb>
    1794:	eb 8c                	jmp    1722 <phase_4+0x30>
    1796:	e8 46 07 00 00       	call   1ee1 <explode_bomb>
    179b:	eb 95                	jmp    1732 <phase_4+0x40>
    179d:	e8 3f 07 00 00       	call   1ee1 <explode_bomb>
    17a2:	eb 9d                	jmp    1741 <phase_4+0x4f>
    17a4:	e8 38 07 00 00       	call   1ee1 <explode_bomb>
    17a9:	eb ce                	jmp    1779 <phase_4+0x87>
    17ab:	e8 f0 f8 ff ff       	call   10a0 <__stack_chk_fail@plt>

00000000000017b0 <phase_5>:
    17b0:	53                   	push   %rbx
    17b1:	48 83 ec 10          	sub    $0x10,%rsp
    17b5:	48 89 fb             	mov    %rdi,%rbx
    17b8:	64 48 8b 04 25 28 00 	mov    %fs:0x28,%rax
    17bf:	00 00 
    17c1:	48 89 44 24 08       	mov    %rax,0x8(%rsp)
    17c6:	31 c0                	xor    %eax,%eax
    17c8:	e8 92 04 00 00       	call   1c5f <string_length>
    17cd:	83 f8 06             	cmp    $0x6,%eax
    17d0:	75 58                	jne    182a <phase_5+0x7a>
    17d2:	ba 00 00 00 00       	mov    $0x0,%edx
    17d7:	48 8d 0d 62 1a 00 00 	lea    0x1a62(%rip),%rcx        # 3240 <array.0>
    17de:	0f be 04 13          	movsbl (%rbx,%rdx,1),%eax
    17e2:	83 c0 0f             	add    $0xf,%eax
    17e5:	83 e0 0f             	and    $0xf,%eax
    17e8:	0f b6 04 01          	movzbl (%rcx,%rax,1),%eax
    17ec:	88 44 14 01          	mov    %al,0x1(%rsp,%rdx,1)
    17f0:	48 83 c2 01          	add    $0x1,%rdx
    17f4:	48 83 fa 06          	cmp    $0x6,%rdx
    17f8:	75 e4                	jne    17de <phase_5+0x2e>
    17fa:	c6 44 24 07 00       	movb   $0x0,0x7(%rsp)
    17ff:	48 8d 7c 24 01       	lea    0x1(%rsp),%rdi
    1804:	48 8d 35 e9 19 00 00 	lea    0x19e9(%rip),%rsi        # 31f4 <_IO_stdin_used+0x1f4>
    180b:	e8 6c 04 00 00       	call   1c7c <strings_not_equal>
    1810:	85 c0                	test   %eax,%eax
    1812:	75 1d                	jne    1831 <phase_5+0x81>
    1814:	48 8b 44 24 08       	mov    0x8(%rsp),%rax
    1819:	64 48 2b 04 25 28 00 	sub    %fs:0x28,%rax
    1820:	00 00 
    1822:	75 14                	jne    1838 <phase_5+0x88>
    1824:	48 83 c4 10          	add    $0x10,%rsp
    1828:	5b                   	pop    %rbx
    1829:	c3                   	ret
    182a:	e8 b2 06 00 00       	call   1ee1 <explode_bomb>
    182f:	eb a1                	jmp    17d2 <phase_5+0x22>
    1831:	e8 ab 06 00 00       	call   1ee1 <explode_bomb>
    1836:	eb dc                	jmp    1814 <phase_5+0x64>
    1838:	e8 63 f8 ff ff       	call   10a0 <__stack_chk_fail@plt>

000000000000183d <phase_6>:
    183d:	41 56                	push   %r14
    183f:	41 55                	push   %r13
    1841:	41 54                	push   %r12
    1843:	55                   	push   %rbp
    1844:	53                   	push   %rbx
    1845:	48 83 ec 60          	sub    $0x60,%rsp
    1849:	64 48 8b 04 25 28 00 	mov    %fs:0x28,%rax
    1850:	00 00 
    1852:	48 89 44 24 58       	mov    %rax,0x58(%rsp)
    1857:	31 c0                	xor    %eax,%eax
    1859:	49 89 e5             	mov    %rsp,%r13
    185c:	4c 89 ee             	mov    %r13,%rsi
    185f:	e8 3d 07 00 00       	call   1fa1 <read_six_numbers>
    1864:	41 be 01 00 00 00    	mov    $0x1,%r14d
    186a:	49 89 e4             	mov    %rsp,%r12
    186d:	eb 28                	jmp    1897 <phase_6+0x5a>
    186f:	e8 6d 06 00 00       	call   1ee1 <explode_bomb>
    1874:	eb 30                	jmp    18a6 <phase_6+0x69>
    1876:	48 83 c3 01          	add    $0x1,%rbx
    187a:	83 fb 05             	cmp    $0x5,%ebx
    187d:	7f 10                	jg     188f <phase_6+0x52>
    187f:	41 8b 04 9c          	mov    (%r12,%rbx,4),%eax
    1883:	39 45 00             	cmp    %eax,0x0(%rbp)
    1886:	75 ee                	jne    1876 <phase_6+0x39>
    1888:	e8 54 06 00 00       	call   1ee1 <explode_bomb>
    188d:	eb e7                	jmp    1876 <phase_6+0x39>
    188f:	49 83 c6 01          	add    $0x1,%r14
    1893:	49 83 c5 04          	add    $0x4,%r13
    1897:	4c 89 ed             	mov    %r13,%rbp
    189a:	41 8b 45 00          	mov    0x0(%r13),%eax
    189e:	83 e8 01             	sub    $0x1,%eax
    18a1:	83 f8 05             	cmp    $0x5,%eax
    18a4:	77 c9                	ja     186f <phase_6+0x32>
    18a6:	41 83 fe 05          	cmp    $0x5,%r14d
    18aa:	7f 05                	jg     18b1 <phase_6+0x74>
    18ac:	4c 89 f3             	mov    %r14,%rbx
    18af:	eb ce                	jmp    187f <phase_6+0x42>
    18b1:	be 00 00 00 00       	mov    $0x0,%esi
    18b6:	8b 0c b4             	mov    (%rsp,%rsi,4),%ecx
    18b9:	b8 01 00 00 00       	mov    $0x1,%eax
    18be:	48 8d 15 4b 39 00 00 	lea    0x394b(%rip),%rdx        # 5210 <node1>
    18c5:	83 f9 01             	cmp    $0x1,%ecx
    18c8:	7e 0b                	jle    18d5 <phase_6+0x98>
    18ca:	48 8b 52 08          	mov    0x8(%rdx),%rdx
    18ce:	83 c0 01             	add    $0x1,%eax
    18d1:	39 c8                	cmp    %ecx,%eax
    18d3:	75 f5                	jne    18ca <phase_6+0x8d>
    18d5:	48 89 54 f4 20       	mov    %rdx,0x20(%rsp,%rsi,8)
    18da:	48 83 c6 01          	add    $0x1,%rsi
    18de:	48 83 fe 06          	cmp    $0x6,%rsi
    18e2:	75 d2                	jne    18b6 <phase_6+0x79>
    18e4:	48 8b 5c 24 20       	mov    0x20(%rsp),%rbx
    18e9:	48 8b 44 24 28       	mov    0x28(%rsp),%rax
    18ee:	48 89 43 08          	mov    %rax,0x8(%rbx)
    18f2:	48 8b 54 24 30       	mov    0x30(%rsp),%rdx
    18f7:	48 89 50 08          	mov    %rdx,0x8(%rax)
    18fb:	48 8b 44 24 38       	mov    0x38(%rsp),%rax
    1900:	48 89 42 08          	mov    %rax,0x8(%rdx)
    1904:	48 8b 54 24 40       	mov    0x40(%rsp),%rdx
    1909:	48 89 50 08          	mov    %rdx,0x8(%rax)
    190d:	48 8b 44 24 48       	mov    0x48(%rsp),%rax
    1912:	48 89 42 08          	mov    %rax,0x8(%rdx)
    1916:	48 c7 40 08 00 00 00 	movq   $0x0,0x8(%rax)
    191d:	00 
    191e:	bd 05 00 00 00       	mov    $0x5,%ebp
    1923:	eb 09                	jmp    192e <phase_6+0xf1>
    1925:	48 8b 5b 08          	mov    0x8(%rbx),%rbx
    1929:	83 ed 01             	sub    $0x1,%ebp
    192c:	74 11                	je     193f <phase_6+0x102>
    192e:	48 8b 43 08          	mov    0x8(%rbx),%rax
    1932:	8b 00                	mov    (%rax),%eax
    1934:	39 03                	cmp    %eax,(%rbx)
    1936:	7e ed                	jle    1925 <phase_6+0xe8>
    1938:	e8 a4 05 00 00       	call   1ee1 <explode_bomb>
    193d:	eb e6                	jmp    1925 <phase_6+0xe8>
    193f:	48 8b 44 24 58       	mov    0x58(%rsp),%rax
    1944:	64 48 2b 04 25 28 00 	sub    %fs:0x28,%rax
    194b:	00 00 
    194d:	75 0d                	jne    195c <phase_6+0x11f>
    194f:	48 83 c4 60          	add    $0x60,%rsp
    1953:	5b                   	pop    %rbx
    1954:	5d                   	pop    %rbp
    1955:	41 5c                	pop    %r12
    1957:	41 5d                	pop    %r13
    1959:	41 5e                	pop    %r14
    195b:	c3                   	ret
    195c:	e8 3f f7 ff ff       	call   10a0 <__stack_chk_fail@plt>

0000000000001961 <func7>:
    1961:	48 81 ec 98 00 00 00 	sub    $0x98,%rsp
    1968:	89 f0                	mov    %esi,%eax
    196a:	41 89 c9             	mov    %ecx,%r9d
    196d:	64 48 8b 0c 25 28 00 	mov    %fs:0x28,%rcx
    1974:	00 00 
    1976:	48 89 8c 24 88 00 00 	mov    %rcx,0x88(%rsp)
    197d:	00 
    197e:	31 c9                	xor    %ecx,%ecx
    1980:	c7 04 24 fe ff ff ff 	movl   $0xfffffffe,(%rsp)
    1987:	c7 44 24 04 ff ff ff 	movl   $0xffffffff,0x4(%rsp)
    198e:	ff 
    198f:	c7 44 24 08 01 00 00 	movl   $0x1,0x8(%rsp)
    1996:	00 
    1997:	c7 44 24 0c 02 00 00 	movl   $0x2,0xc(%rsp)
    199e:	00 
    199f:	c7 44 24 10 02 00 00 	movl   $0x2,0x10(%rsp)
    19a6:	00 
    19a7:	c7 44 24 14 01 00 00 	movl   $0x1,0x14(%rsp)
    19ae:	00 
    19af:	c7 44 24 18 ff ff ff 	movl   $0xffffffff,0x18(%rsp)
    19b6:	ff 
    19b7:	c7 44 24 1c fe ff ff 	movl   $0xfffffffe,0x1c(%rsp)
    19be:	ff 
    19bf:	c7 44 24 20 01 00 00 	movl   $0x1,0x20(%rsp)
    19c6:	00 
    19c7:	c7 44 24 24 02 00 00 	movl   $0x2,0x24(%rsp)
    19ce:	00 
    19cf:	c7 44 24 28 02 00 00 	movl   $0x2,0x28(%rsp)
    19d6:	00 
    19d7:	c7 44 24 2c 01 00 00 	movl   $0x1,0x2c(%rsp)
    19de:	00 
    19df:	c7 44 24 30 ff ff ff 	movl   $0xffffffff,0x30(%rsp)
    19e6:	ff 
    19e7:	c7 44 24 34 fe ff ff 	movl   $0xfffffffe,0x34(%rsp)
    19ee:	ff 
    19ef:	c7 44 24 38 fe ff ff 	movl   $0xfffffffe,0x38(%rsp)
    19f6:	ff 
    19f7:	c7 44 24 3c ff ff ff 	movl   $0xffffffff,0x3c(%rsp)
    19fe:	ff 
    19ff:	c7 44 24 40 ff ff ff 	movl   $0xffffffff,0x40(%rsp)
    1a06:	ff 
    1a07:	c7 44 24 44 00 00 00 	movl   $0x0,0x44(%rsp)
    1a0e:	00 
    1a0f:	c7 44 24 48 00 00 00 	movl   $0x0,0x48(%rsp)
    1a16:	00 
    1a17:	c7 44 24 4c 01 00 00 	movl   $0x1,0x4c(%rsp)
    1a1e:	00 
    1a1f:	c7 44 24 50 01 00 00 	movl   $0x1,0x50(%rsp)
    1a26:	00 
    1a27:	c7 44 24 54 00 00 00 	movl   $0x0,0x54(%rsp)
    1a2e:	00 
    1a2f:	c7 44 24 58 00 00 00 	movl   $0x0,0x58(%rsp)
    1a36:	00 
    1a37:	c7 44 24 5c ff ff ff 	movl   $0xffffffff,0x5c(%rsp)
    1a3e:	ff 
    1a3f:	c7 44 24 60 00 00 00 	movl   $0x0,0x60(%rsp)
    1a46:	00 
    1a47:	c7 44 24 64 01 00 00 	movl   $0x1,0x64(%rsp)
    1a4e:	00 
    1a4f:	c7 44 24 68 01 00 00 	movl   $0x1,0x68(%rsp)
    1a56:	00 
    1a57:	c7 44 24 6c 00 00 00 	movl   $0x0,0x6c(%rsp)
    1a5e:	00 
    1a5f:	c7 44 24 70 00 00 00 	movl   $0x0,0x70(%rsp)
    1a66:	00 
    1a67:	c7 44 24 74 ff ff ff 	movl   $0xffffffff,0x74(%rsp)
    1a6e:	ff 
    1a6f:	c7 44 24 78 ff ff ff 	movl   $0xffffffff,0x78(%rsp)
    1a76:	ff 
    1a77:	c7 44 24 7c 00 00 00 	movl   $0x0,0x7c(%rsp)
    1a7e:	00 
    1a7f:	83 fe 04             	cmp    $0x4,%esi
    1a82:	75 6b                	jne    1aef <func7+0x18e>
    1a84:	83 fa 07             	cmp    $0x7,%edx
    1a87:	75 66                	jne    1aef <func7+0x18e>
    1a89:	49 63 c9             	movslq %r9d,%rcx
    1a8c:	0f b6 34 0f          	movzbl (%rdi,%rcx,1),%esi
    1a90:	b9 01 00 00 00       	mov    $0x1,%ecx
    1a95:	40 84 f6             	test   %sil,%sil
    1a98:	74 34                	je     1ace <func7+0x16d>
    1a9a:	b9 00 00 00 00       	mov    $0x0,%ecx
    1a9f:	41 83 f9 13          	cmp    $0x13,%r9d
    1aa3:	7f 29                	jg     1ace <func7+0x16d>
    1aa5:	41 89 f2             	mov    %esi,%r10d
    1aa8:	41 83 e2 07          	and    $0x7,%r10d
    1aac:	83 e6 07             	and    $0x7,%esi
    1aaf:	41 89 c0             	mov    %eax,%r8d
    1ab2:	44 03 04 b4          	add    (%rsp,%rsi,4),%r8d
    1ab6:	41 89 d3             	mov    %edx,%r11d
    1ab9:	44 03 5c b4 20       	add    0x20(%rsp,%rsi,4),%r11d
    1abe:	44 89 c6             	mov    %r8d,%esi
    1ac1:	44 09 de             	or     %r11d,%esi
    1ac4:	b9 00 00 00 00       	mov    $0x0,%ecx
    1ac9:	83 fe 07             	cmp    $0x7,%esi
    1acc:	76 3f                	jbe    1b0d <func7+0x1ac>
    1ace:	48 8b 84 24 88 00 00 	mov    0x88(%rsp),%rax
    1ad5:	00 
    1ad6:	64 48 2b 04 25 28 00 	sub    %fs:0x28,%rax
    1add:	00 00 
    1adf:	0f 85 9e 00 00 00    	jne    1b83 <func7+0x222>
    1ae5:	89 c8                	mov    %ecx,%eax
    1ae7:	48 81 c4 98 00 00 00 	add    $0x98,%rsp
    1aee:	c3                   	ret
    1aef:	b9 00 00 00 00       	mov    $0x0,%ecx
    1af4:	41 83 f9 13          	cmp    $0x13,%r9d
    1af8:	7f d4                	jg     1ace <func7+0x16d>
    1afa:	49 63 c9             	movslq %r9d,%rcx
    1afd:	0f b6 34 0f          	movzbl (%rdi,%rcx,1),%esi
    1b01:	b9 00 00 00 00       	mov    $0x0,%ecx
    1b06:	40 84 f6             	test   %sil,%sil
    1b09:	74 c3                	je     1ace <func7+0x16d>
    1b0b:	eb 98                	jmp    1aa5 <func7+0x144>
    1b0d:	4d 63 d2             	movslq %r10d,%r10
    1b10:	42 03 44 94 40       	add    0x40(%rsp,%r10,4),%eax
    1b15:	42 03 54 94 60       	add    0x60(%rsp,%r10,4),%edx
    1b1a:	48 8d 35 7f 36 00 00 	lea    0x367f(%rip),%rsi        # 51a0 <row0>
    1b21:	85 c0                	test   %eax,%eax
    1b23:	7e 0b                	jle    1b30 <func7+0x1cf>
    1b25:	48 8b 76 08          	mov    0x8(%rsi),%rsi
    1b29:	83 c1 01             	add    $0x1,%ecx
    1b2c:	39 c8                	cmp    %ecx,%eax
    1b2e:	75 f5                	jne    1b25 <func7+0x1c4>
    1b30:	48 63 d2             	movslq %edx,%rdx
    1b33:	b9 00 00 00 00       	mov    $0x0,%ecx
    1b38:	80 3c 16 01          	cmpb   $0x1,(%rsi,%rdx,1)
    1b3c:	74 90                	je     1ace <func7+0x16d>
    1b3e:	48 8d 15 5b 36 00 00 	lea    0x365b(%rip),%rdx        # 51a0 <row0>
    1b45:	45 85 c0             	test   %r8d,%r8d
    1b48:	7e 11                	jle    1b5b <func7+0x1fa>
    1b4a:	b8 00 00 00 00       	mov    $0x0,%eax
    1b4f:	48 8b 52 08          	mov    0x8(%rdx),%rdx
    1b53:	83 c0 01             	add    $0x1,%eax
    1b56:	41 39 c0             	cmp    %eax,%r8d
    1b59:	75 f4                	jne    1b4f <func7+0x1ee>
    1b5b:	49 63 c3             	movslq %r11d,%rax
    1b5e:	b9 00 00 00 00       	mov    $0x0,%ecx
    1b63:	80 3c 02 01          	cmpb   $0x1,(%rdx,%rax,1)
    1b67:	0f 84 61 ff ff ff    	je     1ace <func7+0x16d>
    1b6d:	41 8d 49 01          	lea    0x1(%r9),%ecx
    1b71:	44 89 da             	mov    %r11d,%edx
    1b74:	44 89 c6             	mov    %r8d,%esi
    1b77:	e8 e5 fd ff ff       	call   1961 <func7>
    1b7c:	89 c1                	mov    %eax,%ecx
    1b7e:	e9 4b ff ff ff       	jmp    1ace <func7+0x16d>
    1b83:	e8 18 f5 ff ff       	call   10a0 <__stack_chk_fail@plt>

0000000000001b88 <secret_phase>:
    1b88:	53                   	push   %rbx
    1b89:	48 8d 3d 6b 16 00 00 	lea    0x166b(%rip),%rdi        # 31fb <_IO_stdin_used+0x1fb>
    1b90:	e8 db f4 ff ff       	call   1070 <puts@plt>
    1b95:	e8 48 04 00 00       	call   1fe2 <read_line>
    1b9a:	48 89 c3             	mov    %rax,%rbx
    1b9d:	48 89 c7             	mov    %rax,%rdi
    1ba0:	e8 ba 00 00 00       	call   1c5f <string_length>
    1ba5:	83 f8 14             	cmp    $0x14,%eax
    1ba8:	7f 2e                	jg     1bd8 <secret_phase+0x50>
    1baa:	b9 00 00 00 00       	mov    $0x0,%ecx
    1baf:	ba 00 00 00 00       	mov    $0x0,%edx
    1bb4:	be 00 00 00 00       	mov    $0x0,%esi
    1bb9:	48 89 df             	mov    %rbx,%rdi
    1bbc:	e8 a0 fd ff ff       	call   1961 <func7>
    1bc1:	85 c0                	test   %eax,%eax
    1bc3:	74 1a                	je     1bdf <secret_phase+0x57>
    1bc5:	48 8d 3d ec 15 00 00 	lea    0x15ec(%rip),%rdi        # 31b8 <_IO_stdin_used+0x1b8>
    1bcc:	e8 9f f4 ff ff       	call   1070 <puts@plt>
    1bd1:	e8 46 05 00 00       	call   211c <phase_defused>
    1bd6:	5b                   	pop    %rbx
    1bd7:	c3                   	ret
    1bd8:	e8 04 03 00 00       	call   1ee1 <explode_bomb>
    1bdd:	eb cb                	jmp    1baa <secret_phase+0x22>
    1bdf:	e8 fd 02 00 00       	call   1ee1 <explode_bomb>
    1be4:	eb df                	jmp    1bc5 <secret_phase+0x3d>

0000000000001be6 <sig_handler>:
    1be6:	48 83 ec 08          	sub    $0x8,%rsp
    1bea:	48 8d 3d 5f 16 00 00 	lea    0x165f(%rip),%rdi        # 3250 <array.0+0x10>
    1bf1:	e8 7a f4 ff ff       	call   1070 <puts@plt>
    1bf6:	bf 03 00 00 00       	mov    $0x3,%edi
    1bfb:	e8 b0 f5 ff ff       	call   11b0 <sleep@plt>
    1c00:	48 8d 3d c2 17 00 00 	lea    0x17c2(%rip),%rdi        # 33c9 <array.0+0x189>
    1c07:	b8 00 00 00 00       	mov    $0x0,%eax
    1c0c:	e8 9f f4 ff ff       	call   10b0 <printf@plt>
    1c11:	48 8b 3d 48 3a 00 00 	mov    0x3a48(%rip),%rdi        # 5660 <stdout@GLIBC_2.2.5>
    1c18:	e8 23 f5 ff ff       	call   1140 <fflush@plt>
    1c1d:	bf 01 00 00 00       	mov    $0x1,%edi
    1c22:	e8 89 f5 ff ff       	call   11b0 <sleep@plt>
    1c27:	48 8d 3d a3 17 00 00 	lea    0x17a3(%rip),%rdi        # 33d1 <array.0+0x191>
    1c2e:	e8 3d f4 ff ff       	call   1070 <puts@plt>
    1c33:	bf 10 00 00 00       	mov    $0x10,%edi
    1c38:	e8 53 f5 ff ff       	call   1190 <exit@plt>

0000000000001c3d <invalid_phase>:
    1c3d:	48 83 ec 08          	sub    $0x8,%rsp
    1c41:	48 89 fe             	mov    %rdi,%rsi
    1c44:	48 8d 3d 90 17 00 00 	lea    0x1790(%rip),%rdi        # 33db <array.0+0x19b>
    1c4b:	b8 00 00 00 00       	mov    $0x0,%eax
    1c50:	e8 5b f4 ff ff       	call   10b0 <printf@plt>
    1c55:	bf 08 00 00 00       	mov    $0x8,%edi
    1c5a:	e8 31 f5 ff ff       	call   1190 <exit@plt>

0000000000001c5f <string_length>:
    1c5f:	80 3f 00             	cmpb   $0x0,(%rdi)
    1c62:	74 12                	je     1c76 <string_length+0x17>
    1c64:	b8 00 00 00 00       	mov    $0x0,%eax
    1c69:	48 83 c7 01          	add    $0x1,%rdi
    1c6d:	83 c0 01             	add    $0x1,%eax
    1c70:	80 3f 00             	cmpb   $0x0,(%rdi)
    1c73:	75 f4                	jne    1c69 <string_length+0xa>
    1c75:	c3                   	ret
    1c76:	b8 00 00 00 00       	mov    $0x0,%eax
    1c7b:	c3                   	ret

0000000000001c7c <strings_not_equal>:
    1c7c:	41 54                	push   %r12
    1c7e:	55                   	push   %rbp
    1c7f:	53                   	push   %rbx
    1c80:	48 89 fb             	mov    %rdi,%rbx
    1c83:	48 89 f5             	mov    %rsi,%rbp
    1c86:	e8 d4 ff ff ff       	call   1c5f <string_length>
    1c8b:	41 89 c4             	mov    %eax,%r12d
    1c8e:	48 89 ef             	mov    %rbp,%rdi
    1c91:	e8 c9 ff ff ff       	call   1c5f <string_length>
    1c96:	89 c2                	mov    %eax,%edx
    1c98:	b8 01 00 00 00       	mov    $0x1,%eax
    1c9d:	41 39 d4             	cmp    %edx,%r12d
    1ca0:	75 31                	jne    1cd3 <strings_not_equal+0x57>
    1ca2:	0f b6 13             	movzbl (%rbx),%edx
    1ca5:	84 d2                	test   %dl,%dl
    1ca7:	74 1e                	je     1cc7 <strings_not_equal+0x4b>
    1ca9:	b8 00 00 00 00       	mov    $0x0,%eax
    1cae:	38 54 05 00          	cmp    %dl,0x0(%rbp,%rax,1)
    1cb2:	75 1a                	jne    1cce <strings_not_equal+0x52>
    1cb4:	48 83 c0 01          	add    $0x1,%rax
    1cb8:	0f b6 14 03          	movzbl (%rbx,%rax,1),%edx
    1cbc:	84 d2                	test   %dl,%dl
    1cbe:	75 ee                	jne    1cae <strings_not_equal+0x32>
    1cc0:	b8 00 00 00 00       	mov    $0x0,%eax
    1cc5:	eb 0c                	jmp    1cd3 <strings_not_equal+0x57>
    1cc7:	b8 00 00 00 00       	mov    $0x0,%eax
    1ccc:	eb 05                	jmp    1cd3 <strings_not_equal+0x57>
    1cce:	b8 01 00 00 00       	mov    $0x1,%eax
    1cd3:	5b                   	pop    %rbx
    1cd4:	5d                   	pop    %rbp
    1cd5:	41 5c                	pop    %r12
    1cd7:	c3                   	ret

0000000000001cd8 <initialize_bomb>:
    1cd8:	55                   	push   %rbp
    1cd9:	53                   	push   %rbx
    1cda:	48 83 ec 58          	sub    $0x58,%rsp
    1cde:	64 48 8b 04 25 28 00 	mov    %fs:0x28,%rax
    1ce5:	00 00 
    1ce7:	48 89 44 24 48       	mov    %rax,0x48(%rsp)
    1cec:	31 c0                	xor    %eax,%eax
    1cee:	48 8d 35 f1 fe ff ff 	lea    -0x10f(%rip),%rsi        # 1be6 <sig_handler>
    1cf5:	bf 02 00 00 00       	mov    $0x2,%edi
    1cfa:	e8 11 f4 ff ff       	call   1110 <signal@plt>
    1cff:	48 8b 3d 5a 35 00 00 	mov    0x355a(%rip),%rdi        # 5260 <host_table>
    1d06:	48 85 ff             	test   %rdi,%rdi
    1d09:	74 23                	je     1d2e <initialize_bomb+0x56>
    1d0b:	48 8d 1d 56 35 00 00 	lea    0x3556(%rip),%rbx        # 5268 <host_table+0x8>
    1d12:	48 89 e5             	mov    %rsp,%rbp
    1d15:	48 89 ee             	mov    %rbp,%rsi
    1d18:	e8 23 f3 ff ff       	call   1040 <strcasecmp@plt>
    1d1d:	85 c0                	test   %eax,%eax
    1d1f:	74 0d                	je     1d2e <initialize_bomb+0x56>
    1d21:	48 83 c3 08          	add    $0x8,%rbx
    1d25:	48 8b 7b f8          	mov    -0x8(%rbx),%rdi
    1d29:	48 85 ff             	test   %rdi,%rdi
    1d2c:	75 e7                	jne    1d15 <initialize_bomb+0x3d>
    1d2e:	48 8d 3d b7 16 00 00 	lea    0x16b7(%rip),%rdi        # 33ec <array.0+0x1ac>
    1d35:	e8 36 f3 ff ff       	call   1070 <puts@plt>
    1d3a:	48 8d 3d b7 16 00 00 	lea    0x16b7(%rip),%rdi        # 33f8 <array.0+0x1b8>
    1d41:	e8 2a f3 ff ff       	call   1070 <puts@plt>
    1d46:	48 8d 3d b7 16 00 00 	lea    0x16b7(%rip),%rdi        # 3404 <array.0+0x1c4>
    1d4d:	e8 1e f3 ff ff       	call   1070 <puts@plt>
    1d52:	48 8d 3d b7 16 00 00 	lea    0x16b7(%rip),%rdi        # 3410 <array.0+0x1d0>
    1d59:	e8 12 f3 ff ff       	call   1070 <puts@plt>
    1d5e:	48 8d 3d b7 16 00 00 	lea    0x16b7(%rip),%rdi        # 341c <array.0+0x1dc>
    1d65:	e8 06 f3 ff ff       	call   1070 <puts@plt>
    1d6a:	48 8b 44 24 48       	mov    0x48(%rsp),%rax
    1d6f:	64 48 2b 04 25 28 00 	sub    %fs:0x28,%rax
    1d76:	00 00 
    1d78:	75 07                	jne    1d81 <initialize_bomb+0xa9>
    1d7a:	48 83 c4 58          	add    $0x58,%rsp
    1d7e:	5b                   	pop    %rbx
    1d7f:	5d                   	pop    %rbp
    1d80:	c3                   	ret
    1d81:	e8 1a f3 ff ff       	call   10a0 <__stack_chk_fail@plt>

0000000000001d86 <initialize_bomb_solve>:
    1d86:	c3                   	ret

0000000000001d87 <blank_line>:
    1d87:	55                   	push   %rbp
    1d88:	53                   	push   %rbx
    1d89:	48 83 ec 08          	sub    $0x8,%rsp
    1d8d:	48 89 fd             	mov    %rdi,%rbp
    1d90:	0f b6 5d 00          	movzbl 0x0(%rbp),%ebx
    1d94:	84 db                	test   %bl,%bl
    1d96:	74 1e                	je     1db6 <blank_line+0x2f>
    1d98:	e8 23 f4 ff ff       	call   11c0 <__ctype_b_loc@plt>
    1d9d:	48 83 c5 01          	add    $0x1,%rbp
    1da1:	48 0f be db          	movsbq %bl,%rbx
    1da5:	48 8b 00             	mov    (%rax),%rax
    1da8:	f6 44 58 01 20       	testb  $0x20,0x1(%rax,%rbx,2)
    1dad:	75 e1                	jne    1d90 <blank_line+0x9>
    1daf:	b8 00 00 00 00       	mov    $0x0,%eax
    1db4:	eb 05                	jmp    1dbb <blank_line+0x34>
    1db6:	b8 01 00 00 00       	mov    $0x1,%eax
    1dbb:	48 83 c4 08          	add    $0x8,%rsp
    1dbf:	5b                   	pop    %rbx
    1dc0:	5d                   	pop    %rbp
    1dc1:	c3                   	ret

0000000000001dc2 <skip>:
    1dc2:	55                   	push   %rbp
    1dc3:	53                   	push   %rbx
    1dc4:	48 83 ec 08          	sub    $0x8,%rsp
    1dc8:	48 8d 2d 51 39 00 00 	lea    0x3951(%rip),%rbp        # 5720 <input_strings>
    1dcf:	48 63 15 42 39 00 00 	movslq 0x3942(%rip),%rdx        # 5718 <num_input_strings>
    1dd6:	48 89 d0             	mov    %rdx,%rax
    1dd9:	48 c1 e0 04          	shl    $0x4,%rax
    1ddd:	48 29 d0             	sub    %rdx,%rax
    1de0:	48 8d 7c c5 00       	lea    0x0(%rbp,%rax,8),%rdi
    1de5:	48 8b 15 a4 38 00 00 	mov    0x38a4(%rip),%rdx        # 5690 <infile>
    1dec:	be 78 00 00 00       	mov    $0x78,%esi
    1df1:	e8 fa f2 ff ff       	call   10f0 <fgets@plt>
    1df6:	48 89 c3             	mov    %rax,%rbx
    1df9:	48 85 c0             	test   %rax,%rax
    1dfc:	74 0c                	je     1e0a <skip+0x48>
    1dfe:	48 89 c7             	mov    %rax,%rdi
    1e01:	e8 81 ff ff ff       	call   1d87 <blank_line>
    1e06:	85 c0                	test   %eax,%eax
    1e08:	75 c5                	jne    1dcf <skip+0xd>
    1e0a:	48 89 d8             	mov    %rbx,%rax
    1e0d:	48 83 c4 08          	add    $0x8,%rsp
    1e11:	5b                   	pop    %rbx
    1e12:	5d                   	pop    %rbp
    1e13:	c3                   	ret

0000000000001e14 <send_msg>:
    1e14:	53                   	push   %rbx
    1e15:	48 81 ec 10 40 00 00 	sub    $0x4010,%rsp
    1e1c:	64 48 8b 04 25 28 00 	mov    %fs:0x28,%rax
    1e23:	00 00 
    1e25:	48 89 84 24 08 40 00 	mov    %rax,0x4008(%rsp)
    1e2c:	00 
    1e2d:	31 c0                	xor    %eax,%eax
    1e2f:	44 8b 05 e2 38 00 00 	mov    0x38e2(%rip),%r8d        # 5718 <num_input_strings>
    1e36:	41 8d 40 ff          	lea    -0x1(%r8),%eax
    1e3a:	48 98                	cltq
    1e3c:	48 89 c2             	mov    %rax,%rdx
    1e3f:	48 c1 e2 04          	shl    $0x4,%rdx
    1e43:	48 29 c2             	sub    %rax,%rdx
    1e46:	85 ff                	test   %edi,%edi
    1e48:	48 8d 0d d9 15 00 00 	lea    0x15d9(%rip),%rcx        # 3428 <array.0+0x1e8>
    1e4f:	48 8d 05 da 15 00 00 	lea    0x15da(%rip),%rax        # 3430 <array.0+0x1f0>
    1e56:	48 0f 44 c8          	cmove  %rax,%rcx
    1e5a:	48 89 e3             	mov    %rsp,%rbx
    1e5d:	48 8d 05 bc 38 00 00 	lea    0x38bc(%rip),%rax        # 5720 <input_strings>
    1e64:	4c 8d 0c d0          	lea    (%rax,%rdx,8),%r9
    1e68:	8b 15 26 33 00 00    	mov    0x3326(%rip),%edx        # 5194 <bomb_id>
    1e6e:	48 8d 35 c4 15 00 00 	lea    0x15c4(%rip),%rsi        # 3439 <array.0+0x1f9>
    1e75:	48 89 df             	mov    %rbx,%rdi
    1e78:	b8 00 00 00 00       	mov    $0x0,%eax
    1e7d:	e8 fe f2 ff ff       	call   1180 <sprintf@plt>
    1e82:	4c 8d 84 24 00 20 00 	lea    0x2000(%rsp),%r8
    1e89:	00 
    1e8a:	b9 00 00 00 00       	mov    $0x0,%ecx
    1e8f:	48 89 da             	mov    %rbx,%rdx
    1e92:	48 8d 35 d7 32 00 00 	lea    0x32d7(%rip),%rsi        # 5170 <user_password>
    1e99:	48 8d 3d e8 32 00 00 	lea    0x32e8(%rip),%rdi        # 5188 <userid>
    1ea0:	e8 ac 0e 00 00       	call   2d51 <driver_post>
    1ea5:	85 c0                	test   %eax,%eax
    1ea7:	78 1c                	js     1ec5 <send_msg+0xb1>
    1ea9:	48 8b 84 24 08 40 00 	mov    0x4008(%rsp),%rax
    1eb0:	00 
    1eb1:	64 48 2b 04 25 28 00 	sub    %fs:0x28,%rax
    1eb8:	00 00 
    1eba:	75 20                	jne    1edc <send_msg+0xc8>
    1ebc:	48 81 c4 10 40 00 00 	add    $0x4010,%rsp
    1ec3:	5b                   	pop    %rbx
    1ec4:	c3                   	ret
    1ec5:	48 8d bc 24 00 20 00 	lea    0x2000(%rsp),%rdi
    1ecc:	00 
    1ecd:	e8 9e f1 ff ff       	call   1070 <puts@plt>
    1ed2:	bf 00 00 00 00       	mov    $0x0,%edi
    1ed7:	e8 b4 f2 ff ff       	call   1190 <exit@plt>
    1edc:	e8 bf f1 ff ff       	call   10a0 <__stack_chk_fail@plt>

0000000000001ee1 <explode_bomb>:
    1ee1:	48 83 ec 08          	sub    $0x8,%rsp
    1ee5:	48 8d 3d 9c 13 00 00 	lea    0x139c(%rip),%rdi        # 3288 <array.0+0x48>
    1eec:	e8 7f f1 ff ff       	call   1070 <puts@plt>
    1ef1:	48 8d 3d 4d 15 00 00 	lea    0x154d(%rip),%rdi        # 3445 <array.0+0x205>
    1ef8:	e8 73 f1 ff ff       	call   1070 <puts@plt>
    1efd:	48 8d 3d 5e 15 00 00 	lea    0x155e(%rip),%rdi        # 3462 <array.0+0x222>
    1f04:	e8 67 f1 ff ff       	call   1070 <puts@plt>
    1f09:	48 8d 3d 6f 15 00 00 	lea    0x156f(%rip),%rdi        # 347f <array.0+0x23f>
    1f10:	e8 5b f1 ff ff       	call   1070 <puts@plt>
    1f15:	48 8d 3d 80 15 00 00 	lea    0x1580(%rip),%rdi        # 349c <array.0+0x25c>
    1f1c:	e8 4f f1 ff ff       	call   1070 <puts@plt>
    1f21:	48 8d 3d 91 15 00 00 	lea    0x1591(%rip),%rdi        # 34b9 <array.0+0x279>
    1f28:	e8 43 f1 ff ff       	call   1070 <puts@plt>
    1f2d:	48 8d 3d a1 15 00 00 	lea    0x15a1(%rip),%rdi        # 34d5 <array.0+0x295>
    1f34:	e8 37 f1 ff ff       	call   1070 <puts@plt>
    1f39:	48 8d 3d b2 15 00 00 	lea    0x15b2(%rip),%rdi        # 34f2 <array.0+0x2b2>
    1f40:	e8 2b f1 ff ff       	call   1070 <puts@plt>
    1f45:	48 8d 3d c3 15 00 00 	lea    0x15c3(%rip),%rdi        # 350f <array.0+0x2cf>
    1f4c:	e8 1f f1 ff ff       	call   1070 <puts@plt>
    1f51:	48 8d 3d d4 15 00 00 	lea    0x15d4(%rip),%rdi        # 352c <array.0+0x2ec>
    1f58:	e8 13 f1 ff ff       	call   1070 <puts@plt>
    1f5d:	48 8d 3d e5 15 00 00 	lea    0x15e5(%rip),%rdi        # 3549 <array.0+0x309>
    1f64:	e8 07 f1 ff ff       	call   1070 <puts@plt>
    1f69:	48 8d 3d f6 15 00 00 	lea    0x15f6(%rip),%rdi        # 3566 <array.0+0x326>
    1f70:	e8 fb f0 ff ff       	call   1070 <puts@plt>
    1f75:	48 8d 3d 07 16 00 00 	lea    0x1607(%rip),%rdi        # 3583 <array.0+0x343>
    1f7c:	e8 ef f0 ff ff       	call   1070 <puts@plt>
    1f81:	bf 00 00 00 00       	mov    $0x0,%edi
    1f86:	e8 89 fe ff ff       	call   1e14 <send_msg>
    1f8b:	48 8d 3d 3e 13 00 00 	lea    0x133e(%rip),%rdi        # 32d0 <array.0+0x90>
    1f92:	e8 d9 f0 ff ff       	call   1070 <puts@plt>
    1f97:	bf 08 00 00 00       	mov    $0x8,%edi
    1f9c:	e8 ef f1 ff ff       	call   1190 <exit@plt>

0000000000001fa1 <read_six_numbers>:
    1fa1:	48 83 ec 08          	sub    $0x8,%rsp
    1fa5:	48 89 f2             	mov    %rsi,%rdx
    1fa8:	48 8d 4e 04          	lea    0x4(%rsi),%rcx
    1fac:	48 8d 46 14          	lea    0x14(%rsi),%rax
    1fb0:	50                   	push   %rax
    1fb1:	48 8d 46 10          	lea    0x10(%rsi),%rax
    1fb5:	50                   	push   %rax
    1fb6:	4c 8d 4e 0c          	lea    0xc(%rsi),%r9
    1fba:	4c 8d 46 08          	lea    0x8(%rsi),%r8
    1fbe:	48 8d 35 d6 15 00 00 	lea    0x15d6(%rip),%rsi        # 359b <array.0+0x35b>
    1fc5:	b8 00 00 00 00       	mov    $0x0,%eax
    1fca:	e8 81 f1 ff ff       	call   1150 <__isoc99_sscanf@plt>
    1fcf:	48 83 c4 10          	add    $0x10,%rsp
    1fd3:	83 f8 05             	cmp    $0x5,%eax
    1fd6:	7e 05                	jle    1fdd <read_six_numbers+0x3c>
    1fd8:	48 83 c4 08          	add    $0x8,%rsp
    1fdc:	c3                   	ret
    1fdd:	e8 ff fe ff ff       	call   1ee1 <explode_bomb>

0000000000001fe2 <read_line>:
    1fe2:	55                   	push   %rbp
    1fe3:	53                   	push   %rbx
    1fe4:	48 83 ec 08          	sub    $0x8,%rsp
    1fe8:	b8 00 00 00 00       	mov    $0x0,%eax
    1fed:	e8 d0 fd ff ff       	call   1dc2 <skip>
    1ff2:	48 85 c0             	test   %rax,%rax
    1ff5:	74 63                	je     205a <read_line+0x78>
    1ff7:	8b 1d 1b 37 00 00    	mov    0x371b(%rip),%ebx        # 5718 <num_input_strings>
    1ffd:	48 63 d3             	movslq %ebx,%rdx
    2000:	48 89 d0             	mov    %rdx,%rax
    2003:	48 c1 e0 04          	shl    $0x4,%rax
    2007:	48 29 d0             	sub    %rdx,%rax
    200a:	48 8d 15 0f 37 00 00 	lea    0x370f(%rip),%rdx        # 5720 <input_strings>
    2011:	48 8d 2c c2          	lea    (%rdx,%rax,8),%rbp
    2015:	48 89 ef             	mov    %rbp,%rdi
    2018:	e8 73 f0 ff ff       	call   1090 <strlen@plt>
    201d:	83 f8 76             	cmp    $0x76,%eax
    2020:	0f 8f ac 00 00 00    	jg     20d2 <read_line+0xf0>
    2026:	83 e8 01             	sub    $0x1,%eax
    2029:	48 98                	cltq
    202b:	48 63 cb             	movslq %ebx,%rcx
    202e:	48 89 ca             	mov    %rcx,%rdx
    2031:	48 c1 e2 04          	shl    $0x4,%rdx
    2035:	48 29 ca             	sub    %rcx,%rdx
    2038:	48 8d 0d e1 36 00 00 	lea    0x36e1(%rip),%rcx        # 5720 <input_strings>
    203f:	48 8d 14 d1          	lea    (%rcx,%rdx,8),%rdx
    2043:	c6 04 02 00          	movb   $0x0,(%rdx,%rax,1)
    2047:	83 c3 01             	add    $0x1,%ebx
    204a:	89 1d c8 36 00 00    	mov    %ebx,0x36c8(%rip)        # 5718 <num_input_strings>
    2050:	48 89 e8             	mov    %rbp,%rax
    2053:	48 83 c4 08          	add    $0x8,%rsp
    2057:	5b                   	pop    %rbx
    2058:	5d                   	pop    %rbp
    2059:	c3                   	ret
    205a:	48 8b 05 0f 36 00 00 	mov    0x360f(%rip),%rax        # 5670 <stdin@GLIBC_2.2.5>
    2061:	48 39 05 28 36 00 00 	cmp    %rax,0x3628(%rip)        # 5690 <infile>
    2068:	74 1b                	je     2085 <read_line+0xa3>
    206a:	48 8d 3d 5a 15 00 00 	lea    0x155a(%rip),%rdi        # 35cb <array.0+0x38b>
    2071:	e8 ba ef ff ff       	call   1030 <getenv@plt>
    2076:	48 85 c0             	test   %rax,%rax
    2079:	74 20                	je     209b <read_line+0xb9>
    207b:	bf 00 00 00 00       	mov    $0x0,%edi
    2080:	e8 0b f1 ff ff       	call   1190 <exit@plt>
    2085:	48 8d 3d 21 15 00 00 	lea    0x1521(%rip),%rdi        # 35ad <array.0+0x36d>
    208c:	e8 df ef ff ff       	call   1070 <puts@plt>
    2091:	bf 08 00 00 00       	mov    $0x8,%edi
    2096:	e8 f5 f0 ff ff       	call   1190 <exit@plt>
    209b:	48 8b 05 ce 35 00 00 	mov    0x35ce(%rip),%rax        # 5670 <stdin@GLIBC_2.2.5>
    20a2:	48 89 05 e7 35 00 00 	mov    %rax,0x35e7(%rip)        # 5690 <infile>
    20a9:	b8 00 00 00 00       	mov    $0x0,%eax
    20ae:	e8 0f fd ff ff       	call   1dc2 <skip>
    20b3:	48 85 c0             	test   %rax,%rax
    20b6:	0f 85 3b ff ff ff    	jne    1ff7 <read_line+0x15>
    20bc:	48 8d 3d ea 14 00 00 	lea    0x14ea(%rip),%rdi        # 35ad <array.0+0x36d>
    20c3:	e8 a8 ef ff ff       	call   1070 <puts@plt>
    20c8:	bf 00 00 00 00       	mov    $0x0,%edi
    20cd:	e8 be f0 ff ff       	call   1190 <exit@plt>
    20d2:	48 8d 3d fd 14 00 00 	lea    0x14fd(%rip),%rdi        # 35d6 <array.0+0x396>
    20d9:	e8 92 ef ff ff       	call   1070 <puts@plt>
    20de:	8b 05 34 36 00 00    	mov    0x3634(%rip),%eax        # 5718 <num_input_strings>
    20e4:	8d 50 01             	lea    0x1(%rax),%edx
    20e7:	89 15 2b 36 00 00    	mov    %edx,0x362b(%rip)        # 5718 <num_input_strings>
    20ed:	48 98                	cltq
    20ef:	48 6b c0 78          	imul   $0x78,%rax,%rax
    20f3:	48 8d 15 26 36 00 00 	lea    0x3626(%rip),%rdx        # 5720 <input_strings>
    20fa:	48 be 2a 2a 2a 74 72 	movabs $0x636e7572742a2a2a,%rsi
    2101:	75 6e 63 
    2104:	48 bf 61 74 65 64 2a 	movabs $0x2a2a2a64657461,%rdi
    210b:	2a 2a 00 
    210e:	48 89 34 02          	mov    %rsi,(%rdx,%rax,1)
    2112:	48 89 7c 02 08       	mov    %rdi,0x8(%rdx,%rax,1)
    2117:	e8 c5 fd ff ff       	call   1ee1 <explode_bomb>

000000000000211c <phase_defused>:
    211c:	48 83 ec 08          	sub    $0x8,%rsp
    2120:	bf 01 00 00 00       	mov    $0x1,%edi
    2125:	e8 ea fc ff ff       	call   1e14 <send_msg>
    212a:	83 3d e7 35 00 00 06 	cmpl   $0x6,0x35e7(%rip)        # 5718 <num_input_strings>
    2131:	74 05                	je     2138 <phase_defused+0x1c>
    2133:	48 83 c4 08          	add    $0x8,%rsp
    2137:	c3                   	ret
    2138:	0f b6 0d 39 38 00 00 	movzbl 0x3839(%rip),%ecx        # 5978 <input_strings+0x258>
    213f:	84 c9                	test   %cl,%cl
    2141:	74 34                	je     2177 <phase_defused+0x5b>
    2143:	b8 01 00 00 00       	mov    $0x1,%eax
    2148:	ba 00 00 00 00       	mov    $0x0,%edx
    214d:	48 8d 3d 24 38 00 00 	lea    0x3824(%rip),%rdi        # 5978 <input_strings+0x258>
    2154:	80 f9 20             	cmp    $0x20,%cl
    2157:	0f 94 c1             	sete   %cl
    215a:	0f b6 c9             	movzbl %cl,%ecx
    215d:	01 ca                	add    %ecx,%edx
    215f:	89 c6                	mov    %eax,%esi
    2161:	0f b6 0c 07          	movzbl (%rdi,%rax,1),%ecx
    2165:	48 83 c0 01          	add    $0x1,%rax
    2169:	83 fa 05             	cmp    $0x5,%edx
    216c:	7f 04                	jg     2172 <phase_defused+0x56>
    216e:	84 c9                	test   %cl,%cl
    2170:	75 e2                	jne    2154 <phase_defused+0x38>
    2172:	83 fa 06             	cmp    $0x6,%edx
    2175:	74 1a                	je     2191 <phase_defused+0x75>
    2177:	48 8d 3d da 11 00 00 	lea    0x11da(%rip),%rdi        # 3358 <array.0+0x118>
    217e:	e8 ed ee ff ff       	call   1070 <puts@plt>
    2183:	48 8d 3d fe 11 00 00 	lea    0x11fe(%rip),%rdi        # 3388 <array.0+0x148>
    218a:	e8 e1 ee ff ff       	call   1070 <puts@plt>
    218f:	eb a2                	jmp    2133 <phase_defused+0x17>
    2191:	48 63 f6             	movslq %esi,%rsi
    2194:	48 8d 05 dd 37 00 00 	lea    0x37dd(%rip),%rax        # 5978 <input_strings+0x258>
    219b:	48 8d 3c 06          	lea    (%rsi,%rax,1),%rdi
    219f:	48 8d 35 4b 14 00 00 	lea    0x144b(%rip),%rsi        # 35f1 <array.0+0x3b1>
    21a6:	e8 d1 fa ff ff       	call   1c7c <strings_not_equal>
    21ab:	85 c0                	test   %eax,%eax
    21ad:	75 c8                	jne    2177 <phase_defused+0x5b>
    21af:	48 8d 3d 42 11 00 00 	lea    0x1142(%rip),%rdi        # 32f8 <array.0+0xb8>
    21b6:	e8 b5 ee ff ff       	call   1070 <puts@plt>
    21bb:	48 8d 3d 5e 11 00 00 	lea    0x115e(%rip),%rdi        # 3320 <array.0+0xe0>
    21c2:	e8 a9 ee ff ff       	call   1070 <puts@plt>
    21c7:	b8 00 00 00 00       	mov    $0x0,%eax
    21cc:	e8 b7 f9 ff ff       	call   1b88 <secret_phase>
    21d1:	eb a4                	jmp    2177 <phase_defused+0x5b>

00000000000021d3 <sigalrm_handler>:
    21d3:	48 83 ec 08          	sub    $0x8,%rsp
    21d7:	ba 00 00 00 00       	mov    $0x0,%edx
    21dc:	48 8d 35 25 14 00 00 	lea    0x1425(%rip),%rsi        # 3608 <array.0+0x3c8>
    21e3:	48 8b 3d 96 34 00 00 	mov    0x3496(%rip),%rdi        # 5680 <stderr@GLIBC_2.2.5>
    21ea:	b8 00 00 00 00       	mov    $0x0,%eax
    21ef:	e8 3c ef ff ff       	call   1130 <fprintf@plt>
    21f4:	bf 01 00 00 00       	mov    $0x1,%edi
    21f9:	e8 92 ef ff ff       	call   1190 <exit@plt>

00000000000021fe <rio_writen>:
    21fe:	41 56                	push   %r14
    2200:	41 55                	push   %r13
    2202:	41 54                	push   %r12
    2204:	55                   	push   %rbp
    2205:	53                   	push   %rbx
    2206:	49 89 d5             	mov    %rdx,%r13
    2209:	48 85 d2             	test   %rdx,%rdx
    220c:	74 3b                	je     2249 <rio_writen+0x4b>
    220e:	41 89 fc             	mov    %edi,%r12d
    2211:	48 89 f5             	mov    %rsi,%rbp
    2214:	48 89 d3             	mov    %rdx,%rbx
    2217:	41 be 00 00 00 00    	mov    $0x0,%r14d
    221d:	eb 08                	jmp    2227 <rio_writen+0x29>
    221f:	48 01 c5             	add    %rax,%rbp
    2222:	48 29 c3             	sub    %rax,%rbx
    2225:	74 22                	je     2249 <rio_writen+0x4b>
    2227:	48 89 da             	mov    %rbx,%rdx
    222a:	48 89 ee             	mov    %rbp,%rsi
    222d:	44 89 e7             	mov    %r12d,%edi
    2230:	e8 4b ee ff ff       	call   1080 <write@plt>
    2235:	48 85 c0             	test   %rax,%rax
    2238:	7f e5                	jg     221f <rio_writen+0x21>
    223a:	e8 11 ee ff ff       	call   1050 <__errno_location@plt>
    223f:	83 38 04             	cmpl   $0x4,(%rax)
    2242:	75 11                	jne    2255 <rio_writen+0x57>
    2244:	4c 89 f0             	mov    %r14,%rax
    2247:	eb d6                	jmp    221f <rio_writen+0x21>
    2249:	4c 89 e8             	mov    %r13,%rax
    224c:	5b                   	pop    %rbx
    224d:	5d                   	pop    %rbp
    224e:	41 5c                	pop    %r12
    2250:	41 5d                	pop    %r13
    2252:	41 5e                	pop    %r14
    2254:	c3                   	ret
    2255:	48 c7 c0 ff ff ff ff 	mov    $0xffffffffffffffff,%rax
    225c:	eb ee                	jmp    224c <rio_writen+0x4e>

000000000000225e <rio_readlineb>:
    225e:	41 56                	push   %r14
    2260:	41 55                	push   %r13
    2262:	41 54                	push   %r12
    2264:	55                   	push   %rbp
    2265:	53                   	push   %rbx
    2266:	49 89 f4             	mov    %rsi,%r12
    2269:	48 83 fa 01          	cmp    $0x1,%rdx
    226d:	0f 86 92 00 00 00    	jbe    2305 <rio_readlineb+0xa7>
    2273:	48 89 fb             	mov    %rdi,%rbx
    2276:	4c 8d 74 16 ff       	lea    -0x1(%rsi,%rdx,1),%r14
    227b:	41 bd 01 00 00 00    	mov    $0x1,%r13d
    2281:	48 8d 6f 10          	lea    0x10(%rdi),%rbp
    2285:	eb 56                	jmp    22dd <rio_readlineb+0x7f>
    2287:	e8 c4 ed ff ff       	call   1050 <__errno_location@plt>
    228c:	83 38 04             	cmpl   $0x4,(%rax)
    228f:	75 55                	jne    22e6 <rio_readlineb+0x88>
    2291:	ba 00 20 00 00       	mov    $0x2000,%edx
    2296:	48 89 ee             	mov    %rbp,%rsi
    2299:	8b 3b                	mov    (%rbx),%edi
    229b:	e8 40 ee ff ff       	call   10e0 <read@plt>
    22a0:	89 c2                	mov    %eax,%edx
    22a2:	89 43 04             	mov    %eax,0x4(%rbx)
    22a5:	85 c0                	test   %eax,%eax
    22a7:	78 de                	js     2287 <rio_readlineb+0x29>
    22a9:	85 c0                	test   %eax,%eax
    22ab:	74 42                	je     22ef <rio_readlineb+0x91>
    22ad:	48 89 6b 08          	mov    %rbp,0x8(%rbx)
    22b1:	48 8b 43 08          	mov    0x8(%rbx),%rax
    22b5:	0f b6 08             	movzbl (%rax),%ecx
    22b8:	48 83 c0 01          	add    $0x1,%rax
    22bc:	48 89 43 08          	mov    %rax,0x8(%rbx)
    22c0:	83 ea 01             	sub    $0x1,%edx
    22c3:	89 53 04             	mov    %edx,0x4(%rbx)
    22c6:	49 83 c4 01          	add    $0x1,%r12
    22ca:	41 88 4c 24 ff       	mov    %cl,-0x1(%r12)
    22cf:	80 f9 0a             	cmp    $0xa,%cl
    22d2:	74 3c                	je     2310 <rio_readlineb+0xb2>
    22d4:	41 83 c5 01          	add    $0x1,%r13d
    22d8:	4d 39 f4             	cmp    %r14,%r12
    22db:	74 30                	je     230d <rio_readlineb+0xaf>
    22dd:	8b 53 04             	mov    0x4(%rbx),%edx
    22e0:	85 d2                	test   %edx,%edx
    22e2:	7e ad                	jle    2291 <rio_readlineb+0x33>
    22e4:	eb cb                	jmp    22b1 <rio_readlineb+0x53>
    22e6:	48 c7 c0 ff ff ff ff 	mov    $0xffffffffffffffff,%rax
    22ed:	eb 05                	jmp    22f4 <rio_readlineb+0x96>
    22ef:	b8 00 00 00 00       	mov    $0x0,%eax
    22f4:	85 c0                	test   %eax,%eax
    22f6:	75 29                	jne    2321 <rio_readlineb+0xc3>
    22f8:	b8 00 00 00 00       	mov    $0x0,%eax
    22fd:	41 83 fd 01          	cmp    $0x1,%r13d
    2301:	75 0d                	jne    2310 <rio_readlineb+0xb2>
    2303:	eb 13                	jmp    2318 <rio_readlineb+0xba>
    2305:	41 bd 01 00 00 00    	mov    $0x1,%r13d
    230b:	eb 03                	jmp    2310 <rio_readlineb+0xb2>
    230d:	4d 89 f4             	mov    %r14,%r12
    2310:	41 c6 04 24 00       	movb   $0x0,(%r12)
    2315:	49 63 c5             	movslq %r13d,%rax
    2318:	5b                   	pop    %rbx
    2319:	5d                   	pop    %rbp
    231a:	41 5c                	pop    %r12
    231c:	41 5d                	pop    %r13
    231e:	41 5e                	pop    %r14
    2320:	c3                   	ret
    2321:	48 c7 c0 ff ff ff ff 	mov    $0xffffffffffffffff,%rax
    2328:	eb ee                	jmp    2318 <rio_readlineb+0xba>

000000000000232a <submitr>:
    232a:	41 57                	push   %r15
    232c:	41 56                	push   %r14
    232e:	41 55                	push   %r13
    2330:	41 54                	push   %r12
    2332:	55                   	push   %rbp
    2333:	53                   	push   %rbx
    2334:	48 81 ec 78 a0 00 00 	sub    $0xa078,%rsp
    233b:	48 89 7c 24 08       	mov    %rdi,0x8(%rsp)
    2340:	89 f5                	mov    %esi,%ebp
    2342:	49 89 d4             	mov    %rdx,%r12
    2345:	48 89 4c 24 10       	mov    %rcx,0x10(%rsp)
    234a:	4c 89 44 24 20       	mov    %r8,0x20(%rsp)
    234f:	4c 89 4c 24 18       	mov    %r9,0x18(%rsp)
    2354:	48 8b 9c 24 b0 a0 00 	mov    0xa0b0(%rsp),%rbx
    235b:	00 
    235c:	4c 8b bc 24 b8 a0 00 	mov    0xa0b8(%rsp),%r15
    2363:	00 
    2364:	64 48 8b 04 25 28 00 	mov    %fs:0x28,%rax
    236b:	00 00 
    236d:	48 89 84 24 68 a0 00 	mov    %rax,0xa068(%rsp)
    2374:	00 
    2375:	31 c0                	xor    %eax,%eax
    2377:	c7 44 24 3c 00 00 00 	movl   $0x0,0x3c(%rsp)
    237e:	00 
    237f:	ba 00 00 00 00       	mov    $0x0,%edx
    2384:	be 01 00 00 00       	mov    $0x1,%esi
    2389:	bf 02 00 00 00       	mov    $0x2,%edi
    238e:	e8 3d ee ff ff       	call   11d0 <socket@plt>
    2393:	85 c0                	test   %eax,%eax
    2395:	0f 88 0d 01 00 00    	js     24a8 <submitr+0x17e>
    239b:	41 89 c6             	mov    %eax,%r14d
    239e:	48 8b 7c 24 08       	mov    0x8(%rsp),%rdi
    23a3:	e8 78 ed ff ff       	call   1120 <gethostbyname@plt>
    23a8:	48 85 c0             	test   %rax,%rax
    23ab:	0f 84 47 01 00 00    	je     24f8 <submitr+0x1ce>
    23b1:	4c 8d 6c 24 40       	lea    0x40(%rsp),%r13
    23b6:	48 c7 44 24 40 00 00 	movq   $0x0,0x40(%rsp)
    23bd:	00 00 
    23bf:	48 c7 44 24 48 00 00 	movq   $0x0,0x48(%rsp)
    23c6:	00 00 
    23c8:	66 c7 44 24 40 02 00 	movw   $0x2,0x40(%rsp)
    23cf:	48 63 50 14          	movslq 0x14(%rax),%rdx
    23d3:	48 8b 40 18          	mov    0x18(%rax),%rax
    23d7:	48 8d 7c 24 44       	lea    0x44(%rsp),%rdi
    23dc:	48 8b 30             	mov    (%rax),%rsi
    23df:	e8 7c ed ff ff       	call   1160 <memmove@plt>
    23e4:	66 c1 c5 08          	rol    $0x8,%bp
    23e8:	66 89 6c 24 42       	mov    %bp,0x42(%rsp)
    23ed:	ba 10 00 00 00       	mov    $0x10,%edx
    23f2:	4c 89 ee             	mov    %r13,%rsi
    23f5:	44 89 f7             	mov    %r14d,%edi
    23f8:	e8 a3 ed ff ff       	call   11a0 <connect@plt>
    23fd:	85 c0                	test   %eax,%eax
    23ff:	0f 88 5e 01 00 00    	js     2563 <submitr+0x239>
    2405:	48 89 df             	mov    %rbx,%rdi
    2408:	e8 83 ec ff ff       	call   1090 <strlen@plt>
    240d:	48 89 c5             	mov    %rax,%rbp
    2410:	4c 89 e7             	mov    %r12,%rdi
    2413:	e8 78 ec ff ff       	call   1090 <strlen@plt>
    2418:	49 89 c5             	mov    %rax,%r13
    241b:	48 8b 7c 24 10       	mov    0x10(%rsp),%rdi
    2420:	e8 6b ec ff ff       	call   1090 <strlen@plt>
    2425:	49 89 c4             	mov    %rax,%r12
    2428:	48 8b 7c 24 18       	mov    0x18(%rsp),%rdi
    242d:	e8 5e ec ff ff       	call   1090 <strlen@plt>
    2432:	48 89 c2             	mov    %rax,%rdx
    2435:	4b 8d 84 25 80 00 00 	lea    0x80(%r13,%r12,1),%rax
    243c:	00 
    243d:	48 01 d0             	add    %rdx,%rax
    2440:	48 8d 54 6d 00       	lea    0x0(%rbp,%rbp,2),%rdx
    2445:	48 01 d0             	add    %rdx,%rax
    2448:	48 3d 00 20 00 00    	cmp    $0x2000,%rax
    244e:	0f 87 6c 01 00 00    	ja     25c0 <submitr+0x296>
    2454:	48 8d 94 24 60 40 00 	lea    0x4060(%rsp),%rdx
    245b:	00 
    245c:	b9 00 04 00 00       	mov    $0x400,%ecx
    2461:	b8 00 00 00 00       	mov    $0x0,%eax
    2466:	48 89 d7             	mov    %rdx,%rdi
    2469:	f3 48 ab             	rep stos %rax,%es:(%rdi)
    246c:	48 89 df             	mov    %rbx,%rdi
    246f:	e8 1c ec ff ff       	call   1090 <strlen@plt>
    2474:	85 c0                	test   %eax,%eax
    2476:	0f 84 13 05 00 00    	je     298f <submitr+0x665>
    247c:	8d 40 ff             	lea    -0x1(%rax),%eax
    247f:	4c 8d 64 03 01       	lea    0x1(%rbx,%rax,1),%r12
    2484:	48 8d ac 24 60 40 00 	lea    0x4060(%rsp),%rbp
    248b:	00 
    248c:	48 8d 84 24 60 80 00 	lea    0x8060(%rsp),%rax
    2493:	00 
    2494:	48 89 44 24 28       	mov    %rax,0x28(%rsp)
    2499:	49 bd d9 ff 00 00 00 	movabs $0x2000000000ffd9,%r13
    24a0:	00 20 00 
    24a3:	e9 a5 01 00 00       	jmp    264d <submitr+0x323>
    24a8:	48 b8 45 72 72 6f 72 	movabs $0x43203a726f727245,%rax
    24af:	3a 20 43 
    24b2:	48 ba 6c 69 65 6e 74 	movabs $0x6e7520746e65696c,%rdx
    24b9:	20 75 6e 
    24bc:	49 89 07             	mov    %rax,(%r15)
    24bf:	49 89 57 08          	mov    %rdx,0x8(%r15)
    24c3:	48 b8 61 62 6c 65 20 	movabs $0x206f7420656c6261,%rax
    24ca:	74 6f 20 
    24cd:	48 ba 63 72 65 61 74 	movabs $0x7320657461657263,%rdx
    24d4:	65 20 73 
    24d7:	49 89 47 10          	mov    %rax,0x10(%r15)
    24db:	49 89 57 18          	mov    %rdx,0x18(%r15)
    24df:	41 c7 47 20 6f 63 6b 	movl   $0x656b636f,0x20(%r15)
    24e6:	65 
    24e7:	66 41 c7 47 24 74 00 	movw   $0x74,0x24(%r15)
    24ee:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
    24f3:	e9 6e 03 00 00       	jmp    2866 <submitr+0x53c>
    24f8:	48 b8 45 72 72 6f 72 	movabs $0x44203a726f727245,%rax
    24ff:	3a 20 44 
    2502:	48 ba 4e 53 20 69 73 	movabs $0x6e7520736920534e,%rdx
    2509:	20 75 6e 
    250c:	49 89 07             	mov    %rax,(%r15)
    250f:	49 89 57 08          	mov    %rdx,0x8(%r15)
    2513:	48 b8 61 62 6c 65 20 	movabs $0x206f7420656c6261,%rax
    251a:	74 6f 20 
    251d:	48 ba 72 65 73 6f 6c 	movabs $0x2065766c6f736572,%rdx
    2524:	76 65 20 
    2527:	49 89 47 10          	mov    %rax,0x10(%r15)
    252b:	49 89 57 18          	mov    %rdx,0x18(%r15)
    252f:	48 b8 73 65 72 76 65 	movabs $0x6120726576726573,%rax
    2536:	72 20 61 
    2539:	49 89 47 20          	mov    %rax,0x20(%r15)
    253d:	41 c7 47 28 64 64 72 	movl   $0x65726464,0x28(%r15)
    2544:	65 
    2545:	66 41 c7 47 2c 73 73 	movw   $0x7373,0x2c(%r15)
    254c:	41 c6 47 2e 00       	movb   $0x0,0x2e(%r15)
    2551:	44 89 f7             	mov    %r14d,%edi
    2554:	e8 77 eb ff ff       	call   10d0 <close@plt>
    2559:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
    255e:	e9 03 03 00 00       	jmp    2866 <submitr+0x53c>
    2563:	48 b8 45 72 72 6f 72 	movabs $0x55203a726f727245,%rax
    256a:	3a 20 55 
    256d:	48 ba 6e 61 62 6c 65 	movabs $0x6f7420656c62616e,%rdx
    2574:	20 74 6f 
    2577:	49 89 07             	mov    %rax,(%r15)
    257a:	49 89 57 08          	mov    %rdx,0x8(%r15)
    257e:	48 b8 20 63 6f 6e 6e 	movabs $0x7463656e6e6f6320,%rax
    2585:	65 63 74 
    2588:	48 ba 20 74 6f 20 74 	movabs $0x20656874206f7420,%rdx
    258f:	68 65 20 
    2592:	49 89 47 10          	mov    %rax,0x10(%r15)
    2596:	49 89 57 18          	mov    %rdx,0x18(%r15)
    259a:	41 c7 47 20 73 65 72 	movl   $0x76726573,0x20(%r15)
    25a1:	76 
    25a2:	66 41 c7 47 24 65 72 	movw   $0x7265,0x24(%r15)
    25a9:	41 c6 47 26 00       	movb   $0x0,0x26(%r15)
    25ae:	44 89 f7             	mov    %r14d,%edi
    25b1:	e8 1a eb ff ff       	call   10d0 <close@plt>
    25b6:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
    25bb:	e9 a6 02 00 00       	jmp    2866 <submitr+0x53c>
    25c0:	48 b8 45 72 72 6f 72 	movabs $0x52203a726f727245,%rax
    25c7:	3a 20 52 
    25ca:	48 ba 65 73 75 6c 74 	movabs $0x747320746c757365,%rdx
    25d1:	20 73 74 
    25d4:	49 89 07             	mov    %rax,(%r15)
    25d7:	49 89 57 08          	mov    %rdx,0x8(%r15)
    25db:	48 b8 72 69 6e 67 20 	movabs $0x6f6f7420676e6972,%rax
    25e2:	74 6f 6f 
    25e5:	48 ba 20 6c 61 72 67 	movabs $0x202e656772616c20,%rdx
    25ec:	65 2e 20 
    25ef:	49 89 47 10          	mov    %rax,0x10(%r15)
    25f3:	49 89 57 18          	mov    %rdx,0x18(%r15)
    25f7:	48 b8 49 6e 63 72 65 	movabs $0x6573616572636e49,%rax
    25fe:	61 73 65 
    2601:	48 ba 20 53 55 42 4d 	movabs $0x5254494d42555320,%rdx
    2608:	49 54 52 
    260b:	49 89 47 20          	mov    %rax,0x20(%r15)
    260f:	49 89 57 28          	mov    %rdx,0x28(%r15)
    2613:	48 b8 5f 4d 41 58 42 	movabs $0x46554258414d5f,%rax
    261a:	55 46 00 
    261d:	49 89 47 30          	mov    %rax,0x30(%r15)
    2621:	44 89 f7             	mov    %r14d,%edi
    2624:	e8 a7 ea ff ff       	call   10d0 <close@plt>
    2629:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
    262e:	e9 33 02 00 00       	jmp    2866 <submitr+0x53c>
    2633:	49 0f a3 c5          	bt     %rax,%r13
    2637:	73 1e                	jae    2657 <submitr+0x32d>
    2639:	88 55 00             	mov    %dl,0x0(%rbp)
    263c:	48 8d 6d 01          	lea    0x1(%rbp),%rbp
    2640:	48 83 c3 01          	add    $0x1,%rbx
    2644:	4c 39 e3             	cmp    %r12,%rbx
    2647:	0f 84 42 03 00 00    	je     298f <submitr+0x665>
    264d:	0f b6 13             	movzbl (%rbx),%edx
    2650:	8d 42 d6             	lea    -0x2a(%rdx),%eax
    2653:	3c 35                	cmp    $0x35,%al
    2655:	76 dc                	jbe    2633 <submitr+0x309>
    2657:	89 d0                	mov    %edx,%eax
    2659:	83 e0 df             	and    $0xffffffdf,%eax
    265c:	83 e8 41             	sub    $0x41,%eax
    265f:	3c 19                	cmp    $0x19,%al
    2661:	76 d6                	jbe    2639 <submitr+0x30f>
    2663:	80 fa 20             	cmp    $0x20,%dl
    2666:	74 50                	je     26b8 <submitr+0x38e>
    2668:	8d 42 e0             	lea    -0x20(%rdx),%eax
    266b:	3c 5f                	cmp    $0x5f,%al
    266d:	76 09                	jbe    2678 <submitr+0x34e>
    266f:	80 fa 09             	cmp    $0x9,%dl
    2672:	0f 85 8a 02 00 00    	jne    2902 <submitr+0x5d8>
    2678:	0f b6 d2             	movzbl %dl,%edx
    267b:	48 8d 35 5d 10 00 00 	lea    0x105d(%rip),%rsi        # 36df <array.0+0x49f>
    2682:	48 8b 7c 24 28       	mov    0x28(%rsp),%rdi
    2687:	b8 00 00 00 00       	mov    $0x0,%eax
    268c:	e8 ef ea ff ff       	call   1180 <sprintf@plt>
    2691:	0f b6 84 24 60 80 00 	movzbl 0x8060(%rsp),%eax
    2698:	00 
    2699:	88 45 00             	mov    %al,0x0(%rbp)
    269c:	0f b6 84 24 61 80 00 	movzbl 0x8061(%rsp),%eax
    26a3:	00 
    26a4:	88 45 01             	mov    %al,0x1(%rbp)
    26a7:	0f b6 84 24 62 80 00 	movzbl 0x8062(%rsp),%eax
    26ae:	00 
    26af:	88 45 02             	mov    %al,0x2(%rbp)
    26b2:	48 8d 6d 03          	lea    0x3(%rbp),%rbp
    26b6:	eb 88                	jmp    2640 <submitr+0x316>
    26b8:	c6 45 00 2b          	movb   $0x2b,0x0(%rbp)
    26bc:	48 8d 6d 01          	lea    0x1(%rbp),%rbp
    26c0:	e9 7b ff ff ff       	jmp    2640 <submitr+0x316>
    26c5:	48 b8 45 72 72 6f 72 	movabs $0x43203a726f727245,%rax
    26cc:	3a 20 43 
    26cf:	48 ba 6c 69 65 6e 74 	movabs $0x6e7520746e65696c,%rdx
    26d6:	20 75 6e 
    26d9:	49 89 07             	mov    %rax,(%r15)
    26dc:	49 89 57 08          	mov    %rdx,0x8(%r15)
    26e0:	48 b8 61 62 6c 65 20 	movabs $0x206f7420656c6261,%rax
    26e7:	74 6f 20 
    26ea:	48 ba 77 72 69 74 65 	movabs $0x6f74206574697277,%rdx
    26f1:	20 74 6f 
    26f4:	49 89 47 10          	mov    %rax,0x10(%r15)
    26f8:	49 89 57 18          	mov    %rdx,0x18(%r15)
    26fc:	48 b8 20 74 68 65 20 	movabs $0x7265732065687420,%rax
    2703:	73 65 72 
    2706:	49 89 47 20          	mov    %rax,0x20(%r15)
    270a:	41 c7 47 28 76 65 72 	movl   $0x726576,0x28(%r15)
    2711:	00 
    2712:	44 89 f7             	mov    %r14d,%edi
    2715:	e8 b6 e9 ff ff       	call   10d0 <close@plt>
    271a:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
    271f:	e9 42 01 00 00       	jmp    2866 <submitr+0x53c>
    2724:	48 b8 45 72 72 6f 72 	movabs $0x43203a726f727245,%rax
    272b:	3a 20 43 
    272e:	48 ba 6c 69 65 6e 74 	movabs $0x6e7520746e65696c,%rdx
    2735:	20 75 6e 
    2738:	49 89 07             	mov    %rax,(%r15)
    273b:	49 89 57 08          	mov    %rdx,0x8(%r15)
    273f:	48 b8 61 62 6c 65 20 	movabs $0x206f7420656c6261,%rax
    2746:	74 6f 20 
    2749:	48 ba 77 72 69 74 65 	movabs $0x6f74206574697277,%rdx
    2750:	20 74 6f 
    2753:	49 89 47 10          	mov    %rax,0x10(%r15)
    2757:	49 89 57 18          	mov    %rdx,0x18(%r15)
    275b:	48 b8 20 74 68 65 20 	movabs $0x7265732065687420,%rax
    2762:	73 65 72 
    2765:	49 89 47 20          	mov    %rax,0x20(%r15)
    2769:	41 c7 47 28 76 65 72 	movl   $0x726576,0x28(%r15)
    2770:	00 
    2771:	44 89 f7             	mov    %r14d,%edi
    2774:	e8 57 e9 ff ff       	call   10d0 <close@plt>
    2779:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
    277e:	e9 e3 00 00 00       	jmp    2866 <submitr+0x53c>
    2783:	48 b8 45 72 72 6f 72 	movabs $0x43203a726f727245,%rax
    278a:	3a 20 43 
    278d:	48 ba 6c 69 65 6e 74 	movabs $0x6e7520746e65696c,%rdx
    2794:	20 75 6e 
    2797:	49 89 07             	mov    %rax,(%r15)
    279a:	49 89 57 08          	mov    %rdx,0x8(%r15)
    279e:	48 b8 61 62 6c 65 20 	movabs $0x206f7420656c6261,%rax
    27a5:	74 6f 20 
    27a8:	48 ba 72 65 61 64 20 	movabs $0x7269662064616572,%rdx
    27af:	66 69 72 
    27b2:	49 89 47 10          	mov    %rax,0x10(%r15)
    27b6:	49 89 57 18          	mov    %rdx,0x18(%r15)
    27ba:	48 b8 73 74 20 68 65 	movabs $0x6564616568207473,%rax
    27c1:	61 64 65 
    27c4:	48 ba 72 20 66 72 6f 	movabs $0x73206d6f72662072,%rdx
    27cb:	6d 20 73 
    27ce:	49 89 47 20          	mov    %rax,0x20(%r15)
    27d2:	49 89 57 28          	mov    %rdx,0x28(%r15)
    27d6:	41 c7 47 30 65 72 76 	movl   $0x65767265,0x30(%r15)
    27dd:	65 
    27de:	66 41 c7 47 34 72 00 	movw   $0x72,0x34(%r15)
    27e5:	44 89 f7             	mov    %r14d,%edi
    27e8:	e8 e3 e8 ff ff       	call   10d0 <close@plt>
    27ed:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
    27f2:	eb 72                	jmp    2866 <submitr+0x53c>
    27f4:	48 8d 8c 24 60 80 00 	lea    0x8060(%rsp),%rcx
    27fb:	00 
    27fc:	48 8d 35 2d 0e 00 00 	lea    0xe2d(%rip),%rsi        # 3630 <array.0+0x3f0>
    2803:	4c 89 ff             	mov    %r15,%rdi
    2806:	b8 00 00 00 00       	mov    $0x0,%eax
    280b:	e8 70 e9 ff ff       	call   1180 <sprintf@plt>
    2810:	44 89 f7             	mov    %r14d,%edi
    2813:	e8 b8 e8 ff ff       	call   10d0 <close@plt>
    2818:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
    281d:	eb 47                	jmp    2866 <submitr+0x53c>
    281f:	48 8d b4 24 60 20 00 	lea    0x2060(%rsp),%rsi
    2826:	00 
    2827:	48 8d 7c 24 50       	lea    0x50(%rsp),%rdi
    282c:	ba 00 20 00 00       	mov    $0x2000,%edx
    2831:	e8 28 fa ff ff       	call   225e <rio_readlineb>
    2836:	48 85 c0             	test   %rax,%rax
    2839:	7e 54                	jle    288f <submitr+0x565>
    283b:	48 8d b4 24 60 20 00 	lea    0x2060(%rsp),%rsi
    2842:	00 
    2843:	4c 89 ff             	mov    %r15,%rdi
    2846:	e8 15 e8 ff ff       	call   1060 <strcpy@plt>
    284b:	44 89 f7             	mov    %r14d,%edi
    284e:	e8 7d e8 ff ff       	call   10d0 <close@plt>
    2853:	48 8d 35 aa 0e 00 00 	lea    0xeaa(%rip),%rsi        # 3704 <array.0+0x4c4>
    285a:	4c 89 ff             	mov    %r15,%rdi
    285d:	e8 9e e8 ff ff       	call   1100 <strcmp@plt>
    2862:	f7 d8                	neg    %eax
    2864:	19 c0                	sbb    %eax,%eax
    2866:	48 8b 94 24 68 a0 00 	mov    0xa068(%rsp),%rdx
    286d:	00 
    286e:	64 48 2b 14 25 28 00 	sub    %fs:0x28,%rdx
    2875:	00 00 
    2877:	0f 85 be 02 00 00    	jne    2b3b <submitr+0x811>
    287d:	48 81 c4 78 a0 00 00 	add    $0xa078,%rsp
    2884:	5b                   	pop    %rbx
    2885:	5d                   	pop    %rbp
    2886:	41 5c                	pop    %r12
    2888:	41 5d                	pop    %r13
    288a:	41 5e                	pop    %r14
    288c:	41 5f                	pop    %r15
    288e:	c3                   	ret
    288f:	48 b8 45 72 72 6f 72 	movabs $0x43203a726f727245,%rax
    2896:	3a 20 43 
    2899:	48 ba 6c 69 65 6e 74 	movabs $0x6e7520746e65696c,%rdx
    28a0:	20 75 6e 
    28a3:	49 89 07             	mov    %rax,(%r15)
    28a6:	49 89 57 08          	mov    %rdx,0x8(%r15)
    28aa:	48 b8 61 62 6c 65 20 	movabs $0x206f7420656c6261,%rax
    28b1:	74 6f 20 
    28b4:	48 ba 72 65 61 64 20 	movabs $0x6174732064616572,%rdx
    28bb:	73 74 61 
    28be:	49 89 47 10          	mov    %rax,0x10(%r15)
    28c2:	49 89 57 18          	mov    %rdx,0x18(%r15)
    28c6:	48 b8 74 75 73 20 6d 	movabs $0x7373656d20737574,%rax
    28cd:	65 73 73 
    28d0:	48 ba 61 67 65 20 66 	movabs $0x6d6f726620656761,%rdx
    28d7:	72 6f 6d 
    28da:	49 89 47 20          	mov    %rax,0x20(%r15)
    28de:	49 89 57 28          	mov    %rdx,0x28(%r15)
    28e2:	48 b8 20 73 65 72 76 	movabs $0x72657672657320,%rax
    28e9:	65 72 00 
    28ec:	49 89 47 30          	mov    %rax,0x30(%r15)
    28f0:	44 89 f7             	mov    %r14d,%edi
    28f3:	e8 d8 e7 ff ff       	call   10d0 <close@plt>
    28f8:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
    28fd:	e9 64 ff ff ff       	jmp    2866 <submitr+0x53c>
    2902:	48 b8 45 72 72 6f 72 	movabs $0x52203a726f727245,%rax
    2909:	3a 20 52 
    290c:	48 ba 65 73 75 6c 74 	movabs $0x747320746c757365,%rdx
    2913:	20 73 74 
    2916:	49 89 07             	mov    %rax,(%r15)
    2919:	49 89 57 08          	mov    %rdx,0x8(%r15)
    291d:	48 b8 72 69 6e 67 20 	movabs $0x6e6f6320676e6972,%rax
    2924:	63 6f 6e 
    2927:	48 ba 74 61 69 6e 73 	movabs $0x6e6120736e696174,%rdx
    292e:	20 61 6e 
    2931:	49 89 47 10          	mov    %rax,0x10(%r15)
    2935:	49 89 57 18          	mov    %rdx,0x18(%r15)
    2939:	48 b8 20 69 6c 6c 65 	movabs $0x6c6167656c6c6920,%rax
    2940:	67 61 6c 
    2943:	48 ba 20 6f 72 20 75 	movabs $0x72706e7520726f20,%rdx
    294a:	6e 70 72 
    294d:	49 89 47 20          	mov    %rax,0x20(%r15)
    2951:	49 89 57 28          	mov    %rdx,0x28(%r15)
    2955:	48 b8 69 6e 74 61 62 	movabs $0x20656c6261746e69,%rax
    295c:	6c 65 20 
    295f:	48 ba 63 68 61 72 61 	movabs $0x6574636172616863,%rdx
    2966:	63 74 65 
    2969:	49 89 47 30          	mov    %rax,0x30(%r15)
    296d:	49 89 57 38          	mov    %rdx,0x38(%r15)
    2971:	66 41 c7 47 40 72 2e 	movw   $0x2e72,0x40(%r15)
    2978:	41 c6 47 42 00       	movb   $0x0,0x42(%r15)
    297d:	44 89 f7             	mov    %r14d,%edi
    2980:	e8 4b e7 ff ff       	call   10d0 <close@plt>
    2985:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
    298a:	e9 d7 fe ff ff       	jmp    2866 <submitr+0x53c>
    298f:	48 8d 9c 24 60 20 00 	lea    0x2060(%rsp),%rbx
    2996:	00 
    2997:	4c 8d 8c 24 60 40 00 	lea    0x4060(%rsp),%r9
    299e:	00 
    299f:	4c 8b 44 24 18       	mov    0x18(%rsp),%r8
    29a4:	48 8b 4c 24 20       	mov    0x20(%rsp),%rcx
    29a9:	48 8b 54 24 10       	mov    0x10(%rsp),%rdx
    29ae:	48 8d 35 ab 0c 00 00 	lea    0xcab(%rip),%rsi        # 3660 <array.0+0x420>
    29b5:	48 89 df             	mov    %rbx,%rdi
    29b8:	b8 00 00 00 00       	mov    $0x0,%eax
    29bd:	e8 be e7 ff ff       	call   1180 <sprintf@plt>
    29c2:	48 89 df             	mov    %rbx,%rdi
    29c5:	e8 c6 e6 ff ff       	call   1090 <strlen@plt>
    29ca:	48 89 c2             	mov    %rax,%rdx
    29cd:	48 89 de             	mov    %rbx,%rsi
    29d0:	44 89 f7             	mov    %r14d,%edi
    29d3:	e8 26 f8 ff ff       	call   21fe <rio_writen>
    29d8:	48 85 c0             	test   %rax,%rax
    29db:	0f 88 e4 fc ff ff    	js     26c5 <submitr+0x39b>
    29e1:	48 8d 9c 24 60 20 00 	lea    0x2060(%rsp),%rbx
    29e8:	00 
    29e9:	48 8b 54 24 08       	mov    0x8(%rsp),%rdx
    29ee:	48 8d 35 f1 0c 00 00 	lea    0xcf1(%rip),%rsi        # 36e6 <array.0+0x4a6>
    29f5:	48 89 df             	mov    %rbx,%rdi
    29f8:	b8 00 00 00 00       	mov    $0x0,%eax
    29fd:	e8 7e e7 ff ff       	call   1180 <sprintf@plt>
    2a02:	48 89 df             	mov    %rbx,%rdi
    2a05:	e8 86 e6 ff ff       	call   1090 <strlen@plt>
    2a0a:	48 89 c2             	mov    %rax,%rdx
    2a0d:	48 89 de             	mov    %rbx,%rsi
    2a10:	44 89 f7             	mov    %r14d,%edi
    2a13:	e8 e6 f7 ff ff       	call   21fe <rio_writen>
    2a18:	48 85 c0             	test   %rax,%rax
    2a1b:	0f 88 03 fd ff ff    	js     2724 <submitr+0x3fa>
    2a21:	44 89 74 24 50       	mov    %r14d,0x50(%rsp)
    2a26:	c7 44 24 54 00 00 00 	movl   $0x0,0x54(%rsp)
    2a2d:	00 
    2a2e:	48 8d 7c 24 50       	lea    0x50(%rsp),%rdi
    2a33:	48 8d 44 24 60       	lea    0x60(%rsp),%rax
    2a38:	48 89 44 24 58       	mov    %rax,0x58(%rsp)
    2a3d:	48 8d b4 24 60 20 00 	lea    0x2060(%rsp),%rsi
    2a44:	00 
    2a45:	ba 00 20 00 00       	mov    $0x2000,%edx
    2a4a:	e8 0f f8 ff ff       	call   225e <rio_readlineb>
    2a4f:	48 85 c0             	test   %rax,%rax
    2a52:	0f 8e 2b fd ff ff    	jle    2783 <submitr+0x459>
    2a58:	48 8d 4c 24 3c       	lea    0x3c(%rsp),%rcx
    2a5d:	48 8d 94 24 60 60 00 	lea    0x6060(%rsp),%rdx
    2a64:	00 
    2a65:	48 8d bc 24 60 20 00 	lea    0x2060(%rsp),%rdi
    2a6c:	00 
    2a6d:	4c 8d 84 24 60 80 00 	lea    0x8060(%rsp),%r8
    2a74:	00 
    2a75:	48 8d 35 77 0c 00 00 	lea    0xc77(%rip),%rsi        # 36f3 <array.0+0x4b3>
    2a7c:	b8 00 00 00 00       	mov    $0x0,%eax
    2a81:	e8 ca e6 ff ff       	call   1150 <__isoc99_sscanf@plt>
    2a86:	8b 54 24 3c          	mov    0x3c(%rsp),%edx
    2a8a:	81 fa c8 00 00 00    	cmp    $0xc8,%edx
    2a90:	0f 85 5e fd ff ff    	jne    27f4 <submitr+0x4ca>
    2a96:	48 8d 1d 53 0c 00 00 	lea    0xc53(%rip),%rbx        # 36f0 <array.0+0x4b0>
    2a9d:	48 8d bc 24 60 20 00 	lea    0x2060(%rsp),%rdi
    2aa4:	00 
    2aa5:	48 89 de             	mov    %rbx,%rsi
    2aa8:	e8 53 e6 ff ff       	call   1100 <strcmp@plt>
    2aad:	85 c0                	test   %eax,%eax
    2aaf:	0f 84 6a fd ff ff    	je     281f <submitr+0x4f5>
    2ab5:	48 8d b4 24 60 20 00 	lea    0x2060(%rsp),%rsi
    2abc:	00 
    2abd:	48 8d 7c 24 50       	lea    0x50(%rsp),%rdi
    2ac2:	ba 00 20 00 00       	mov    $0x2000,%edx
    2ac7:	e8 92 f7 ff ff       	call   225e <rio_readlineb>
    2acc:	48 85 c0             	test   %rax,%rax
    2acf:	7f cc                	jg     2a9d <submitr+0x773>
    2ad1:	48 b8 45 72 72 6f 72 	movabs $0x43203a726f727245,%rax
    2ad8:	3a 20 43 
    2adb:	48 ba 6c 69 65 6e 74 	movabs $0x6e7520746e65696c,%rdx
    2ae2:	20 75 6e 
    2ae5:	49 89 07             	mov    %rax,(%r15)
    2ae8:	49 89 57 08          	mov    %rdx,0x8(%r15)
    2aec:	48 b8 61 62 6c 65 20 	movabs $0x206f7420656c6261,%rax
    2af3:	74 6f 20 
    2af6:	48 ba 72 65 61 64 20 	movabs $0x6165682064616572,%rdx
    2afd:	68 65 61 
    2b00:	49 89 47 10          	mov    %rax,0x10(%r15)
    2b04:	49 89 57 18          	mov    %rdx,0x18(%r15)
    2b08:	48 b8 64 65 72 73 20 	movabs $0x6f72662073726564,%rax
    2b0f:	66 72 6f 
    2b12:	48 ba 6d 20 73 65 72 	movabs $0x726576726573206d,%rdx
    2b19:	76 65 72 
    2b1c:	49 89 47 20          	mov    %rax,0x20(%r15)
    2b20:	49 89 57 28          	mov    %rdx,0x28(%r15)
    2b24:	41 c6 47 30 00       	movb   $0x0,0x30(%r15)
    2b29:	44 89 f7             	mov    %r14d,%edi
    2b2c:	e8 9f e5 ff ff       	call   10d0 <close@plt>
    2b31:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
    2b36:	e9 2b fd ff ff       	jmp    2866 <submitr+0x53c>
    2b3b:	e8 60 e5 ff ff       	call   10a0 <__stack_chk_fail@plt>

0000000000002b40 <init_timeout>:
    2b40:	85 ff                	test   %edi,%edi
    2b42:	75 01                	jne    2b45 <init_timeout+0x5>
    2b44:	c3                   	ret
    2b45:	53                   	push   %rbx
    2b46:	89 fb                	mov    %edi,%ebx
    2b48:	48 8d 35 84 f6 ff ff 	lea    -0x97c(%rip),%rsi        # 21d3 <sigalrm_handler>
    2b4f:	bf 0e 00 00 00       	mov    $0xe,%edi
    2b54:	e8 b7 e5 ff ff       	call   1110 <signal@plt>
    2b59:	85 db                	test   %ebx,%ebx
    2b5b:	b8 00 00 00 00       	mov    $0x0,%eax
    2b60:	0f 49 c3             	cmovns %ebx,%eax
    2b63:	89 c7                	mov    %eax,%edi
    2b65:	e8 56 e5 ff ff       	call   10c0 <alarm@plt>
    2b6a:	5b                   	pop    %rbx
    2b6b:	c3                   	ret

0000000000002b6c <init_driver>:
    2b6c:	41 54                	push   %r12
    2b6e:	55                   	push   %rbp
    2b6f:	53                   	push   %rbx
    2b70:	48 83 ec 20          	sub    $0x20,%rsp
    2b74:	48 89 fd             	mov    %rdi,%rbp
    2b77:	64 48 8b 04 25 28 00 	mov    %fs:0x28,%rax
    2b7e:	00 00 
    2b80:	48 89 44 24 18       	mov    %rax,0x18(%rsp)
    2b85:	31 c0                	xor    %eax,%eax
    2b87:	be 01 00 00 00       	mov    $0x1,%esi
    2b8c:	bf 0d 00 00 00       	mov    $0xd,%edi
    2b91:	e8 7a e5 ff ff       	call   1110 <signal@plt>
    2b96:	be 01 00 00 00       	mov    $0x1,%esi
    2b9b:	bf 1d 00 00 00       	mov    $0x1d,%edi
    2ba0:	e8 6b e5 ff ff       	call   1110 <signal@plt>
    2ba5:	be 01 00 00 00       	mov    $0x1,%esi
    2baa:	bf 1d 00 00 00       	mov    $0x1d,%edi
    2baf:	e8 5c e5 ff ff       	call   1110 <signal@plt>
    2bb4:	ba 00 00 00 00       	mov    $0x0,%edx
    2bb9:	be 01 00 00 00       	mov    $0x1,%esi
    2bbe:	bf 02 00 00 00       	mov    $0x2,%edi
    2bc3:	e8 08 e6 ff ff       	call   11d0 <socket@plt>
    2bc8:	85 c0                	test   %eax,%eax
    2bca:	0f 88 97 00 00 00    	js     2c67 <init_driver+0xfb>
    2bd0:	89 c3                	mov    %eax,%ebx
    2bd2:	48 8d 3d 2e 0b 00 00 	lea    0xb2e(%rip),%rdi        # 3707 <array.0+0x4c7>
    2bd9:	e8 42 e5 ff ff       	call   1120 <gethostbyname@plt>
    2bde:	48 85 c0             	test   %rax,%rax
    2be1:	0f 84 cc 00 00 00    	je     2cb3 <init_driver+0x147>
    2be7:	49 89 e4             	mov    %rsp,%r12
    2bea:	48 c7 04 24 00 00 00 	movq   $0x0,(%rsp)
    2bf1:	00 
    2bf2:	48 c7 44 24 08 00 00 	movq   $0x0,0x8(%rsp)
    2bf9:	00 00 
    2bfb:	66 c7 04 24 02 00    	movw   $0x2,(%rsp)
    2c01:	48 63 50 14          	movslq 0x14(%rax),%rdx
    2c05:	48 8b 40 18          	mov    0x18(%rax),%rax
    2c09:	48 8d 7c 24 04       	lea    0x4(%rsp),%rdi
    2c0e:	48 8b 30             	mov    (%rax),%rsi
    2c11:	e8 4a e5 ff ff       	call   1160 <memmove@plt>
    2c16:	66 c7 44 24 02 00 50 	movw   $0x5000,0x2(%rsp)
    2c1d:	ba 10 00 00 00       	mov    $0x10,%edx
    2c22:	4c 89 e6             	mov    %r12,%rsi
    2c25:	89 df                	mov    %ebx,%edi
    2c27:	e8 74 e5 ff ff       	call   11a0 <connect@plt>
    2c2c:	85 c0                	test   %eax,%eax
    2c2e:	0f 88 e7 00 00 00    	js     2d1b <init_driver+0x1af>
    2c34:	89 df                	mov    %ebx,%edi
    2c36:	e8 95 e4 ff ff       	call   10d0 <close@plt>
    2c3b:	66 c7 45 00 4f 4b    	movw   $0x4b4f,0x0(%rbp)
    2c41:	c6 45 02 00          	movb   $0x0,0x2(%rbp)
    2c45:	b8 00 00 00 00       	mov    $0x0,%eax
    2c4a:	48 8b 54 24 18       	mov    0x18(%rsp),%rdx
    2c4f:	64 48 2b 14 25 28 00 	sub    %fs:0x28,%rdx
    2c56:	00 00 
    2c58:	0f 85 ee 00 00 00    	jne    2d4c <init_driver+0x1e0>
    2c5e:	48 83 c4 20          	add    $0x20,%rsp
    2c62:	5b                   	pop    %rbx
    2c63:	5d                   	pop    %rbp
    2c64:	41 5c                	pop    %r12
    2c66:	c3                   	ret
    2c67:	48 b8 45 72 72 6f 72 	movabs $0x43203a726f727245,%rax
    2c6e:	3a 20 43 
    2c71:	48 ba 6c 69 65 6e 74 	movabs $0x6e7520746e65696c,%rdx
    2c78:	20 75 6e 
    2c7b:	48 89 45 00          	mov    %rax,0x0(%rbp)
    2c7f:	48 89 55 08          	mov    %rdx,0x8(%rbp)
    2c83:	48 b8 61 62 6c 65 20 	movabs $0x206f7420656c6261,%rax
    2c8a:	74 6f 20 
    2c8d:	48 ba 63 72 65 61 74 	movabs $0x7320657461657263,%rdx
    2c94:	65 20 73 
    2c97:	48 89 45 10          	mov    %rax,0x10(%rbp)
    2c9b:	48 89 55 18          	mov    %rdx,0x18(%rbp)
    2c9f:	c7 45 20 6f 63 6b 65 	movl   $0x656b636f,0x20(%rbp)
    2ca6:	66 c7 45 24 74 00    	movw   $0x74,0x24(%rbp)
    2cac:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
    2cb1:	eb 97                	jmp    2c4a <init_driver+0xde>
    2cb3:	48 b8 45 72 72 6f 72 	movabs $0x44203a726f727245,%rax
    2cba:	3a 20 44 
    2cbd:	48 ba 4e 53 20 69 73 	movabs $0x6e7520736920534e,%rdx
    2cc4:	20 75 6e 
    2cc7:	48 89 45 00          	mov    %rax,0x0(%rbp)
    2ccb:	48 89 55 08          	mov    %rdx,0x8(%rbp)
    2ccf:	48 b8 61 62 6c 65 20 	movabs $0x206f7420656c6261,%rax
    2cd6:	74 6f 20 
    2cd9:	48 ba 72 65 73 6f 6c 	movabs $0x2065766c6f736572,%rdx
    2ce0:	76 65 20 
    2ce3:	48 89 45 10          	mov    %rax,0x10(%rbp)
    2ce7:	48 89 55 18          	mov    %rdx,0x18(%rbp)
    2ceb:	48 b8 73 65 72 76 65 	movabs $0x6120726576726573,%rax
    2cf2:	72 20 61 
    2cf5:	48 89 45 20          	mov    %rax,0x20(%rbp)
    2cf9:	c7 45 28 64 64 72 65 	movl   $0x65726464,0x28(%rbp)
    2d00:	66 c7 45 2c 73 73    	movw   $0x7373,0x2c(%rbp)
    2d06:	c6 45 2e 00          	movb   $0x0,0x2e(%rbp)
    2d0a:	89 df                	mov    %ebx,%edi
    2d0c:	e8 bf e3 ff ff       	call   10d0 <close@plt>
    2d11:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
    2d16:	e9 2f ff ff ff       	jmp    2c4a <init_driver+0xde>
    2d1b:	b9 50 00 00 00       	mov    $0x50,%ecx
    2d20:	48 8d 15 e0 09 00 00 	lea    0x9e0(%rip),%rdx        # 3707 <array.0+0x4c7>
    2d27:	48 8d 35 82 09 00 00 	lea    0x982(%rip),%rsi        # 36b0 <array.0+0x470>
    2d2e:	48 89 ef             	mov    %rbp,%rdi
    2d31:	b8 00 00 00 00       	mov    $0x0,%eax
    2d36:	e8 45 e4 ff ff       	call   1180 <sprintf@plt>
    2d3b:	89 df                	mov    %ebx,%edi
    2d3d:	e8 8e e3 ff ff       	call   10d0 <close@plt>
    2d42:	b8 ff ff ff ff       	mov    $0xffffffff,%eax
    2d47:	e9 fe fe ff ff       	jmp    2c4a <init_driver+0xde>
    2d4c:	e8 4f e3 ff ff       	call   10a0 <__stack_chk_fail@plt>

0000000000002d51 <driver_post>:
    2d51:	53                   	push   %rbx
    2d52:	4c 89 c3             	mov    %r8,%rbx
    2d55:	85 c9                	test   %ecx,%ecx
    2d57:	75 17                	jne    2d70 <driver_post+0x1f>
    2d59:	48 85 ff             	test   %rdi,%rdi
    2d5c:	74 05                	je     2d63 <driver_post+0x12>
    2d5e:	80 3f 00             	cmpb   $0x0,(%rdi)
    2d61:	75 31                	jne    2d94 <driver_post+0x43>
    2d63:	66 c7 03 4f 4b       	movw   $0x4b4f,(%rbx)
    2d68:	c6 43 02 00          	movb   $0x0,0x2(%rbx)
    2d6c:	89 c8                	mov    %ecx,%eax
    2d6e:	5b                   	pop    %rbx
    2d6f:	c3                   	ret
    2d70:	48 89 d6             	mov    %rdx,%rsi
    2d73:	48 8d 3d 98 09 00 00 	lea    0x998(%rip),%rdi        # 3712 <array.0+0x4d2>
    2d7a:	b8 00 00 00 00       	mov    $0x0,%eax
    2d7f:	e8 2c e3 ff ff       	call   10b0 <printf@plt>
    2d84:	66 c7 03 4f 4b       	movw   $0x4b4f,(%rbx)
    2d89:	c6 43 02 00          	movb   $0x0,0x2(%rbx)
    2d8d:	b8 00 00 00 00       	mov    $0x0,%eax
    2d92:	eb da                	jmp    2d6e <driver_post+0x1d>
    2d94:	41 50                	push   %r8
    2d96:	52                   	push   %rdx
    2d97:	4c 8d 0d 8b 09 00 00 	lea    0x98b(%rip),%r9        # 3729 <array.0+0x4e9>
    2d9e:	49 89 f0             	mov    %rsi,%r8
    2da1:	48 89 f9             	mov    %rdi,%rcx
    2da4:	48 8d 15 86 09 00 00 	lea    0x986(%rip),%rdx        # 3731 <array.0+0x4f1>
    2dab:	be 50 00 00 00       	mov    $0x50,%esi
    2db0:	48 8d 3d 50 09 00 00 	lea    0x950(%rip),%rdi        # 3707 <array.0+0x4c7>
    2db7:	e8 6e f5 ff ff       	call   232a <submitr>
    2dbc:	48 83 c4 10          	add    $0x10,%rsp
    2dc0:	eb ac                	jmp    2d6e <driver_post+0x1d>
    2dc2:	66 2e 0f 1f 84 00 00 	cs nopw 0x0(%rax,%rax,1)
    2dc9:	00 00 00 
    2dcc:	0f 1f 40 00          	nopl   0x0(%rax)

0000000000002dd0 <__libc_csu_init>:
    2dd0:	f3 0f 1e fa          	endbr64
    2dd4:	41 57                	push   %r15
    2dd6:	4c 8d 3d 0b 20 00 00 	lea    0x200b(%rip),%r15        # 4de8 <__frame_dummy_init_array_entry>
    2ddd:	41 56                	push   %r14
    2ddf:	49 89 d6             	mov    %rdx,%r14
    2de2:	41 55                	push   %r13
    2de4:	49 89 f5             	mov    %rsi,%r13
    2de7:	41 54                	push   %r12
    2de9:	41 89 fc             	mov    %edi,%r12d
    2dec:	55                   	push   %rbp
    2ded:	48 8d 2d fc 1f 00 00 	lea    0x1ffc(%rip),%rbp        # 4df0 <__do_global_dtors_aux_fini_array_entry>
    2df4:	53                   	push   %rbx
    2df5:	4c 29 fd             	sub    %r15,%rbp
    2df8:	48 83 ec 08          	sub    $0x8,%rsp
    2dfc:	e8 ff e1 ff ff       	call   1000 <_init>
    2e01:	48 c1 fd 03          	sar    $0x3,%rbp
    2e05:	74 1f                	je     2e26 <__libc_csu_init+0x56>
    2e07:	31 db                	xor    %ebx,%ebx
    2e09:	0f 1f 80 00 00 00 00 	nopl   0x0(%rax)
    2e10:	4c 89 f2             	mov    %r14,%rdx
    2e13:	4c 89 ee             	mov    %r13,%rsi
    2e16:	44 89 e7             	mov    %r12d,%edi
    2e19:	41 ff 14 df          	call   *(%r15,%rbx,8)
    2e1d:	48 83 c3 01          	add    $0x1,%rbx
    2e21:	48 39 dd             	cmp    %rbx,%rbp
    2e24:	75 ea                	jne    2e10 <__libc_csu_init+0x40>
    2e26:	48 83 c4 08          	add    $0x8,%rsp
    2e2a:	5b                   	pop    %rbx
    2e2b:	5d                   	pop    %rbp
    2e2c:	41 5c                	pop    %r12
    2e2e:	41 5d                	pop    %r13
    2e30:	41 5e                	pop    %r14
    2e32:	41 5f                	pop    %r15
    2e34:	c3                   	ret
    2e35:	66 66 2e 0f 1f 84 00 	data16 cs nopw 0x0(%rax,%rax,1)
    2e3c:	00 00 00 00 

0000000000002e40 <__libc_csu_fini>:
    2e40:	f3 0f 1e fa          	endbr64
    2e44:	c3                   	ret

Disassembly of section .fini:

0000000000002e48 <_fini>:
    2e48:	f3 0f 1e fa          	endbr64
    2e4c:	48 83 ec 08          	sub    $0x8,%rsp
    2e50:	48 83 c4 08          	add    $0x8,%rsp
    2e54:	c3                   	ret
