<a name="0.0.1"></a>
# [0.0.1]() (2018-11-17)

### Features

* **core:** startup faster by [Enabling webpack, Adding uglification and Performing heap snapshots](https://docs.nativescript.org/performance-optimizations)

```bash
    npm install --save-dev nativescript-dev-webpack
    npm install
    
    tns run android --bundle --env.uglify --env.aot --env.snapshot
    tns build android --bundle --env.snapshot --release --keyStorePath ~/path/to/keystore --keyStorePassword your-pass --keyStoreAlias your-alias --keyStoreAliasPassword your-alias-pass

    tns run ios --bundle --env.uglify --env.aot 
    tns build ios --bundle --release --forDevice --teamId TEAM_ID
    tns publish ios --ipa ipa-file-path-here

```

```
    tns build android|ios --bundle --env.uglify
```

To build with Ahead-of-Time compilation provide the --env.aot flag:

```
    $ tns build android|ios --bundle --env.aot
```

<a name="0.0.0"></a>
# [0.0.0]() (2018-11-09)

### Features

* **core:** Build the application heavily based on [sample groceries](https://github.com/NativeScript/sample-Groceries)