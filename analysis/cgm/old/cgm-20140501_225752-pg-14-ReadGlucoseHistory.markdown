## do stuff with an insulin pump over RF
using ` Namespace(begin=None, bytesPerRecord=None, command='tweak', descr=None, dryrun=False, effectTime=None, end=None, init=False, maxRecords=None, name=None, no_postlude=False, no_prelude=False, no_rf_prelude=False, other='ReadGlucoseHistory', page=14, params=None, port='/dev/ttyUSB0', postfix=None, prefix=None, prefix_path='logs/20140501_225752-pg-14-', save=True, saveall=False, serial='584923', verbose=None) `
```
```
```
```
```
```
```
```
```javascript
{'radio': {'errors.crc': 0,
           'errors.naks': 0,
           'errors.sequence': 0,
           'errors.timeouts': 0,
           'packets.received': 782L,
           'packets.transmit': 812L},
 'usb': {'errors.crc': 0,
         'errors.naks': 0,
         'errors.sequence': 0,
         'errors.timeouts': 0,
         'packets.received': 1118L,
         'packets.transmit': 1118L}}
```
```
```
### PUMP MODEL: `ReadPumpModel:size[64]:data:'722'`
<class 'decocare.commands.ReadGlucoseHistory'> {'page': 14}
response: ReadGlucoseHistory:size[1024]:[page][0]:data[1024]:
hexdump:
```python
0000   0x30 0x32 0x35 0x13 0x37 0x3a 0x3d 0x3f    025.7:=?
0008   0x41 0x43 0x44 0x45 0x46 0x48 0x49 0x4b    ACDEFHIK
0010   0x4c 0x4d 0x4c 0x4d 0x52 0x57 0x5a 0x5b    LMLMRWZ[
0018   0x5b 0x5c 0x60 0x63 0x67 0x6a 0x6b 0x69    [\`cgjki
0020   0x67 0x13 0x65 0x62 0x5f 0x5a 0x55 0x4f    g.eb_ZUO
0028   0x4a 0x46 0x42 0x3f 0x3c 0x39 0x37 0x35    JFB?<975
0030   0x32 0x31 0x2f 0x2d 0x2b 0x2a 0x28 0x3c    21/-+*(<
0038   0x0e 0x0e 0x20 0x57 0x0e 0x27 0x27 0x23    .. W.''#
0040   0xfb 0x0c 0x0e 0x0e 0x2f 0x57 0x0f 0x26    ..../W.&
0048   0x2a 0x2e 0x33 0x36 0x39 0x3c 0x13 0x3f    *.369<.?
0050   0x13 0x3d 0x13 0x3a 0x13 0x36 0x13 0x33    .=.:.6.3
0058   0x13 0x30 0x0e 0x4f 0x33 0x40 0x08 0x13    .0.O3@..
0060   0x2f 0x2f 0x34 0x3b 0x40 0x41 0x42 0x42    //4;@ABB
0068   0x44 0x47 0x4a 0x4d 0x50 0x52 0x54 0x13    DGJMPRT.
0070   0x56 0x13 0x56 0x13 0x55 0x13 0x54 0x13    V.V.U.T.
0078   0x54 0x13 0x54 0x0e 0x4f 0x24 0x42 0x08    T.T.O$B.
0080   0x13 0x54 0x58 0x5c 0x5e 0x60 0x61 0x62    .TX\^`ab
0088   0x63 0x63 0x64 0x65 0x65 0x66 0x66 0x66    ccdeefff
0090   0x66 0x65 0x64 0x63 0x64 0x66 0x66 0x66    fedcdfff
0098   0x65 0x64 0x62 0x5e 0x5b 0x59 0x59 0x58    edb^[YYX
00A0   0x59 0x5c 0x5e 0x60 0x61 0x62 0x62 0x62    Y\^`abbb
00A8   0x63 0x63 0x62 0x62 0x61 0x60 0x5f 0x5e    ccbba`_^
00B0   0x5d 0x5c 0x5b 0x5a 0x54 0x52 0x51 0x50    ]\[ZTRQP
00B8   0x13 0x50 0x13 0x50 0x4e 0x4e 0x4e 0xcb    .P.PNNN.
00C0   0x0e 0x0f 0x28 0x47 0x0e 0x4e 0x4e 0x63    ..(G.NNc
00C8   0x52 0x10 0x0e 0x0f 0x33 0x47 0x0f 0x64    R...3G.d
00D0   0x65 0x64 0x62 0x5f 0x5b 0x58 0x54 0x4f    edb_[XTO
00D8   0x4b 0x46 0x41 0x3e 0x3d 0x3b 0x39 0x36    KFA>=;96
00E0   0x32 0x2f 0x2c 0x2a 0x2a 0x2a 0x2a 0x2a    2/,*****
00E8   0x2b 0x2c 0x2c 0x2b 0x2b 0x2a 0x29 0x28    +,,++*)(
00F0   0x26 0x25 0x24 0x23 0x24 0x27 0x2c 0x32    &%$#$',2
00F8   0x39 0x3f 0x44 0x48 0x4b 0x4c 0x4b 0x49    9?DHKLKI
0100   0x48 0x47 0x84 0x0e 0x0f 0x0a 0x4c 0x0e    HG....L.
0108   0x47 0x47 0x45 0x99 0x0f 0x0e 0x0f 0x16    GGE.....
0110   0x4c 0x0f 0x47 0x47 0x46 0x44 0x41 0x3e    L.GGFDA>
0118   0x3c 0x13 0x02 0x0e 0x4f 0x01 0x4d 0x08    <...O.M.
0120   0x0e 0x0f 0x06 0x4d 0x0b 0x0e 0x2f 0x2f    ...M..//
0128   0x52 0x0b 0x0e 0x2f 0x30 0x52 0x0d 0x0e    R../0R..
0130   0x0f 0x00 0x53 0x0b 0x0e 0x30 0x11 0x54    ..S..0.T
0138   0x0b 0x0e 0x10 0x12 0x54 0x0b 0x0e 0x30    ....T..0
0140   0x12 0x54 0x0b 0x0e 0x30 0x12 0x54 0x0d    .T..0.T.
0148   0x02 0x04 0x02 0x04 0x02 0x04 0x02 0x04    ........
0150   0x02 0x04 0x02 0x04 0x02 0x04 0x02 0x04    ........
0158   0x02 0x04 0x02 0x04 0x02 0x04 0x02 0x04    ........
0160   0x02 0x04 0x02 0x04 0x02 0x04 0x02 0x04    ........
0168   0x02 0x04 0x02 0x04 0x02 0x04 0x02 0x04    ........
0170   0x02 0x04 0x02 0x04 0x00 0x03 0xd1 0x0e    ........
0178   0x10 0x0b 0x56 0x0e 0x01 0x03 0x01 0x03    ..V.....
0180   0x68 0x05 0x16 0x0e 0x10 0x1a 0x56 0x0f    h.....V.
0188   0x67 0x66 0x65 0x64 0x63 0x61 0x61 0x63    gfedcaac
0190   0x63 0x61 0x5e 0xd8 0x0e 0x10 0x1a 0x57    ca^....W
0198   0x0e 0x5a 0x56 0x53 0x5c 0x27 0x19 0x0e    .ZVS\'..
01A0   0x10 0x29 0x57 0x0f 0x59 0x54 0x4d 0x45    .)W.YTME
01A8   0x3f 0x3a 0x34 0x2e 0x2a 0x28 0x27 0x26    ?:4.*('&
01B0   0x26 0x26 0x25 0x25 0x25 0x25 0x25 0x25    &&%%%%%%
01B8   0x25 0x25 0x25 0x25 0x25 0x25 0x26 0x26    %%%%%%&&
01C0   0x26 0x26 0x26 0x26 0x26 0x26 0x26 0x26    &&&&&&&&
01C8   0x25 0x25 0x25 0x25 0x25 0x24 0x25 0x25    %%%%%$%%
01D0   0x26 0x27 0x28 0x2a 0x2c 0x2e 0x2f 0x31    &'(*,./1
01D8   0x35 0x39 0x3d 0x40 0x44 0x48 0x4c 0x4e    59=@DHLN
01E0   0x53 0x5c 0x61 0x62 0x66 0x69 0x6b 0x6b    S\abfikk
01E8   0x6c 0x6c 0x6d 0x6e 0x6f 0x71 0x72 0x73    llmnoqrs
01F0   0x74 0x74 0x74 0x74 0x73 0x72 0x70 0x6e    ttttsrpn
01F8   0x6c 0xa7 0x0e 0x11 0x31 0x46 0x0e 0x6b    l...1F.k
0200   0x6a 0x5c 0xe0 0x15 0x0e 0x11 0x01 0x47    j\.....G
0208   0x0f 0x5b 0x5b 0x5a 0x5a 0x5b 0x5b 0x5b    .[[ZZ[[[
0210   0x5a 0x59 0x57 0x55 0x53 0x54 0x85 0x0e    ZYWUST..
0218   0x11 0x09 0x48 0x0e 0x55 0x54 0x4d 0x2c    ..H.UTM,
0220   0x14 0x0e 0x11 0x15 0x48 0x0f 0x4c 0x4b    ....H.LK
0228   0x49 0x46 0x42 0x40 0x3f 0x71 0x0e 0x11    IFB@?q..
0230   0x39 0x48 0x0e 0x13 0x3e 0x0e 0x51 0x00    9H..>.Q.
0238   0x49 0x08 0x13 0x3c 0x3a 0xbc 0x13 0x0e    I..<:...
0240   0x11 0x0b 0x49 0x0f 0x13 0x38 0x37 0x36    ..I..876
0248   0x36 0x37 0x37 0x36 0x35 0x35 0x35 0x5e    6776555^
0250   0x0e 0x11 0x01 0x4a 0x0e 0x35 0x35 0x31    ...J.551
0258   0x91 0x12 0x0e 0x11 0x10 0x4a 0x0f 0x30    .....J.0
0260   0x2f 0x2f 0x32 0x38 0x3d 0x42 0x48 0x4d    //28=BHM
0268   0x50 0x51 0x52 0x53 0x53 0x53 0x52 0x50    PQRSSSRP
0270   0x13 0x4e 0x4c 0x4b 0x4a 0x48 0x46 0x44    .NLKJHFD
0278   0x13 0x41 0x3e 0x3b 0x38 0x37 0x36 0x36    .A>;8766
0280   0x37 0x37 0x36 0x35 0x36 0x35 0x34 0x33    77656543
0288   0x30 0x2f 0x31 0x33 0x34 0x35 0x36 0x36    0/134566
0290   0x37 0x36 0x35 0x35 0x38 0x3a 0x3d 0x3f    76558:=?
0298   0x40 0x41 0x41 0x41 0x42 0x42 0x43 0x45    @AAABBCE
02A0   0x47 0x79 0x0e 0x11 0x26 0x4f 0x0e 0x49    Gy..&O.I
02A8   0x4b 0x42 0x0c 0x10 0x0e 0x11 0x33 0x4f    KB....3O
02B0   0x0f 0x44 0x45 0x48 0x4b 0x4d 0x50 0x54    .DEHKMPT
02B8   0x56 0x13 0x58 0x59 0x13 0x5b 0x5c 0x5e    V.XY.[\^
02C0   0x5e 0x5e 0x5f 0x62 0x63 0x65 0x65 0x65    ^^_bceee
02C8   0x65 0x65 0x66 0x66 0x67 0x67 0x67 0x68    eeffgggh
02D0   0x68 0x68 0x66 0x64 0x62 0x61 0x61 0x60    hhfdbaa`
02D8   0x5f 0x5e 0x5e 0x5f 0x61 0x62 0x63 0xbd    _^^_abc.
02E0   0x0e 0x11 0x20 0x53 0x0e 0x66 0x69 0x61    .. S.fia
02E8   0x88 0x0e 0x0e 0x11 0x2e 0x53 0x0f 0x62    .....S.b
02F0   0x62 0x61 0x5e 0x59 0x55 0x52 0x4e 0x4a    ba^YURNJ
02F8   0x46 0x42 0x3e 0x3a 0x35 0x30 0x2b 0x27    FB>:50+'
0300   0x26 0x26 0x27 0x2a 0x2e 0x32 0x36 0x39    &&'*.269
0308   0x3a 0x3a 0x3a 0x3a 0x3a 0x3a 0x3a 0x5b    :::::::[
0310   0x0e 0x11 0x1e 0x56 0x0e 0x3b 0x3b 0x3b    ...V.;;;
0318   0x37 0x44 0x0d 0x0e 0x11 0x2e 0x56 0x0f    7D....V.
0320   0x38 0x3a 0x39 0x37 0x35 0x36 0x37 0x38    8:975678
0328   0x38 0x38 0x38 0x38 0x39 0x39 0x3a 0x3b    888899:;
0330   0x3b 0x3c 0x3d 0x3e 0x3f 0x40 0x41 0x43    ;<=>?@AC
0338   0x44 0x46 0x48 0x4b 0x4d 0x4f 0x51 0x53    DFHKMOQS
0340   0x53 0x52 0x51 0x51 0x54 0x58 0x5a 0x5c    SRQQTXZ\
0348   0x5d 0x5e 0x5f 0x60 0x61 0x61 0x62 0x62    ]^_`aabb
0350   0x62 0x62 0x63 0x63 0x64 0x64 0x64 0x64    bbccdddd
0358   0x64 0x63 0x63 0x63 0x63 0x63 0x63 0x61    dcccccca
0360   0x5e 0x5a 0x58 0x58 0x59 0x5a 0x5b 0x5c    ^ZXXYZ[\
0368   0x5d 0x5d 0x5d 0x5d 0x5c 0x5c 0x5b 0x5b    ]]]]\\[[
0370   0x5a 0x5a 0x5a 0x5a 0x5a 0x5b 0x5c 0x5d    ZZZZZ[\]
0378   0x5c 0x5c 0x5b 0x5a 0x59 0x58 0x56 0x52    \\[ZYXVR
0380   0x51 0x13 0x50 0x50 0x4f 0x4e 0x4e 0x4f    Q.PPONNO
0388   0x4f 0x50 0x4f 0x4f 0x4f 0x50 0x50 0xa7    OPOOOPP.
0390   0x0e 0x12 0x3a 0x47 0x0e 0x51 0x52 0x53    ..:G.QRS
0398   0x35 0x0d 0x0e 0x12 0x0a 0x48 0x0f 0x55    5....H.U
03A0   0x57 0x56 0x53 0x4f 0x4c 0x48 0x45 0x41    WVSOLHEA
03A8   0x3d 0x3b 0x38 0x35 0x32 0x2f 0x2d 0x2c    =;852/-,
03B0   0x2c 0x2d 0x2f 0x30 0x32 0x35 0x36 0x38    ,-/02568
03B8   0x38 0x39 0x3a 0x3c 0x3f 0x41 0x43 0x45    89:<?ACE
03C0   0x47 0x48 0x48 0x48 0x49 0x49 0x49 0x49    GHHHIIII
03C8   0x49 0x49 0x47 0x46 0x45 0x43 0x40 0x3d    IIGFEC@=
03D0   0x3a 0x38 0x35 0x32 0x2f 0x2c 0x29 0x28    :852/,)(
03D8   0x27 0x28 0x29 0x2a 0x2b 0x2d 0x2e 0x30    '()*+-.0
03E0   0x32 0x33 0x35 0x36 0x59 0x0e 0x12 0x38    2356Y..8
03E8   0x4d 0x0e 0x37 0x38 0x33 0xf0 0x0b 0x0e    M.783...
03F0   0x12 0x0a 0x4e 0x0f 0x33 0x33 0x34 0x35    ..N.3345
03F8   0x35 0x0e 0x32 0x23 0x4e 0x08 0x43 0x26    5.2#N.C&
```
#### decoded:
```python
"0000   0x30 0x32 0x35 0x13 0x37 0x3a 0x3d 0x3f    025.7:=?\n0008   0x41 0x43 0x44 0x45 0x46 0x48 0x49 0x4b    ACDEFHIK\n0010   0x4c 0x4d 0x4c 0x4d 0x52 0x57 0x5a 0x5b    LMLMRWZ[\n0018   0x5b 0x5c 0x60 0x63 0x67 0x6a 0x6b 0x69    [\\`cgjki\n0020   0x67 0x13 0x65 0x62 0x5f 0x5a 0x55 0x4f    g.eb_ZUO\n0028   0x4a 0x46 0x42 0x3f 0x3c 0x39 0x37 0x35    JFB?<975\n0030   0x32 0x31 0x2f 0x2d 0x2b 0x2a 0x28 0x3c    21/-+*(<\n0038   0x0e 0x0e 0x20 0x57 0x0e 0x27 0x27 0x23    .. W.''#\n0040   0xfb 0x0c 0x0e 0x0e 0x2f 0x57 0x0f 0x26    ..../W.&\n0048   0x2a 0x2e 0x33 0x36 0x39 0x3c 0x13 0x3f    *.369<.?\n0050   0x13 0x3d 0x13 0x3a 0x13 0x36 0x13 0x33    .=.:.6.3\n0058   0x13 0x30 0x0e 0x4f 0x33 0x40 0x08 0x13    .0.O3@..\n0060   0x2f 0x2f 0x34 0x3b 0x40 0x41 0x42 0x42    //4;@ABB\n0068   0x44 0x47 0x4a 0x4d 0x50 0x52 0x54 0x13    DGJMPRT.\n0070   0x56 0x13 0x56 0x13 0x55 0x13 0x54 0x13    V.V.U.T.\n0078   0x54 0x13 0x54 0x0e 0x4f 0x24 0x42 0x08    T.T.O$B.\n0080   0x13 0x54 0x58 0x5c 0x5e 0x60 0x61 0x62    .TX\\^`ab\n0088   0x63 0x63 0x64 0x65 0x65 0x66 0x66 0x66    ccdeefff\n0090   0x66 0x65 0x64 0x63 0x64 0x66 0x66 0x66    fedcdfff\n0098   0x65 0x64 0x62 0x5e 0x5b 0x59 0x59 0x58    edb^[YYX\n00A0   0x59 0x5c 0x5e 0x60 0x61 0x62 0x62 0x62    Y\\^`abbb\n00A8   0x63 0x63 0x62 0x62 0x61 0x60 0x5f 0x5e    ccbba`_^\n00B0   0x5d 0x5c 0x5b 0x5a 0x54 0x52 0x51 0x50    ]\\[ZTRQP\n00B8   0x13 0x50 0x13 0x50 0x4e 0x4e 0x4e 0xcb    .P.PNNN.\n00C0   0x0e 0x0f 0x28 0x47 0x0e 0x4e 0x4e 0x63    ..(G.NNc\n00C8   0x52 0x10 0x0e 0x0f 0x33 0x47 0x0f 0x64    R...3G.d\n00D0   0x65 0x64 0x62 0x5f 0x5b 0x58 0x54 0x4f    edb_[XTO\n00D8   0x4b 0x46 0x41 0x3e 0x3d 0x3b 0x39 0x36    KFA>=;96\n00E0   0x32 0x2f 0x2c 0x2a 0x2a 0x2a 0x2a 0x2a    2/,*****\n00E8   0x2b 0x2c 0x2c 0x2b 0x2b 0x2a 0x29 0x28    +,,++*)(\n00F0   0x26 0x25 0x24 0x23 0x24 0x27 0x2c 0x32    &%$#$',2\n00F8   0x39 0x3f 0x44 0x48 0x4b 0x4c 0x4b 0x49    9?DHKLKI\n0100   0x48 0x47 0x84 0x0e 0x0f 0x0a 0x4c 0x0e    HG....L.\n0108   0x47 0x47 0x45 0x99 0x0f 0x0e 0x0f 0x16    GGE.....\n0110   0x4c 0x0f 0x47 0x47 0x46 0x44 0x41 0x3e    L.GGFDA>\n0118   0x3c 0x13 0x02 0x0e 0x4f 0x01 0x4d 0x08    <...O.M.\n0120   0x0e 0x0f 0x06 0x4d 0x0b 0x0e 0x2f 0x2f    ...M..//\n0128   0x52 0x0b 0x0e 0x2f 0x30 0x52 0x0d 0x0e    R../0R..\n0130   0x0f 0x00 0x53 0x0b 0x0e 0x30 0x11 0x54    ..S..0.T\n0138   0x0b 0x0e 0x10 0x12 0x54 0x0b 0x0e 0x30    ....T..0\n0140   0x12 0x54 0x0b 0x0e 0x30 0x12 0x54 0x0d    .T..0.T.\n0148   0x02 0x04 0x02 0x04 0x02 0x04 0x02 0x04    ........\n0150   0x02 0x04 0x02 0x04 0x02 0x04 0x02 0x04    ........\n0158   0x02 0x04 0x02 0x04 0x02 0x04 0x02 0x04    ........\n0160   0x02 0x04 0x02 0x04 0x02 0x04 0x02 0x04    ........\n0168   0x02 0x04 0x02 0x04 0x02 0x04 0x02 0x04    ........\n0170   0x02 0x04 0x02 0x04 0x00 0x03 0xd1 0x0e    ........\n0178   0x10 0x0b 0x56 0x0e 0x01 0x03 0x01 0x03    ..V.....\n0180   0x68 0x05 0x16 0x0e 0x10 0x1a 0x56 0x0f    h.....V.\n0188   0x67 0x66 0x65 0x64 0x63 0x61 0x61 0x63    gfedcaac\n0190   0x63 0x61 0x5e 0xd8 0x0e 0x10 0x1a 0x57    ca^....W\n0198   0x0e 0x5a 0x56 0x53 0x5c 0x27 0x19 0x0e    .ZVS\\'..\n01A0   0x10 0x29 0x57 0x0f 0x59 0x54 0x4d 0x45    .)W.YTME\n01A8   0x3f 0x3a 0x34 0x2e 0x2a 0x28 0x27 0x26    ?:4.*('&\n01B0   0x26 0x26 0x25 0x25 0x25 0x25 0x25 0x25    &&%%%%%%\n01B8   0x25 0x25 0x25 0x25 0x25 0x25 0x26 0x26    %%%%%%&&\n01C0   0x26 0x26 0x26 0x26 0x26 0x26 0x26 0x26    &&&&&&&&\n01C8   0x25 0x25 0x25 0x25 0x25 0x24 0x25 0x25    %%%%%$%%\n01D0   0x26 0x27 0x28 0x2a 0x2c 0x2e 0x2f 0x31    &'(*,./1\n01D8   0x35 0x39 0x3d 0x40 0x44 0x48 0x4c 0x4e    59=@DHLN\n01E0   0x53 0x5c 0x61 0x62 0x66 0x69 0x6b 0x6b    S\\abfikk\n01E8   0x6c 0x6c 0x6d 0x6e 0x6f 0x71 0x72 0x73    llmnoqrs\n01F0   0x74 0x74 0x74 0x74 0x73 0x72 0x70 0x6e    ttttsrpn\n01F8   0x6c 0xa7 0x0e 0x11 0x31 0x46 0x0e 0x6b    l...1F.k\n0200   0x6a 0x5c 0xe0 0x15 0x0e 0x11 0x01 0x47    j\\.....G\n0208   0x0f 0x5b 0x5b 0x5a 0x5a 0x5b 0x5b 0x5b    .[[ZZ[[[\n0210   0x5a 0x59 0x57 0x55 0x53 0x54 0x85 0x0e    ZYWUST..\n0218   0x11 0x09 0x48 0x0e 0x55 0x54 0x4d 0x2c    ..H.UTM,\n0220   0x14 0x0e 0x11 0x15 0x48 0x0f 0x4c 0x4b    ....H.LK\n0228   0x49 0x46 0x42 0x40 0x3f 0x71 0x0e 0x11    IFB@?q..\n0230   0x39 0x48 0x0e 0x13 0x3e 0x0e 0x51 0x00    9H..>.Q.\n0238   0x49 0x08 0x13 0x3c 0x3a 0xbc 0x13 0x0e    I..<:...\n0240   0x11 0x0b 0x49 0x0f 0x13 0x38 0x37 0x36    ..I..876\n0248   0x36 0x37 0x37 0x36 0x35 0x35 0x35 0x5e    6776555^\n0250   0x0e 0x11 0x01 0x4a 0x0e 0x35 0x35 0x31    ...J.551\n0258   0x91 0x12 0x0e 0x11 0x10 0x4a 0x0f 0x30    .....J.0\n0260   0x2f 0x2f 0x32 0x38 0x3d 0x42 0x48 0x4d    //28=BHM\n0268   0x50 0x51 0x52 0x53 0x53 0x53 0x52 0x50    PQRSSSRP\n0270   0x13 0x4e 0x4c 0x4b 0x4a 0x48 0x46 0x44    .NLKJHFD\n0278   0x13 0x41 0x3e 0x3b 0x38 0x37 0x36 0x36    .A>;8766\n0280   0x37 0x37 0x36 0x35 0x36 0x35 0x34 0x33    77656543\n0288   0x30 0x2f 0x31 0x33 0x34 0x35 0x36 0x36    0/134566\n0290   0x37 0x36 0x35 0x35 0x38 0x3a 0x3d 0x3f    76558:=?\n0298   0x40 0x41 0x41 0x41 0x42 0x42 0x43 0x45    @AAABBCE\n02A0   0x47 0x79 0x0e 0x11 0x26 0x4f 0x0e 0x49    Gy..&O.I\n02A8   0x4b 0x42 0x0c 0x10 0x0e 0x11 0x33 0x4f    KB....3O\n02B0   0x0f 0x44 0x45 0x48 0x4b 0x4d 0x50 0x54    .DEHKMPT\n02B8   0x56 0x13 0x58 0x59 0x13 0x5b 0x5c 0x5e    V.XY.[\\^\n02C0   0x5e 0x5e 0x5f 0x62 0x63 0x65 0x65 0x65    ^^_bceee\n02C8   0x65 0x65 0x66 0x66 0x67 0x67 0x67 0x68    eeffgggh\n02D0   0x68 0x68 0x66 0x64 0x62 0x61 0x61 0x60    hhfdbaa`\n02D8   0x5f 0x5e 0x5e 0x5f 0x61 0x62 0x63 0xbd    _^^_abc.\n02E0   0x0e 0x11 0x20 0x53 0x0e 0x66 0x69 0x61    .. S.fia\n02E8   0x88 0x0e 0x0e 0x11 0x2e 0x53 0x0f 0x62    .....S.b\n02F0   0x62 0x61 0x5e 0x59 0x55 0x52 0x4e 0x4a    ba^YURNJ\n02F8   0x46 0x42 0x3e 0x3a 0x35 0x30 0x2b 0x27    FB>:50+'\n0300   0x26 0x26 0x27 0x2a 0x2e 0x32 0x36 0x39    &&'*.269\n0308   0x3a 0x3a 0x3a 0x3a 0x3a 0x3a 0x3a 0x5b    :::::::[\n0310   0x0e 0x11 0x1e 0x56 0x0e 0x3b 0x3b 0x3b    ...V.;;;\n0318   0x37 0x44 0x0d 0x0e 0x11 0x2e 0x56 0x0f    7D....V.\n0320   0x38 0x3a 0x39 0x37 0x35 0x36 0x37 0x38    8:975678\n0328   0x38 0x38 0x38 0x38 0x39 0x39 0x3a 0x3b    888899:;\n0330   0x3b 0x3c 0x3d 0x3e 0x3f 0x40 0x41 0x43    ;<=>?@AC\n0338   0x44 0x46 0x48 0x4b 0x4d 0x4f 0x51 0x53    DFHKMOQS\n0340   0x53 0x52 0x51 0x51 0x54 0x58 0x5a 0x5c    SRQQTXZ\\\n0348   0x5d 0x5e 0x5f 0x60 0x61 0x61 0x62 0x62    ]^_`aabb\n0350   0x62 0x62 0x63 0x63 0x64 0x64 0x64 0x64    bbccdddd\n0358   0x64 0x63 0x63 0x63 0x63 0x63 0x63 0x61    dcccccca\n0360   0x5e 0x5a 0x58 0x58 0x59 0x5a 0x5b 0x5c    ^ZXXYZ[\\\n0368   0x5d 0x5d 0x5d 0x5d 0x5c 0x5c 0x5b 0x5b    ]]]]\\\\[[\n0370   0x5a 0x5a 0x5a 0x5a 0x5a 0x5b 0x5c 0x5d    ZZZZZ[\\]\n0378   0x5c 0x5c 0x5b 0x5a 0x59 0x58 0x56 0x52    \\\\[ZYXVR\n0380   0x51 0x13 0x50 0x50 0x4f 0x4e 0x4e 0x4f    Q.PPONNO\n0388   0x4f 0x50 0x4f 0x4f 0x4f 0x50 0x50 0xa7    OPOOOPP.\n0390   0x0e 0x12 0x3a 0x47 0x0e 0x51 0x52 0x53    ..:G.QRS\n0398   0x35 0x0d 0x0e 0x12 0x0a 0x48 0x0f 0x55    5....H.U\n03A0   0x57 0x56 0x53 0x4f 0x4c 0x48 0x45 0x41    WVSOLHEA\n03A8   0x3d 0x3b 0x38 0x35 0x32 0x2f 0x2d 0x2c    =;852/-,\n03B0   0x2c 0x2d 0x2f 0x30 0x32 0x35 0x36 0x38    ,-/02568\n03B8   0x38 0x39 0x3a 0x3c 0x3f 0x41 0x43 0x45    89:<?ACE\n03C0   0x47 0x48 0x48 0x48 0x49 0x49 0x49 0x49    GHHHIIII\n03C8   0x49 0x49 0x47 0x46 0x45 0x43 0x40 0x3d    IIGFEC@=\n03D0   0x3a 0x38 0x35 0x32 0x2f 0x2c 0x29 0x28    :852/,)(\n03D8   0x27 0x28 0x29 0x2a 0x2b 0x2d 0x2e 0x30    '()*+-.0\n03E0   0x32 0x33 0x35 0x36 0x59 0x0e 0x12 0x38    2356Y..8\n03E8   0x4d 0x0e 0x37 0x38 0x33 0xf0 0x0b 0x0e    M.783...\n03F0   0x12 0x0a 0x4e 0x0f 0x33 0x33 0x34 0x35    ..N.3345\n03F8   0x35 0x0e 0x32 0x23 0x4e 0x08 0x43 0x26    5.2#N.C&"
```
### end stats
```
```
```javascript
{'radio': {'errors.crc': 0,
           'errors.naks': 0,
           'errors.sequence': 0,
           'errors.timeouts': 0,
           'packets.received': 800L,
           'packets.transmit': 831L},
 'usb': {'errors.crc': 0,
         'errors.naks': 0,
         'errors.sequence': 0,
         'errors.timeouts': 0,
         'packets.received': 1142L,
         'packets.transmit': 1142L}}
```
