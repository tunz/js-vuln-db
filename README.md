# Case Study of JavaScript engine vulnerabilities

## V8
- [CVE-2013-6632](./v8/CVE-2013-6632.js): TypedArray, Integer Overflow, OOB, _Pinkie Pie_
- [CVE-2014-1705](./v8/CVE-2014-1705.js): TypedArray, Invalid Array Length, OOB, _geohot_
- [CVE-2014-3176](./v8/CVE-2014-3176.js): Array.concat, Side Effect, OOB, _lokihardt_
- [CVE-2014-7927](./v8/CVE-2014-7927.js): asm.js, Compiler, OOB, _Christian Holler_
- [CVE-2014-7928](./v8/CVE-2014-7928.js): Array, Optimization, _Christian Holler_
- [CVE-2015-1242](./v8/CVE-2015-1242.js): Type Confusion, _fcole@onshape.com_
- [CVE-2015-6764](./v8/CVE-2015-6764.js): JSON, Side Effect, OOB, Pwn2Own, _Guang Gong_, _Qihoo 360_
- [CVE-2015-6771](./v8/CVE-2015-6771.js): TypedArray, OOB
- [CVE-2015-8584](./v8/CVE-2015-8548.js): JSON, OOB
- [CVE-2016-1646](./v8/CVE-2016-1646.js): Array.concat, Side Effect, OOB, _Wen Xu_, _Tencent KeenLab_
- [CVE-2016-1653](./v8/CVE-2016-1653.js): asm.js, TypedArray, Compiler, OOB, _Choongwoo Han_
- [CVE-2016-1665](./v8/CVE-2016-1665.js): asm.js, Compiler, _HyungSeok Han_
- [CVE-2016-1669](./v8/CVE-2016-1669.js): RegExp, Heap Overflow, Integer Overflow, _Choongwoo Han_
- [CVE-2016-1677](./v8/CVE-2016-1677.js): Side Effect, Information Leak, _Guang Gong_, _Qihoo 360_
- [CVE-2016-1688](./v8/CVE-2016-1688.js): RegExp, _Max Korenko_
- [CVE-2016-5129](./v8/CVE-2016-5129.js): Array, Side Effect, _Jeonghoon Shin_
- [CVE-2016-5172](./v8/CVE-2016-5172.js): Scope, _Choongwoo Han_

## JavaScriptCore
- [CVE-2016-4622](./jsc/CVE-2016-4622.js): Array.slice, OOB, _Samuel Groß_

## ChakraCore
- [CVE-2016-3386](./chakra/CVE-2016-3386.js): Spread Operator, Stack Overflow, _Richard Zhu_
- [CVE-2016-7189](./chakra/CVE-2016-7189.js): Array.join, Information Leak, _Natalie Silvanovich_, _Google Project Zero_
- [CVE-2016-7190](./chakra/CVE-2016-7190.js): Array.map, Heap Overflow, _Natalie Silvanovich_, _Google Project Zero_
- [CVE-2016-7194](./chakra/CVE-2016-7194.js): Function.apply, Information Leak, _Natalie Silvanovich_, _Google Project Zero_
- [CVE-2016-7200](./chakra/CVE-2016-7200.js): Array.filter, Heap Corruption, _Natalie Silvanovich_, _Google Project Zero_
- [CVE-2016-7202](./chakra/CVE-2016-7202.js): Array.reverse, Overflow, _Natalie Silvanovich_, _Google Project Zero_
- [CVE-2016-7203](./chakra/CVE-2016-7203.js): Array.splice, Heap Overflow, _Natalie Silvanovich_, _Google Project Zero_
- [CVE-2016-7240](./chakra/CVE-2016-7240.js): eval, Proxy, Type Confusion, _Natalie Silvanovich_, _Google Project Zero_
- [CVE-2016-7241](./chakra/CVE-2016-7241.js): JSON.parse, Information Leak, _Natalie Silvanovich_, _Google Project Zero_
- [CVE-2016-7286](./chakra/CVE-2016-7286.js): SIMD.toLocaleString, Uninitialized Memory, _Natalie Silvanovich_, _Google Project Zero_
- [CVE-2016-7287](./chakra/CVE-2016-7287.js): Intl, Initialization, Type Confusion, _Natalie Silvanovich_, _Google Project Zero_
