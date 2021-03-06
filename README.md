# Clover Builder (Automated Clover Builds)

[![Build Status](https://www.bitrise.io/app/d99a8cc679de9944/status.svg?token=4iYU6RsLSXBRMno3j3GnJg&branch=master)](https://www.bitrise.io/app/d99a8cc679de9944)

```text
       (       )            (                 (   (   (         (
   (   )\ ) ( /(            )\ )     (        )\ ))\ ))\ )      )\ )
   )\ (()/( )\())(   (  (  (()/(   ( )\    ( (()/(()/(()/(  (  (()/(
 (((_) /(_)|(_)\ )\  )\ )\  /(_))  )((_)   )\ /(_))(_))(_)) )\  /(_))
 )\___(_))   ((_|(_)((_|(_)(_))   ((_)_ _ ((_|_))(_))(_))_ ((_)(_))
((/ __| |   / _ \ \ / /| __| _ \   | _ ) | | |_ _| |  |   \| __| _ \
 | (__| |__| (_) \ V / | _||   /   | _ \ |_| || || |__| |) | _||   /
  \___|____|\___/ \_/  |___|_|_\   |___/\___/|___|____|___/|___|_|_\

                    _          ____  _   _
                   | |_ _ _   |    \|_|_| |___
                   | . | | |  |  |  | | . |_ -|
                   |___|_  |  |____/|_|___|___|
                       |___|
```

A project that provides automated builds for every [Clover](https://clover-wiki.zetam.org) revision.

Note that the following additional drivers are included with each build:

- [AptioFixPkg](https://github.com/vit9696/AptioFixPkg) (includes `AptioInputFix.efi` and `AptioMemoryFix.efi`)
- [ApfsSupportPkg](https://github.com/acidanthera/ApfsSupportPkg) (includes `ApfsDriverLoader.efi`)
- [Misc](https://github.com/Micky1979/Build_Clover/tree/work/Files) (includes `HFSPlus.efi`, `NTFS.efi` and `apfs.efi`)

**DISCLAIMER:** These builds are automated and largely untested, so use them at your own discretion.

## Releases

See the [Releases](https://github.com/Dids/clover-builder/releases) tab.

## License

See [LICENSE.md](LICENSE.md).

A big thank you to [Micky1979](https://github.com/Micky1979) for creating [Build_Clover](https://github.com/Micky1979/Build_Clover) (which this project as initially based around on), as well as everyone else involved (Clover developers and contributors included!).
