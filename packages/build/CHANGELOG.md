# @serwist/build

## 8.4.3

### Patch Changes

- Updated dependencies []:
  - @serwist/background-sync@8.4.3
  - @serwist/broadcast-update@8.4.3
  - @serwist/cacheable-response@8.4.3
  - @serwist/core@8.4.3
  - @serwist/expiration@8.4.3
  - @serwist/google-analytics@8.4.3
  - @serwist/precaching@8.4.3
  - @serwist/routing@8.4.3

## 8.4.2

### Patch Changes

- Updated dependencies []:
  - @serwist/background-sync@8.4.2
  - @serwist/broadcast-update@8.4.2
  - @serwist/cacheable-response@8.4.2
  - @serwist/core@8.4.2
  - @serwist/expiration@8.4.2
  - @serwist/google-analytics@8.4.2
  - @serwist/precaching@8.4.2
  - @serwist/routing@8.4.2

## 8.4.1

### Patch Changes

- [#36](https://github.com/serwist/serwist/pull/36) [`d45c7a3`](https://github.com/serwist/serwist/commit/d45c7a3e62cd98eab3110038f3f90240bd5e6831) Thanks [@DuCanhGH](https://github.com/DuCanhGH)! - fix(build): fixed CommonJS build crashing (again)

  - It is `stringify-object` this time.
  - A test has been added to help avoid this issue.

- Updated dependencies []:
  - @serwist/background-sync@8.4.1
  - @serwist/broadcast-update@8.4.1
  - @serwist/cacheable-response@8.4.1
  - @serwist/core@8.4.1
  - @serwist/expiration@8.4.1
  - @serwist/google-analytics@8.4.1
  - @serwist/precaching@8.4.1
  - @serwist/routing@8.4.1

## 8.4.0

### Patch Changes

- [#32](https://github.com/serwist/serwist/pull/32) [`87fea3c`](https://github.com/serwist/serwist/commit/87fea3c8ce51eab78404e64887b3840b9f633d9d) Thanks [@DuCanhGH](https://github.com/DuCanhGH)! - chore(docs): changed docs's URL

  - Currently we deploy at Cloudflare Pages.

- Updated dependencies [[`87fea3c`](https://github.com/serwist/serwist/commit/87fea3c8ce51eab78404e64887b3840b9f633d9d)]:
  - @serwist/cacheable-response@8.4.0
  - @serwist/broadcast-update@8.4.0
  - @serwist/google-analytics@8.4.0
  - @serwist/background-sync@8.4.0
  - @serwist/expiration@8.4.0
  - @serwist/precaching@8.4.0
  - @serwist/routing@8.4.0
  - @serwist/core@8.4.0

## 8.3.0

### Patch Changes

- Updated dependencies [[`bd75087`](https://github.com/serwist/serwist/commit/bd7508722a50bc2191d24a1e6e55a835060ba350)]:
  - @serwist/core@8.3.0
  - @serwist/background-sync@8.3.0
  - @serwist/broadcast-update@8.3.0
  - @serwist/cacheable-response@8.3.0
  - @serwist/expiration@8.3.0
  - @serwist/google-analytics@8.3.0
  - @serwist/precaching@8.3.0
  - @serwist/routing@8.3.0

## 8.2.0

### Patch Changes

- Updated dependencies []:
  - @serwist/background-sync@8.2.0
  - @serwist/broadcast-update@8.2.0
  - @serwist/cacheable-response@8.2.0
  - @serwist/core@8.2.0
  - @serwist/expiration@8.2.0
  - @serwist/google-analytics@8.2.0
  - @serwist/precaching@8.2.0
  - @serwist/routing@8.2.0

## 8.1.1

### Patch Changes

- Updated dependencies []:
  - @serwist/background-sync@8.1.1
  - @serwist/broadcast-update@8.1.1
  - @serwist/cacheable-response@8.1.1
  - @serwist/core@8.1.1
  - @serwist/expiration@8.1.1
  - @serwist/google-analytics@8.1.1
  - @serwist/precaching@8.1.1
  - @serwist/routing@8.1.1

## 8.1.0

### Patch Changes

- Updated dependencies []:
  - @serwist/background-sync@8.1.0
  - @serwist/broadcast-update@8.1.0
  - @serwist/cacheable-response@8.1.0
  - @serwist/core@8.1.0
  - @serwist/expiration@8.1.0
  - @serwist/google-analytics@8.1.0
  - @serwist/precaching@8.1.0
  - @serwist/routing@8.1.0

## 8.0.5

### Patch Changes

- Updated dependencies []:
  - @serwist/background-sync@8.0.5
  - @serwist/broadcast-update@8.0.5
  - @serwist/cacheable-response@8.0.5
  - @serwist/core@8.0.5
  - @serwist/expiration@8.0.5
  - @serwist/google-analytics@8.0.5
  - @serwist/precaching@8.0.5
  - @serwist/routing@8.0.5

## 8.0.4

### Patch Changes

- [#10](https://github.com/serwist/serwist/pull/10) [`52edfe2`](https://github.com/serwist/serwist/commit/52edfe2f9e4ff2007747dd038023dbc94af52698) Thanks [@DuCanhGH](https://github.com/DuCanhGH)! - fix(node-16-cjs): added type support for NodeNext with CommonJS

  - The "fix" is really simple - we copy `.d.ts` to `.old.d.cts` 💀
  - This also fixes the issue where using `@serwist/build`, `@serwist/webpack-plugin`, and their dependents with CommonJS crashes due to us using `pretty-bytes`, which is an ESM package.

- Updated dependencies [[`52edfe2`](https://github.com/serwist/serwist/commit/52edfe2f9e4ff2007747dd038023dbc94af52698)]:
  - @serwist/cacheable-response@8.0.4
  - @serwist/broadcast-update@8.0.4
  - @serwist/google-analytics@8.0.4
  - @serwist/background-sync@8.0.4
  - @serwist/expiration@8.0.4
  - @serwist/precaching@8.0.4
  - @serwist/routing@8.0.4
  - @serwist/core@8.0.4

## 8.0.3

### Patch Changes

- [`22bc8a8`](https://github.com/serwist/serwist/commit/22bc8a86e14873d8fc335c3ea4db11f46e91aa07) Thanks [@DuCanhGH](https://github.com/DuCanhGH)! - fix(serwist/build): removed fsevents

  - Seems that it only supports Darwin, which means that other OSes' users are not be able to install the package (not sure why this doesn't happen to most people, including me). Not that we actually use it anyway.

- Updated dependencies []:
  - @serwist/background-sync@8.0.3
  - @serwist/broadcast-update@8.0.3
  - @serwist/cacheable-response@8.0.3
  - @serwist/core@8.0.3
  - @serwist/expiration@8.0.3
  - @serwist/google-analytics@8.0.3
  - @serwist/precaching@8.0.3
  - @serwist/routing@8.0.3

## 8.0.2

### Patch Changes

- Updated dependencies []:
  - @serwist/background-sync@8.0.2
  - @serwist/broadcast-update@8.0.2
  - @serwist/cacheable-response@8.0.2
  - @serwist/core@8.0.2
  - @serwist/expiration@8.0.2
  - @serwist/google-analytics@8.0.2
  - @serwist/precaching@8.0.2
  - @serwist/routing@8.0.2

## 8.0.1

### Patch Changes

- [`15fb388`](https://github.com/serwist/serwist/commit/15fb38839a5b3b06bdaa39994fba29b56d05b301) Thanks [@DuCanhGH](https://github.com/DuCanhGH)! - fix(publish): removed declarations map

- Updated dependencies [[`15fb388`](https://github.com/serwist/serwist/commit/15fb38839a5b3b06bdaa39994fba29b56d05b301)]:
  - @serwist/background-sync@8.0.1
  - @serwist/broadcast-update@8.0.1
  - @serwist/cacheable-response@8.0.1
  - @serwist/core@8.0.1
  - @serwist/expiration@8.0.1
  - @serwist/google-analytics@8.0.1
  - @serwist/precaching@8.0.1
  - @serwist/routing@8.0.1

## 8.0.0

### Major Changes

- [`e0313f0`](https://github.com/serwist/serwist/commit/e0313f02f661a07ccbe9edc64e44e1af6136c73e) Thanks [@DuCanhGH](https://github.com/DuCanhGH)! - chore: initial release

  - Reimagined `@serwist/next`.
    - Removed various options.
      - Removed `aggressiveFrontEndNavCaching` to reassess its usefulness.
      - Removed `browserslist`. Use `swcEnvTargets` instead (TODO: add this option).
      - Custom workers have been removed. You should use `swSrc`.
      - Removed `extendDefaultRuntimeCaching`. Use the spread syntax instead (use `import { defaultCache } from "@serwist/next/browser"` to import the default runtimeCaching array).
      - Temporarily removed `fallbacks` to investigate module-friendly alternatives.
      - Removed `swcMinify`.
      - Removed `watchWorkersInDev`.
      - Removed `cacheStartUrl`, `dynamicStartUrl`, and `dynamicStartUrl`. These shall be re-added only when their use cases are made more clear to me.
    - Merged `workboxOptions` with the plugin's options.
    - Removed `swc-loader`, `terser-minify`, `webpack-builders`,... (we now leverage `ChildCompilationPlugin` to compile workers - this change will be backported to `@ducanh2912/next-pwa@10`)
    - Removed the ability to use GenerateSW. `@serwist/sw.installSerwist` is provided as a replacement.
    - `swSrc` is now a required property.
    - Moved minimum support Next.js version from `11.0.0` to `14.0.0`.
  - Removed GenerateSW (replaced by `@serwist/sw.installSerwist`).
    - See `examples/next-basic/app/sw.ts` to see how `installSerwist` should be used.
  - Repurposed `@serwist/sw`.
    - The old package might be reintroduced if there's demand.
  - **Note:** This is just the initial release, and there is still a lot of ground to cover (a lot of legacy code to be removed, a lot of features to be reintroduced,...). Here's to a bright future for the project :\_)

### Patch Changes

- Updated dependencies [[`e0313f0`](https://github.com/serwist/serwist/commit/e0313f02f661a07ccbe9edc64e44e1af6136c73e)]:
  - @serwist/cacheable-response@8.0.0
  - @serwist/broadcast-update@8.0.0
  - @serwist/google-analytics@8.0.0
  - @serwist/background-sync@8.0.0
  - @serwist/expiration@8.0.0
  - @serwist/precaching@8.0.0
  - @serwist/routing@8.0.0
  - @serwist/core@8.0.0
