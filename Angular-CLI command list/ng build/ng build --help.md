ng build --help

```
ng build [project]

Compiles an Angular application or library into an output directory named dist/ at the given output path.

Arguments:
  project  The name of the project to build. Can be an application or a library.       [string] [choices: "app-project"]

Options:
      --help                            Shows a help message for this command in the console.                  [boolean]
  -c, --configuration                   One or more named builder configurations as a comma-separated list as specified
                                        in the "configurations" section in angular.json.
                                        The builder uses the named configurations to run the given target.
                                        For more information, see https://angular.dev/reference/configs/workspace-config
                                        #alternate-build-configurations.
                                                                  [string] [choices: "development", "hmr", "production"]
      --allowed-common-js-dependencies  A list of CommonJS or AMD packages that are allowed to be used without a build
                                        time warning. Use `'*'` to allow all.                                    [array]
      --aot                             Build using Ahead of Time compilation.                 [boolean] [default: true]
      --app-shell                       Generates an application shell during build time.                      [boolean]
      --base-href                       Base url for the application being built.                               [string]
      --browser                         The full path for the browser entry point to the application, relative to the
                                        current workspace.                                                      [string]
      --clear-screen                    Automatically clear the terminal screen during rebuilds.
                                                                                              [boolean] [default: false]
      --cross-origin                    Define the crossorigin attribute setting of elements that provide CORS support.
                                            [string] [choices: "none", "anonymous", "use-credentials"] [default: "none"]
      --define                          Defines global identifiers that will be replaced with a specified constant value
                                        when found in any JavaScript or TypeScript code including libraries. The value
                                        will be used directly. String values must be put in quotes. Identifiers within
                                        Angular metadata such as Component Decorators will not be replaced.      [array]
      --delete-output-path              Delete the output path before building.                [boolean] [default: true]
      --deploy-url                      Customize the base path for the URLs of resources in 'index.html' and component
                                        stylesheets. This option is only necessary for specific deployment scenarios,
                                        such as with Angular Elements or when utilizing different CDN locations.[string]
      --external-dependencies           Exclude the listed external dependencies from being bundled into the bundle.
                                        Instead, the created bundle relies on these dependencies to be available during
                                        runtime.                                                                 [array]
      --extract-licenses                Extract all licenses in a separate file.               [boolean] [default: true]
      --i18n-duplicate-translation      How to handle duplicate translations for i18n.
                                                   [string] [choices: "warning", "error", "ignore"] [default: "warning"]
      --i18n-missing-translation        How to handle missing translations for i18n.
                                                   [string] [choices: "warning", "error", "ignore"] [default: "warning"]
      --index                           Configures the generation of the application's HTML index.              [string]
      --inline-style-language           The stylesheet language to use for the application's inline component styles.
                                                      [string] [choices: "css", "less", "sass", "scss"] [default: "css"]
      --localize                        Translate the bundles in one or more locales.                          [boolean]
      --named-chunks                    Use file name for lazy loaded chunks.                 [boolean] [default: false]
      --optimization                    Enables optimization of the build output. Including minification of scripts and
                                        styles, tree-shaking, dead-code elimination, inlining of critical CSS and fonts
                                        inlining. For more information, see https://angular.dev/reference/configs/worksp
                                        ace-config#optimization-configuration.                 [boolean] [default: true]
      --output-hashing                  Define the output filename cache-busting hashing mode.
                                                 [string] [choices: "none", "all", "media", "bundles"] [default: "none"]
      --output-mode                     Defines the build output target. 'static': Generates a static site for
                                        deployment on any static hosting service. 'server': Produces an application
                                        designed for deployment on a server that supports server-side rendering (SSR).
                                                                                  [string] [choices: "static", "server"]
      --output-path                     Specify the output path relative to workspace root.                     [string]
      --poll                            Enable and define the file watching poll time period in milliseconds.   [number]
      --polyfills                       A list of polyfills to include in the build. Can be a full path for a file,
                                        relative to the current workspace or module specifier. Example: 'zone.js'.
                                                                                                                 [array]
      --prerender                       Prerender (SSG) pages of your application during build time.           [boolean]
      --preserve-symlinks               Do not use the real path when resolving modules. If unset then will default to
                                        `true` if NodeJS option --preserve-symlinks is set.                    [boolean]
      --progress                        Log progress to the console while building.            [boolean] [default: true]
      --server                          The full path for the server entry point to the application, relative to the
                                        current workspace.                                                      [string]
      --service-worker                  Generates a service worker configuration.                               [string]
      --source-map                      Output source maps for scripts and styles. For more information, see
                                        https://angular.dev/reference/configs/workspace-config#source-map-configuration.
                                                                                              [boolean] [default: false]
      --ssr                             Server side render (SSR) pages of your application during runtime.
                                                                                              [boolean] [default: false]
      --stats-json                      Generates a 'stats.json' file which can be analyzed with
                                        https://esbuild.github.io/analyze/.                   [boolean] [default: false]
      --subresource-integrity           Enables the use of subresource integrity validation.  [boolean] [default: false]
      --ts-config                       The full path for the TypeScript configuration file, relative to the current
                                        workspace.                                                              [string]
      --verbose                         Adds more details to output logging.                  [boolean] [default: false]
      --watch                           Run build when files change.                          [boolean] [default: false]
      --web-worker-ts-config            TypeScript configuration for Web Worker modules.                        [string]
```
