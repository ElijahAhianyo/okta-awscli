# Oktaawscli Util

[_Documentation generated by Documatic_](https://www.documatic.com)

<!---Documatic-section-Codebase Structure-start--->
## Codebase Structure

<!---Documatic-block-system_architecture-start--->
```mermaid
None
```
<!---Documatic-block-system_architecture-end--->

# #
<!---Documatic-section-Codebase Structure-end--->

<!---Documatic-section-oktaawscli.util.input-start--->
## [oktaawscli.util.input](4-oktaawscli_util.md#oktaawscli.util.input)

<!---Documatic-section-input-start--->
<!---Documatic-block-oktaawscli.util.input-start--->
<details>
	<summary><code>oktaawscli.util.input</code> code snippet</summary>

```python
def input(prompt=None):
    if not prompt:
        return _input()
    print(prompt.rstrip('\n'), end='', file=sys.stderr, flush=True)
    return _input()
```
</details>
<!---Documatic-block-oktaawscli.util.input-end--->
<!---Documatic-section-input-end--->

# #
<!---Documatic-section-oktaawscli.util.input-end--->

[_Documentation generated by Documatic_](https://www.documatic.com)