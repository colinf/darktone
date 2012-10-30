
# darktone

Darktone theme bundling all individual component darktone themes for convenience of installation.

Currently incorporates the following individual component themes:

* [darktone/tip](https://github.com/colinf/darktone-tip)
* [darktone/popover](https://github.com/colinf/darktone-popover)
* [darktone/calendar](https://github.com/colinf/darktone-calendar)

If you are only using a single component, it is better to use the individual darktone theme file instead of this bundle.

## Installation

You can quickly install the component into your project using the following command from the root.
```
$ component install colinf/darktone
```
But the best way to use it is to amend your component.json file to add the theme as a dependency. You can then use the `component build` command to install the required components.

Below is an example extract from a component.json which uses the darktone theme bundle.

```json
"dependencies": {
  "colinf/datepicker": "*",
  "colinf/darktone": "*"
}
```
# License

  MIT (see the file License.txt included in this distribution for further details)
