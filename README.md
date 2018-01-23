# check-crontab
## Description
Checks for crontab lines.

## Usage
```
check-crontab [subcommand] [options]...
```

### check-crontab lines [-u user] [-w num] [-c num]
    Description:
        alert when crontab lines count under threshold.

    Options:
        -u    crontab user select. (default: "")
        -w    warning  threshold   (default: 0)
        -c    critical threthold   (default: 1)

### check-crontab version
    Description:
        show version.

## License
License

Copyright 2017 KAYAC Inc.

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0
Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
