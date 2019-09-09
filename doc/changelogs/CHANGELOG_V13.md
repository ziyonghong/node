# Node.js 13 ChangeLog

<!--lint disable prohibited-strings-->
<!--lint disable maximum-line-length-->

<table>
<tr>
<th>Current</th>
</tr>
<tr>
<td>
<a href="#13.0.0">13.0.0</a><br/>
</td>
</tr>
</table>

* Other Versions
  * [11.x](CHANGELOG_V11.md)
  * [10.x](CHANGELOG_V10.md)
  * [9.x](CHANGELOG_V9.md)
  * [8.x](CHANGELOG_V8.md)
  * [7.x](CHANGELOG_V7.md)
  * [6.x](CHANGELOG_V6.md)
  * [5.x](CHANGELOG_V5.md)
  * [4.x](CHANGELOG_V4.md)
  * [0.12.x](CHANGELOG_V012.md)
  * [0.10.x](CHANGELOG_V010.md)
  * [io.js](CHANGELOG_IOJS.md)
  * [Archive](CHANGELOG_ARCHIVE.md)

<a id="13.0.0"></a>
## 2019-10-22, Version 13.0.0 (Current), @BethGriggs

### Notable Changes

* TBD

### Semver-Major Commits

* [[`5981fb7faa`](https://github.com/nodejs/node/commit/5981fb7faa)] - **(SEMVER-MAJOR)** **assert**: fix line number calculation after V8 upgrade (Michaël Zasso) [#29694](https://github.com/nodejs/node/pull/29694)
* [[`48d1ea5e7f`](https://github.com/nodejs/node/commit/48d1ea5e7f)] - **(SEMVER-MAJOR)** **assert**: special handle identical error names in instance checks (Ruben Bridgewater) [#28263](https://github.com/nodejs/node/pull/28263)
* [[`97c52ca5dc`](https://github.com/nodejs/node/commit/97c52ca5dc)] - **(SEMVER-MAJOR)** **assert**: add more information to AssertionErrors (Ruben Bridgewater) [#28263](https://github.com/nodejs/node/pull/28263)
* [[`5700cd17dd`](https://github.com/nodejs/node/commit/5700cd17dd)] - **(SEMVER-MAJOR)** **assert**: do not repeat .throws() code (Ruben Bridgewater) [#28263](https://github.com/nodejs/node/pull/28263)
* [[`d47b6786c9`](https://github.com/nodejs/node/commit/d47b6786c9)] - **(SEMVER-MAJOR)** **assert**: wrap validation function errors (Ruben Bridgewater) [#28263](https://github.com/nodejs/node/pull/28263)
* [[`0b3242c3ce`](https://github.com/nodejs/node/commit/0b3242c3ce)] - **(SEMVER-MAJOR)** **assert**: fix generatedMessage property (Ruben Bridgewater) [#28263](https://github.com/nodejs/node/pull/28263)
* [[`ace3f16917`](https://github.com/nodejs/node/commit/ace3f16917)] - **(SEMVER-MAJOR)** **assert**: improve class instance errors (Ruben Bridgewater) [#28263](https://github.com/nodejs/node/pull/28263)
* [[`0376b5b7ba`](https://github.com/nodejs/node/commit/0376b5b7ba)] - **(SEMVER-MAJOR)** **benchmark**: use test/common/tmpdir consistently (João Reis) [#28858](https://github.com/nodejs/node/pull/28858)
* [[`4885e50f7e`](https://github.com/nodejs/node/commit/4885e50f7e)] - **(SEMVER-MAJOR)** **build**: make full-icu the default for releases (Richard Lau) [#29887](https://github.com/nodejs/node/pull/29887)
* [[`60a3bd93ce`](https://github.com/nodejs/node/commit/60a3bd93ce)] - **(SEMVER-MAJOR)** **build**: reset embedder string to "-node.0" (Myles Borins) [#29694](https://github.com/nodejs/node/pull/29694)
* [[`9f830f37da`](https://github.com/nodejs/node/commit/9f830f37da)] - **(SEMVER-MAJOR)** **build**: update minimum Xcode version for macOS (Michael Dawson) [#29622](https://github.com/nodejs/node/pull/29622)
* [[`66eaeac1df`](https://github.com/nodejs/node/commit/66eaeac1df)] - **(SEMVER-MAJOR)** **build**: reset embedder string to "-node.0" (Michaël Zasso) [#28016](https://github.com/nodejs/node/pull/28016)
* [[`d05668d688`](https://github.com/nodejs/node/commit/d05668d688)] - **(SEMVER-MAJOR)** **child_process**: runtime deprecate \_channel (cjihrig) [#27949](https://github.com/nodejs/node/pull/27949)
* [[`4f9cd2770a`](https://github.com/nodejs/node/commit/4f9cd2770a)] - **(SEMVER-MAJOR)** **child_process**: simplify spawn argument parsing (cjihrig) [#27854](https://github.com/nodejs/node/pull/27854)
* [[`66043e1812`](https://github.com/nodejs/node/commit/66043e1812)] - **(SEMVER-MAJOR)** **console**: display timeEnd with suitable time unit (Xavier Stouder) [#29251](https://github.com/nodejs/node/pull/29251)
* [[`80f2b67367`](https://github.com/nodejs/node/commit/80f2b67367)] - **(SEMVER-MAJOR)** **deps**: patch V8 to 7.8.279.14 (Myles Borins) [#29694](https://github.com/nodejs/node/pull/29694)
* [[`eeafb263f4`](https://github.com/nodejs/node/commit/eeafb263f4)] - **(SEMVER-MAJOR)** **deps**: patch V8 to 7.8.279.12 (Myles Borins) [#29694](https://github.com/nodejs/node/pull/29694)
* [[`ddfc3b0a76`](https://github.com/nodejs/node/commit/ddfc3b0a76)] - **(SEMVER-MAJOR)** **deps**: patch V8 to 7.8.279.10 (Myles Borins) [#29694](https://github.com/nodejs/node/pull/29694)
* [[`8d05991d10`](https://github.com/nodejs/node/commit/8d05991d10)] - **(SEMVER-MAJOR)** **deps**: update V8's postmortem script (cjihrig) [#29694](https://github.com/nodejs/node/pull/29694)
* [[`858602445b`](https://github.com/nodejs/node/commit/858602445b)] - **(SEMVER-MAJOR)** **deps**: V8: cherry-pick 716875d (Myles Borins) [#29694](https://github.com/nodejs/node/pull/29694)
* [[`f7f6c928c1`](https://github.com/nodejs/node/commit/f7f6c928c1)] - **(SEMVER-MAJOR)** **deps**: update V8 to 7.8.279.9 (Myles Borins) [#29694](https://github.com/nodejs/node/pull/29694)
* [[`84d3243ce9`](https://github.com/nodejs/node/commit/84d3243ce9)] - **(SEMVER-MAJOR)** **deps**: V8: cherry-pick b33af60 (Michaël Zasso) [#28016](https://github.com/nodejs/node/pull/28016)
* [[`2dcc3665ab`](https://github.com/nodejs/node/commit/2dcc3665ab)] - **(SEMVER-MAJOR)** **deps**: update V8 to 7.6.303.28 (Michaël Zasso) [#28016](https://github.com/nodejs/node/pull/28016)
* [[`eef1b5aa0f`](https://github.com/nodejs/node/commit/eef1b5aa0f)] - **(SEMVER-MAJOR)** **doc**: make `AssertionError` a link (Ruben Bridgewater) [#28263](https://github.com/nodejs/node/pull/28263)
* [[`8fd7184959`](https://github.com/nodejs/node/commit/8fd7184959)] - **(SEMVER-MAJOR)** **doc**: update assert.throws() examples (Ruben Bridgewater) [#28263](https://github.com/nodejs/node/pull/28263)
* [[`80d9b1c712`](https://github.com/nodejs/node/commit/80d9b1c712)] - **(SEMVER-MAJOR)** **doc**: wrap long line (cjihrig) [#27951](https://github.com/nodejs/node/pull/27951)
* [[`43a5170858`](https://github.com/nodejs/node/commit/43a5170858)] - **(SEMVER-MAJOR)** **domain**: error handler runs outside of its domain (Julien Gilli) [#26211](https://github.com/nodejs/node/pull/26211)
* [[`7eacb74389`](https://github.com/nodejs/node/commit/7eacb74389)] - **(SEMVER-MAJOR)** **fs**: make FSWatcher.start private (Lucas Holmquist) [#29905](https://github.com/nodejs/node/pull/29905)
* [[`773769df60`](https://github.com/nodejs/node/commit/773769df60)] - **(SEMVER-MAJOR)** **fs**: add runtime deprecate for file stream open() (Robert Nagy) [#29061](https://github.com/nodejs/node/pull/29061)
* [[`5e3b4d6ed9`](https://github.com/nodejs/node/commit/5e3b4d6ed9)] - **(SEMVER-MAJOR)** **fs**: allow int64 offset in fs.write/writeSync/fd.write (Zach Bjornson) [#26572](https://github.com/nodejs/node/pull/26572)
* [[`a3c0014e73`](https://github.com/nodejs/node/commit/a3c0014e73)] - **(SEMVER-MAJOR)** **fs**: use IsSafeJsInt instead of IsNumber for ftruncate (Zach Bjornson) [#26572](https://github.com/nodejs/node/pull/26572)
* [[`0bbda5e5ae`](https://github.com/nodejs/node/commit/0bbda5e5ae)] - **(SEMVER-MAJOR)** **fs**: allow int64 offset in fs.read/readSync/fd.read (Zach Bjornson) [#26572](https://github.com/nodejs/node/pull/26572)
* [[`eadc3850fe`](https://github.com/nodejs/node/commit/eadc3850fe)] - **(SEMVER-MAJOR)** **fs**: close file descriptor of promisified truncate (João Reis) [#28858](https://github.com/nodejs/node/pull/28858)
* [[`5f80df8820`](https://github.com/nodejs/node/commit/5f80df8820)] - **(SEMVER-MAJOR)** **http**: do not emit end after aborted (Robert Nagy) [#27984](https://github.com/nodejs/node/pull/27984)
* [[`e573c39b88`](https://github.com/nodejs/node/commit/e573c39b88)] - **(SEMVER-MAJOR)** **http**: don't emit 'data' after 'error' (Robert Nagy) [#28711](https://github.com/nodejs/node/pull/28711)
* [[`ac59dc42ed`](https://github.com/nodejs/node/commit/ac59dc42ed)] - **(SEMVER-MAJOR)** **http**: remove legacy parser (Anna Henningsen) [#29589](https://github.com/nodejs/node/pull/29589)
* [[`2daf883a18`](https://github.com/nodejs/node/commit/2daf883a18)] - **(SEMVER-MAJOR)** **http**: throw if 'host' agent header is not a string value (Giorgos Ntemiris) [#29568](https://github.com/nodejs/node/pull/29568)
* [[`0daec61b9b`](https://github.com/nodejs/node/commit/0daec61b9b)] - **(SEMVER-MAJOR)** **http**: replace superfluous connection property with getter/setter (Robert Nagy) [#29015](https://github.com/nodejs/node/pull/29015)
* [[`461bf36d70`](https://github.com/nodejs/node/commit/461bf36d70)] - **(SEMVER-MAJOR)** **http**: fix test where aborted should not be emitted (Robert Nagy) [#20077](https://github.com/nodejs/node/pull/20077)
* [[`d5577f0395`](https://github.com/nodejs/node/commit/d5577f0395)] - **(SEMVER-MAJOR)** **http**: remove default 'timeout' listener on upgrade (Luigi Pinca) [#26030](https://github.com/nodejs/node/pull/26030)
* [[`c30ef3cbd2`](https://github.com/nodejs/node/commit/c30ef3cbd2)] - **(SEMVER-MAJOR)** **http, http2**: remove default server timeout (Ali Ijaz Sheikh) [#27558](https://github.com/nodejs/node/pull/27558)
* [[`4e782c9deb`](https://github.com/nodejs/node/commit/4e782c9deb)] - **(SEMVER-MAJOR)** **http2**: remove security revert flags (Anna Henningsen) [#29141](https://github.com/nodejs/node/pull/29141)
* [[`41637a530e`](https://github.com/nodejs/node/commit/41637a530e)] - **(SEMVER-MAJOR)** **http2**: remove callback-based padding (Anna Henningsen) [#29144](https://github.com/nodejs/node/pull/29144)
* [[`91a4cb7175`](https://github.com/nodejs/node/commit/91a4cb7175)] - **(SEMVER-MAJOR)** **lib**: rename validateInteger to validateSafeInteger (Zach Bjornson) [#26572](https://github.com/nodejs/node/pull/26572)
* [[`1432065e9d`](https://github.com/nodejs/node/commit/1432065e9d)] - **(SEMVER-MAJOR)** **lib**: correct error.errno to always be numeric (Joyee Cheung) [#28140](https://github.com/nodejs/node/pull/28140)
* [[`702331be90`](https://github.com/nodejs/node/commit/702331be90)] - **(SEMVER-MAJOR)** **lib**: no need to strip BOM or shebang for scripts (Refael Ackermann) [#27375](https://github.com/nodejs/node/pull/27375)
* [[`e2c0c0c680`](https://github.com/nodejs/node/commit/e2c0c0c680)] - **(SEMVER-MAJOR)** **lib**: rework logic of stripping BOM+Shebang from commonjs (Gus Caplan) [#27768](https://github.com/nodejs/node/pull/27768)
* [[`14701e539c`](https://github.com/nodejs/node/commit/14701e539c)] - **(SEMVER-MAJOR)** **module**: runtime deprecate createRequireFromPath() (cjihrig) [#27951](https://github.com/nodejs/node/pull/27951)
* [[`04633eeeb9`](https://github.com/nodejs/node/commit/04633eeeb9)] - **(SEMVER-MAJOR)** **readline**: error on falsy values for callback (Sam Roberts) [#28109](https://github.com/nodejs/node/pull/28109)
* [[`3eea43af07`](https://github.com/nodejs/node/commit/3eea43af07)] - **(SEMVER-MAJOR)** **repl**: close file descriptor of history file (João Reis) [#28858](https://github.com/nodejs/node/pull/28858)
* [[`458a38c904`](https://github.com/nodejs/node/commit/458a38c904)] - **(SEMVER-MAJOR)** **src**: bring 425 status code name into accordance with RFC 8470 (Sergei Osipov) [#29880](https://github.com/nodejs/node/pull/29880)
* [[`7fcc1f7047`](https://github.com/nodejs/node/commit/7fcc1f7047)] - **(SEMVER-MAJOR)** **src**: update NODE\_MODULE\_VERSION to 79 (Myles Borins) [#29694](https://github.com/nodejs/node/pull/29694)
* [[`4b7be335b9`](https://github.com/nodejs/node/commit/4b7be335b9)] - **(SEMVER-MAJOR)** **src**: update NODE\_MODULE\_VERSION to 78 (Michaël Zasso) [#28918](https://github.com/nodejs/node/pull/28918)
* [[`a0e2c6d284`](https://github.com/nodejs/node/commit/a0e2c6d284)] - **(SEMVER-MAJOR)** **src**: add error codes to errors thrown in C++ (Yaniv Friedensohn) [#27700](https://github.com/nodejs/node/pull/27700)
* [[`94e980c9d3`](https://github.com/nodejs/node/commit/94e980c9d3)] - **(SEMVER-MAJOR)** **src**: use non-deprecated overload of V8::SetFlagsFromString (Michaël Zasso) [#28016](https://github.com/nodejs/node/pull/28016)
* [[`655e0dc01a`](https://github.com/nodejs/node/commit/655e0dc01a)] - **(SEMVER-MAJOR)** **src**: update NODE\_MODULE\_VERSION to 77 (Michaël Zasso) [#28016](https://github.com/nodejs/node/pull/28016)
* [[`e3cd79ef8e`](https://github.com/nodejs/node/commit/e3cd79ef8e)] - **(SEMVER-MAJOR)** **src**: update NODE\_MODULE\_VERSION to 74 (Refael Ackermann) [#27375](https://github.com/nodejs/node/pull/27375)
* [[`eba348b6ae`](https://github.com/nodejs/node/commit/eba348b6ae)] - **(SEMVER-MAJOR)** **src**: make process.env.TZ setter clear tz cache (Ben Noordhuis) [#20026](https://github.com/nodejs/node/pull/20026)
* [[`f2061930c8`](https://github.com/nodejs/node/commit/f2061930c8)] - **(SEMVER-MAJOR)** **src**: enable V8's WASM trap handlers (Gus Caplan) [#27246](https://github.com/nodejs/node/pull/27246)
* [[`f8f6a21580`](https://github.com/nodejs/node/commit/f8f6a21580)] - **(SEMVER-MAJOR)** **stream**: throw unhandled error for readable with autoDestroy (Robert Nagy) [#29806](https://github.com/nodejs/node/pull/29806)
* [[`f663b31cc2`](https://github.com/nodejs/node/commit/f663b31cc2)] - **(SEMVER-MAJOR)** **stream**: always invoke callback before emitting error (Robert Nagy) [#29293](https://github.com/nodejs/node/pull/29293)
* [[`3de5eae6db`](https://github.com/nodejs/node/commit/3de5eae6db)] - **(SEMVER-MAJOR)** **stream**: invoke callback before emitting error always (Robert Nagy) [#29293](https://github.com/nodejs/node/pull/29293)
* [[`aa32e13968`](https://github.com/nodejs/node/commit/aa32e13968)] - **(SEMVER-MAJOR)** **stream**: do not flush destroyed writable (Robert Nagy) [#29028](https://github.com/nodejs/node/pull/29028)
* [[`ba3be578d8`](https://github.com/nodejs/node/commit/ba3be578d8)] - **(SEMVER-MAJOR)** **stream**: don't emit finish on error (Robert Nagy) [#28979](https://github.com/nodejs/node/pull/28979)
* [[`db706da235`](https://github.com/nodejs/node/commit/db706da235)] - **(SEMVER-MAJOR)** **stream**: disallow stream methods on finished stream (Robert Nagy) [#28687](https://github.com/nodejs/node/pull/28687)
* [[`188896ea3e`](https://github.com/nodejs/node/commit/188896ea3e)] - **(SEMVER-MAJOR)** **stream**: do not emit after 'error' (Robert Nagy) [#28708](https://github.com/nodejs/node/pull/28708)
* [[`4a2bd69db9`](https://github.com/nodejs/node/commit/4a2bd69db9)] - **(SEMVER-MAJOR)** **stream**: fix destroy() behavior (Robert Nagy) [#29058](https://github.com/nodejs/node/pull/29058)
* [[`824dc576db`](https://github.com/nodejs/node/commit/824dc576db)] - **(SEMVER-MAJOR)** **stream**: simplify `.pipe()` and `.unpipe()` in Readable (Weijia Wang) [#28583](https://github.com/nodejs/node/pull/28583)
* [[`8ef68e66d0`](https://github.com/nodejs/node/commit/8ef68e66d0)] - **(SEMVER-MAJOR)** **test**: clean tmpdir on process exit (João Reis) [#28858](https://github.com/nodejs/node/pull/28858)
* [[`d3f20a4725`](https://github.com/nodejs/node/commit/d3f20a4725)] - **(SEMVER-MAJOR)** **test**: use unique tmpdirs for each test (João Reis) [#28858](https://github.com/nodejs/node/pull/28858)
* [[`174723354e`](https://github.com/nodejs/node/commit/174723354e)] - **(SEMVER-MAJOR)** **tools**: patch V8 to run on older XCode versions (Ujjwal Sharma) [#29694](https://github.com/nodejs/node/pull/29694)
* [[`1676502318`](https://github.com/nodejs/node/commit/1676502318)] - **(SEMVER-MAJOR)** **tools**: update V8 gypfiles (Michaël Zasso) [#29694](https://github.com/nodejs/node/pull/29694)
* [[`1a25e901b7`](https://github.com/nodejs/node/commit/1a25e901b7)] - **(SEMVER-MAJOR)** **tools**: support full-icu by default (Steven R. Loomis) [#29522](https://github.com/nodejs/node/pull/29522)
* [[`2664dacf7e`](https://github.com/nodejs/node/commit/2664dacf7e)] - **(SEMVER-MAJOR)** **util**: validate formatWithOptions inspectOptions (Ruben Bridgewater) [#29824](https://github.com/nodejs/node/pull/29824)

### Semver-Minor Commits

* TBD

### Semver-Patch Commits

* TBD
