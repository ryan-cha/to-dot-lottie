# ryan-to-dot-lottie

## What's different?

- Removed the check on the path for presence of specific folder name.
- Exit the process (with result `0`) once the job is done.

## Generate binary

```sh
# generate binary
./gradlew distZip

# unzip the distribution file
$ cd lib/build/distribution
$ unzip -d . lib.zip

# run the binary
$ ./bin/lib

➡️ Initializing... (v1.0.3)
Traversing ~/.../lib/build/distributions/lib
✅ Done

# 1. Add the path to the binary to env
# 2. Go to any folder containing the Lottie json files
# 3. Run it!
```

## 📝 License

```
Copyright © 2023 - theapache64

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
