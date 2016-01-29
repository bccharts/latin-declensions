## Latin declensions chart

Uses [PlotDevice](http://plotdevice.io).


### Installation

- Download [PyYAML](http://pyyaml.org/wiki/PyYAML) (the zipfile is fine).
- Unpack it.
- Copy the `yaml` directory (inside of `lib`) into `~/Library/Application Support/PlotDevice` or the same directory as these files (per [the manual](http://plotdevice.io/tut/Libraries)).


### Configuration

To modify the order of the cases, just change the headings setting in `data.yaml`. To add a case (such as vocative), do this:

- Add it to the headings setting
- Add it to the declension data (same format as the others)
- Tweak spacing as necessary

To switch to the alternate version in this repo, edit line 4 of `latin-declensions.pv` to point to `data-vocative.yaml` instead of `data.yaml`, then rerun the script in PlotDevice.
