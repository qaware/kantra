## Output


#### Default rules:

- the analyze command runs against a set of packaged rules [here](https://github.com/konveyor/rulesets/)
- `--label-selector` and/or `--target` can filter these rules
- `--rules` can be provided to run analyze on rules outside of this set

#### `--rules` + `--target`

- In kantra, if a rule is given as well as a target, but the given rule **does not**
have the target label, the given rule will not match. 
    - You must add the target label to the custom rule (if applicable) in
    order to run this rule.
