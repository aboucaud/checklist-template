# Checklist template

Single-page HTML checklist template with a progress bar. Feel free to modify and expand as needed.

The checklist status is stored on your computer as a web cookie. No data is sent to any server.

This template is based on [cookiecutter][cc] and will create a ready-to-push GitLab/GitHub project to host the checklist online for free.

[cc]: https://cookiecutter.readthedocs.io/

## Getting started

### Get `cookiecutter`

```shell
python -m pip install cookiecutter
```

### Generate the project

Run the cookiecutter and follow the instructions

```shell
cookiecutter gh:aboucaud/checklist-template
```

## Adapt the checklist

Modify the content of the `index.html` file to suit your needs. You can add/remove/reorder checklist items as needed.

One item of the checklist is given by the following code snippet

```html
<div class="item">
  <div class="box">
    <input type="checkbox">
  </div>
  <div class="text">
    This is where the text needs to be modified.
  </div>
</div>
```

Copy/paste and adapt as needed.

## Acknowledgements

This project is a direct adaptation of the [DESC pre-meeting-checklist][pmc] originally proposed by [Yao-Yuan Mao][yao].

[pmc]: https://github.com/LSSTDESC/pre-meeting-checklist
[yao]: https://yymao.github.io/

## License

This template is released under the MIT License. See the [LICENSE](LICENSE) file for more details.
