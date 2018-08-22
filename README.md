<img
  src="https://raw.githubusercontent.com/Caleb-Shepard/vscode-poly-header/master/poly.png" 
  width=128>

# Poly Header for VSCode

This extension is a fork of kube's 42header and provides Poly header integration within VS Code.
[kube's repository](https://github.com/kube-Shepard/vscode-poly-header/master)

```bash
/* ************************************************************************** */
/*                                                                            */
/*                                                            |\              */
/*   main.c                                             ------| \----         */
/*                                                      |    \`  \  |  p      */
/*   By: cshepard6055 <cshepard6055@floridapoly.edu>    |  \`-\   \ |  o      */
/*                                                      |---\  \   `|  l      */
/*   Created: 2018/08/22 13:08:31 by cshepard6055       | ` .\  \   |  y      */
/*   Updated: 2018/08/22 13:08:34 by cshepard6055       -------------         */
/*                                                                            */
/* ************************************************************************** */
```

## Install

Launch Quick Open with <kbd>⌘</kbd>+<kbd>P</kbd> and enter
```
ext install poly-header
```

## Usage

### Insert a header
 - **macOS** : <kbd>⌘</kbd> + <kbd>⌥</kbd> + <kbd>H</kbd>
 - **Linux** / **Windows** : <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>H</kbd>.

Header is automatically updated on save.


## Configuration

Default values for **username** and **email** are imported from environment variables.

To override these values, specify these properties in *User Settings* :

```ts
{
  "42header.username": string,
  "42header.email": string
}
```


## Issues

To report a bug or ask for a feature, please open a [Github issue](https://github.com/Caleb-Shepard/vscode-poly-header/issues).


## License

MIT
