# Install pip and django dependencies

A github action that makes it possible to install pip, and install the dependencies described in the requirements.txt file

## Example of use

```yaml
jobs:
  executar_jobs:
    runs-on: ubuntu-latest
    steps:
      - name: Install pip and packages
        uses: luisgs7/django-action-pip@v1
```
