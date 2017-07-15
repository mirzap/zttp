# Zttp

**Important disclaimer :**

This package is a fork of [kitetail/zttp](https://github.com/kitetail/zttp) for those who love PSR-2 and type-hinting.
All credit must go to its authors, they did an amazing work.

Feel free to contribute and integrate changes from original repository to this one.

**end of disclaimer**

## Intallation

```
composer require mirzap/zttp
```

## Documentation

From [kitetail/zttp](https://github.com/kitetail/zttp)

Zttp is a simple Guzzle wrapper designed to provide a really pleasant development experience for most common use cases.

If you need more functionality, just use [Guzzle](https://github.com/guzzle/guzzle) :)

Real documentation is in the works, but for now [read the tests](https://github.com/soyhuce/zttp/blob/master/tests/ZttpTest.php).

```php
$response = Zttp::withHeaders(['Fancy' => 'Pants'])->post($url, [
    'foo' => 'bar',
    'baz' => 'qux',
]);

$response->json();
// => [
//  'whatever' => 'was returned',
// ];
```

