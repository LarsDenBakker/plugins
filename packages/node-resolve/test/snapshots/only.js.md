# Snapshot report for `test/only.js`

The actual snapshot is saved in `only.js.snap`.

Generated by [AVA](https://ava.li).

## regex

> Snapshot 1

    [
      {
        code: 'UNRESOLVED_IMPORT',
        importer: 'only.js',
        message: '\'test\' is imported by only.js, but could not be resolved – treating it as an external dependency',
        source: 'test',
        toString: Function {},
        url: 'https://rollupjs.org/guide/en/#warning-treating-module-as-external-dependency',
      },
    ]

## specify the only packages to resolve

> Snapshot 1

    [
      {
        code: 'UNRESOLVED_IMPORT',
        importer: 'only.js',
        message: '\'@scoped/foo\' is imported by only.js, but could not be resolved – treating it as an external dependency',
        source: '@scoped/foo',
        toString: Function {},
        url: 'https://rollupjs.org/guide/en/#warning-treating-module-as-external-dependency',
      },
      {
        code: 'UNRESOLVED_IMPORT',
        importer: 'only.js',
        message: '\'@scoped/bar\' is imported by only.js, but could not be resolved – treating it as an external dependency',
        source: '@scoped/bar',
        toString: Function {},
        url: 'https://rollupjs.org/guide/en/#warning-treating-module-as-external-dependency',
      },
    ]
