<h1 align="center">
  💻  PLS-CLI
</h1>
<p align="center">
    <a href="https://github.com/guedesfelipe/pls-cli/actions/workflows/ci.yml" target="_blank">
        <img src="https://github.com/guedesfelipe/pls-cli/actions/workflows/ci.yml/badge.svg?branch=main" />
    </a>
    <a href="https://github.com/guedesfelipe/pls-cli/actions/workflows/security.yml" target="_blank">
        <img src="https://github.com/guedesfelipe/pls-cli/actions/workflows/security.yml/badge.svg?branch=main" />
    </a>
    <a href="https://codecov.io/gh/guedesfelipe/pls-cli" > 
      <img src="https://codecov.io/gh/guedesfelipe/pls-cli/branch/main/graph/badge.svg"/> 
    </a>
    <a href="https://pypi.org/project/pls-cli/" target="_blank">
      <img src="https://img.shields.io/pypi/v/pls-cli?label=pypi%20package" />
    </a>
    <a href="" target="_blank">
      <img src="https://img.shields.io/pypi/pyversions/pls-cli.svg?color=green&logo=python&logoColor=yellow" />
    </a>
    <img src="https://img.shields.io/badge/platforms-windows%7C%20linux%7C%20macos-lightgrey" />
</p>

<p align="center">
  <em>If you are like me, and your terminal is your home, this CLI will make your life better, I hope 😄</em>
  <br>
  <br>
  <img src="https://user-images.githubusercontent.com/25853920/175831710-20fa013d-5b83-4fe0-baf9-f035345c9192.gif" />
</p>

## 🛠 Installation

```sh
pip install pls-cli
```

!!! tip "Upgrade Version"

    ```sh
    pip install pls-cli --upgrade
    ```

## ⚙️ Configuration

To run **`pls-cli`** everytime you open your shell's:


=== "Bash"

    ```sh
    echo 'pls' >> ~/.bashrc
    ```

=== "Zsh"

    ```sh
    echo 'pls' >> ~/.zshrc
    ```

=== "Fish"

    ```sh
    echo 'pls' >> ~/.config/fish/config.fish
    ```

=== "Ion"

    ```sh
    echo 'pls' >> ~/.config/ion/initrc
    ```

=== "Tcsh"

    ```sh
    echo 'pls' >> ~/.tcshrc
    ```

=== "Xonsh"

    ```sh
    echo 'pls' >> ~/.xonshrc
    ```

=== "Powershell"

    Add the following to the end of `Microsoft.PowerShell_profile.ps1`. You can check the location of this file by querying the `$PROFILE` variable in PowerShell. Typically the path is `~\Documents\PowerShell\Microsoft.PowerShell_profile.ps1` or `~/.config/powershell/Microsoft.PowerShell_profile.ps1` on -Nix.
     
    ```txt
    pls
    ```


## ⌨️ Commands

```sh
pls --help
```

```
  add           Add a Task (Add task name inside quotes)
  clean         Clean up tasks marked as done
  clear         Clear all tasks
  count-done    Count done tasks
  count-undone  Count undone tasks
  delete        Delete a Task
  done          Mark a task as done
  move          Change task order
  setup         Reset all data and run setup
  showtasks     Show all Tasks
  undone        Mark a task as undone
  version       Show version
```


## 🎨 Color Configuration

You can configure all colors with envs!!

=== "Linux, macOS, Windows Bash"

    ```sh
    export PLS_ERROR_LINE_STYLE="#e56767"
    ```

=== "Windows PowerShell"

    ```sh
    $Env:PLS_ERROR_LINE_STYLE = "#e56767"
    ```


All envs:
```sh
export PLS_ERROR_LINE_STYLE="#e56767"
export PLS_ERROR_TEXT_STYLE="#ff0000 bold"

export PLS_WARNING_LINE_STYLE="#FFBF00"
export PLS_WARNING_TEXT_STYLE="#FFBF00 bold"

export PLS_UPDATE_LINE_STYLE="#61E294"
export PLS_UPDATE_TEXT_STYLE="#61E294 bold"

export PLS_INSERT_DELETE_LINE_STYLE="#bb93f2"

export PLS_INSERT_DELETE_TEXT_STYLE="#a0a0a0"

export PLS_MSG_PENDING_STYLE="#61E294"
export PLS_TABLE_HEADER_STYLE="#844191"
export PLS_TABLE_HEADER_STYLE="#d77dd8"
export PLS_TASK_DONE_STYLE="#a0a0a0"
export PLS_TASK_PENDING_STYLE="#bb93f2"
export PLS_HEADER_GREETINGS_STYLE="#FFBF00"
export PLS_QUOTE_STYLE="#a0a0a0"
export PLS_AUTHOR_STYLE="#a0a0a0"
```


???+ tip "You can specify the background color like this:"


    ```sh
    export PLS_QUOTE_STYLE="#a0a0a0 on blue"
    ```

If you create some theme, share with us <a href="https://github.com/guedesfelipe/pls-cli/discussions/1#discussion-4174647" target="_blank">here</a> :heart:.

## 💄 Formatting a task

???+ info "You can format your tasks with:"


    ```sh
    pls add "[b]Bold[/], [i]Italic[/], [s]Strikethrough[/], [d]Dim[/], [r]Reverse[/], [red]Color Red[/], [#FFBF00 on green]Color exa with background[/], :star:, ✨"
    ```

    <img src="https://user-images.githubusercontent.com/25853920/175835339-8059bc7e-0538-4e2d-aed8-80487d7b2478.png" />


## 🚧 TMUX integration

Using `pls count-done` and `pls count-undone`.

---

<p align="center">
  <a href="https://ko-fi.com/guedesfelipe" target="_blank">
    <img src="https://user-images.githubusercontent.com/25853920/175832199-6c75d866-31b8-4209-bd1a-db116a6dd032.png" width=300 />
  </a>
</p>
