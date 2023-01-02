<p align="center">
  <h3 align="center">rofi-ddgr</h3>

  <p align="center">
    A rofi script to run ddgr.
    <br />
    <a href="https://github.com/davatorium/rofi/wiki/User-scripts"><strong> More rofi scripts here</strong></a>
    <br />
    <br />
  </p>
</p>

### :hammer_and_pick: Dependencies

`rofi-ddgr` depends on the following tools:

- [rofi](https://github.com/davatorium/rofi)
- [ddgr](https://github.com/jarun/ddgr)
- [python3.6](https://www.python.org/)

They need to be installed in your system and available in the PATH.

### :package: Installation

Just place `ddgr_search.py` script somewhere in your system PATH.

### :feet: Usage

https://user-images.githubusercontent.com/46817915/125208524-65112d00-e269-11eb-8c2a-b6471e346f89.mp4

Trigger `rofi-ddgr` by running:

```bash
rofi -lines 5 -eh 3 -show ddgrsearch -modi "ddgrsearch:ddgr_search.py"
```

or add a key binding on your window manager to trigger it.

### :copyright: License

Distributed under the MIT License. See `LICENSE` for more information.

[license-url]: https://github.com/gmagno/igl/blob/master/LICENSE

