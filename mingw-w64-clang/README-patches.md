### Patches statuses

Legend:
- :grey_exclamation: - not meant to upstream, for compatibility with GCC only
- :x: - not upstreamed
- :grey_question: - sent but not merged yet
- :arrow_up_small:  - upstreamed
- :arrow_down_small:  - backported

-----
- `"0001-Use-posix-style-path-separators-with-MinGW.patch"` :x::x::x: - this one is really imporant
- `"0002-Fix-GetHostTriple-for-mingw-w64-in-msys.patch"` :x:
- `"0004-llvm-config-look-for-unversioned-shared-lib-on-win32.patch"` :grey_question: - https://reviews.llvm.org/D87521 https://reviews.llvm.org/D89009
- `"0005-add-pthread-as-system-lib-for-mingw.patch"` :grey_exclamation:
- `"0008-enable-emutls-for-mingw.patch"` :grey_exclamation:
- `"0010-mbig-obj-for-all.patch"` :arrow_up_small:
- `"0011-nm-version-option.patch"` :arrow_down_small:
- `"0012-windres.patch"` :arrow_down_small:
- `"0013-Dlltool-use-default-LLVM-target-unless-specified.patch"` :x:
- `"0101-Disable-fPIC-errors.patch"` :x:
- `"0103-Use-posix-style-path-separators-with-MinGW.patch"` :x::x::x: - this one is really imporant
- `"0104-link-pthread-with-mingw.patch"` :grey_exclamation:
- `"0105-Dont-mark-emutls-variables-as-DSO-local.patch"` :arrow_down_small:
- `"0201-Provide-a-SEH-specific-__gcc_personality_seh0.patch"` :arrow_down_small:
- `"0301-fix-including-the-personality-function-for-dwarf.patch"` :arrow_down_small:
- `"0302-ignore-no-undefined-flag.patch"` :arrow_up_small:
- `"0303-LLD-MinGW-Add-fatal-warnings-and-no-fatal-warnings-f.patch"` :arrow_up_small:
- `"0304-ignore-new-bfd-options.patch"` :x:
- `"0305-use-TerminateProcess-instead-of-exit.patch"` :grey_exclamation:
- `"0306-LLD-MinGW-Pass-the-canExitEarly-parameter-through-pr.patch"` :arrow_down_small:
- `"0307-lld-MinGW-Introduce-aliases-for-Bdynamic-and-Bstatic.patch"` :arrow_down_small:
- `"0308-LLD-COFF-Fix-automatic-export-of-symbols-from-LTO-ob.patch"` :arrow_down_small:
- `"0310-backport-2b01a41.patch"` :arrow_down_small:
- `"0311-backport-82de4e0.patch"` :arrow_down_small:
- `"0312-LLD-COFF-Fix-autoexport-from-LTO-objects-with-comdat.patch"` :arrow_down_small:
- `"0401-libcxx-fs.patch"` :arrow_down_small:
- `"0402-make-the-visibility-attributes-consistent-for-__narr.patch"` :arrow_down_small:
- `"0601-libunwind-Install-the-DLL-when-doing-ninja-install.patch"` :arrow_down_small:
- `"0710-backport-05b3716.patch"` :arrow_down_small:
- `"0901-cast-to-make-gcc-happy.patch"` :grey_exclamation: