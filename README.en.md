# bebasit

bebasit is a derivative repository of bebasid which contains applications for bypassing deep packet inspection (DPI) measures.

<a href="README.md">Indonesia</a> | <b>English</b>

## List of Applications

Here is a list of applications which was already tested in regards to it's DPI bypassing capability.

### Windows

- GoodbyeDPI.
- PowerTunnel (JRE).

### Linux

- Green Tunnel (NodeJS + NPM).
- PowerTunnel (JRE).
- Zapret (currently it is still under testing phase as zapret does not include DoH within tpws).

### macOS

- Green Tunnel (NodeJS + NPM).
- PowerTunnel (JRE).

## Notes

### Windows

- Not all version of Windows will work, for example Windows 7 without any update has problem, it needs KBxxxxxx.

### Linux and macOS

- Green Tunnel usability depends on luck (it does not mean that Green Tunnel cannot bypass DPI).

### Addendum

- Version of applications inside this repository does not use auto update scheme to latest version because a new feature of application might not be useful.

### Why bebasid and bebasit are separate

- Easing control for application suitability.
- If applications such as GoodbyeDPI, Green Tunnel, PowerTunnel, and Zapret are put into the bebasid repository, it would consume more data. Often, people use the `git clone` command when downloading bebasid and it caused Mac version of the app being downloaded as well in Windows.
- New project.
- To make bebasid look more formal.

## bebasit Dependencies

- [GoodbyeDPI](https://github.com/ValdikSS/GoodbyeDPI)
- [Green Tunnel](https://github.com/SadeghHayeri/GreenTunnel/)
- [PowerTunnel](https://github.com/krlvm/PowerTunnel)
- [Zapret](https://github.com/bol-van/zapret)

## License

bebasit is licensed under [MIT License](https://github.com/bebasid/bebasit/blob/master/LICENSE).

---

# Terms and Conditions

By using this service, you are deemed to have read, understood, and agreed to all the rules that we have made and you accept all the consequences that will arise. For more about the rules, you can see them on [this page](https://github.com/bebasid/bebasit/blob/master/dev/readme/RULES.md).
