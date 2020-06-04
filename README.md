# <p align="center">Gaffeine.Data.XmlSerializers</p>

<p align="center">
  <a href="https://admin.gear.mycelium.com/gateways/3554/orders/new"><img src="https://img.shields.io/badge/donate-bitcoin-f7941a?logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCI%2BPHBhdGggZD0iTTIzLjYzOCAxNC45MDRjLTEuNjAyIDYuNDMtOC4xMTMgMTAuMzQtMTQuNTQyIDguNzM2QzIuNjcgMjIuMDUtMS4yNDQgMTUuNTI1LjM2MiA5LjEwNSAxLjk2MiAyLjY3IDguNDc1LTEuMjQzIDE0LjkuMzU4YTEyIDEyIDAgMCAxIDguNzM4IDE0LjU0OHYtLjAwMnptLTYuMzUtNC42MTNjLjI0LTEuNi0uOTc0LTIuNDUtMi42NC0zLjAzbC41NC0yLjE1My0xLjMxNS0uMzMtLjUyNSAyLjEwN2MtLjM0NS0uMDg3LS43MDUtLjE2Ny0xLjA2NC0uMjVsLjUyNi0yLjEyNy0xLjMyLS4zMy0uNTQgMi4xNjUtLjg0LS4yLTEuODE1LS40NS0uMzUgMS40MDcuOTU1LjIzNmMuNTM1LjEzNi42My40ODYuNjE1Ljc2NmwtMS40NzcgNS45MmMtLjA3NS4xNjYtLjI0LjQwNi0uNjE0LjMxNC4wMTUuMDItLjk2LS4yNC0uOTYtLjI0bC0uNjYgMS41IDEuNy40MjYuOTMuMjQyLS41NCAyLjIgMS4zMi4zMjcuNTQtMi4xN2MuMzYuMS43MDUuMiAxLjA1LjI3M2wtLjUgMi4xNTQgMS4zMi4zMy41NDUtMi4yYzIuMjQuNDI3IDMuOTMuMjU3IDQuNjQtMS43NzQuNTctMS42MzctLjAzLTIuNTgtMS4yMTctMy4xOTYuODU0LS4xOTMgMS41LS43NiAxLjY4LTEuOTNoLjAxem0tMyA0LjIyYy0uNDA0IDEuNjQtMy4xNTcuNzUtNC4wNS41M2wuNzItMi45Yy44OTYuMjMgMy43NTcuNjcgMy4zMyAyLjM3em0uNC00LjI0Yy0uMzcgMS41LTIuNjYyLjczNS0zLjQwNS41NWwuNjU0LTIuNjRjLjc0NC4xOCAzLjEzNy41MjQgMi43NSAyLjA4NHYuMDA2eiIgZmlsbD0iI2NjYyIvPjwvc3ZnPg%3D%3D&style=for-the-badge"/></a>
  <img src="https://img.shields.io/github/license/bnsmodpolice/Gaffeine.Data.XmlSerializers?style=for-the-badge"/>
</p>

<p align="center">
  Personal project I decided to (partially) release to the public.
</p>

## Features
You can check out the [**projects**](https://github.com/bnsmodpolice/Gaffeine.Data.XmlSerializers/projects)
page for an overview of planned and already implemented features.

## Building
1. NC Launcher 2 must be installed.
2. With each new version of NC Launcher 2, [`assemblyinfo.cs`][0.0] must be
   updated to match the MVID of `Gaffeine.Data.dll`, or nothing will work. You
   can find this value with [dnSpy][0.1].
3. If you update the `MonoMod.Utils.dll` dependency, you need to modify it so
   that its `System.Runtime.CompilerServices.IgnoresAccessChecksToAttribute`
   type is `internal` instead of `public`. This can be done easily with [dnSpy][0.1].

[0.0]: https://github.com/bnsmodpolice/Gaffeine.Data.XmlSerializers/blob/master/src/Gaffeine.Data.XmlSerializers/Properties/assemblyinfo.cs#L12
[0.1]: https://github.com/0xd4d/dnSpy

## Acknowledgements
- [MonoMod/**MonoMod**][1.0] (MIT license)

[1.0]: https://github.com/MonoMod/MonoMod
