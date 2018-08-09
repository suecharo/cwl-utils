Requires Python 3.6.x or Python 3.7

``` bash
git clone https://github.com/common-workflow-language/cwl-utils.git
virtualenv -p python3.6 venv3.6
source venv3.6/bin/activate
pip install cwl-utils/docker_cache_pull/requirements.txt
python docker_cache_pull/docker-extract.py path_to_my_workflow.cwl
```
