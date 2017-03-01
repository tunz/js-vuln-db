# Case Study of JavaScript engine vulnerabilities

## V8
- [CVE-2013-6632](./v8/CVE-2013-6632.md): TypedArray, Integer Overflow, OOB, _Pinkie Pie_
- [CVE-2014-1705](./v8/CVE-2014-1705.md): TypedArray, Invalid Array Length, OOB, _geohot_
- [CVE-2014-3176](./v8/CVE-2014-3176.md): Array.concat, Side Effect, OOB, _lokihardt_
- [CVE-2014-7927](./v8/CVE-2014-7927.md): asm.js, Compiler, OOB, _Christian Holler_
- [CVE-2014-7928](./v8/CVE-2014-7928.md): Array, Optimization, _Christian Holler_
- [CVE-2015-1233](./v8/CVE-2015-1233.md): Array, Optimization, OOB
- [CVE-2015-1242](./v8/CVE-2015-1242.md): Type Confusion, _fcole@onshape.com_
- [CVE-2015-6764](./v8/CVE-2015-6764.md): JSON.stringify, Side Effect, OOB, Pwn2Own, _Guang Gong_, _Qihoo 360_
- [CVE-2015-6771](./v8/CVE-2015-6771.md): TypedArray, OOB
- [CVE-2015-8584](./v8/CVE-2015-8548.md): JSON, OOB
- [CVE-2016-1646](./v8/CVE-2016-1646.md): Array.concat, Side Effect, OOB, _Wen Xu_, _Tencent KeenLab_
- [CVE-2016-1653](./v8/CVE-2016-1653.md): asm.js, TypedArray, Optimization, OOB, _Choongwoo Han_
- [CVE-2016-1665](./v8/CVE-2016-1665.md): asm.js, Compiler, _HyungSeok Han_
- [CVE-2016-1669](./v8/CVE-2016-1669.md): RegExp, Heap Overflow, Integer Overflow, _Choongwoo Han_
- [CVE-2016-1677](./v8/CVE-2016-1677.md): Side Effect, Information Leak, _Guang Gong_, _Qihoo 360_
- [CVE-2016-1688](./v8/CVE-2016-1688.md): RegExp, _Max Korenko_
- [CVE-2016-5129](./v8/CVE-2016-5129.md): Array, Side Effect, _Jeonghoon Shin_
- [CVE-2016-5172](./v8/CVE-2016-5172.md): Scope, _Choongwoo Han_
- [CVE-2016-5198](./v8/CVE-2016-5198.md): parseInt, Compiler, Optimization, OOB, _Tencent Keen Security Lab_
- [CVE-2016-5200](./v8/CVE-2016-5200.md): asm.js, TypedArray, Optimization, OOB, _Choongwoo Han_
- [CVE-2016-9651](./v8/CVE-2016-9651.md): Object.assign, Property, _Guang Gong_, _Qihoo 360_

## ChakraCore
- [CVE-2016-3386](./chakra/CVE-2016-3386.md): Spread Operator, Stack Overflow, _Richard Zhu_
- [CVE-2016-7189](./chakra/CVE-2016-7189.md): Array.join, Information Leak, _Natalie Silvanovich_, _Google Project Zero_
- [CVE-2016-7190](./chakra/CVE-2016-7190.md): Array.map, Heap Overflow, _Natalie Silvanovich_, _Google Project Zero_
- [CVE-2016-7194](./chakra/CVE-2016-7194.md): Function.apply, Information Leak, _Natalie Silvanovich_, _Google Project Zero_
- [CVE-2016-7200](./chakra/CVE-2016-7200.md): Array.filter, Heap Corruption, _Natalie Silvanovich_, _Google Project Zero_
- [CVE-2016-7201](./chakra/CVE-2016-7201.md): Array, Prototype, Type Confusion, _Natalie Silvanovich_, _Google Project Zero_
- [CVE-2016-7202](./chakra/CVE-2016-7202.md): Array.reverse, Overflow, _Natalie Silvanovich_, _Google Project Zero_
- [CVE-2016-7203](./chakra/CVE-2016-7203.md): Array.splice, Heap Overflow, _Natalie Silvanovich_, _Google Project Zero_
- [CVE-2016-7240](./chakra/CVE-2016-7240.md): eval, Proxy, Type Confusion, _Natalie Silvanovich_, _Google Project Zero_
- [CVE-2016-7241](./chakra/CVE-2016-7241.md): JSON.parse, Information Leak, _Natalie Silvanovich_, _Google Project Zero_
- [CVE-2016-7286](./chakra/CVE-2016-7286.md): SIMD.toLocaleString, Uninitialized Memory, _Natalie Silvanovich_, _Google Project Zero_
- [CVE-2016-7287](./chakra/CVE-2016-7287.md): Intl, Initialization, Type Confusion, _Natalie Silvanovich_, _Google Project Zero_
- [CVE-2016-7288](./chakra/CVE-2016-7288.md): TypedArray, sort, Use After Free, Buffer Neutering, Side Effect, _Natalie Silvanovich_, _Google Project Zero_

## JavaScriptCore
- [CVE-2016-1857](./jsc/CVE-2016-1857.md): Array.join, Use After Free, Side Effect, _KeenLab Tencent_, (_Liang Chen_, _Zhen Feng_, _wushi_), _Jeonghoon Shin_
- [CVE-2016-4622](./jsc/CVE-2016-4622.md): Array.slice, OOB, Side Effect, _Samuel Groß_
- [CVE-2016-4734](./jsc/CVE-2016-4734.md): TypedArray.copyWithin, TypedArray.fill, Buffer Neutering, Side Effect, _Natalie Silvanovich_, _Google Project Zero_

## SpiderMonkey
- [CVE-2014-1513](./spidermonkey/CVE-2014-1513.md): TypedArray.subarray, OOB, Buffer Neutering, Side Effect,  _Jüri Aedla_
