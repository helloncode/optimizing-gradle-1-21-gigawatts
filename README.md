# Welcome to 1.21 gigawatts of Gradle optimization!

This repository contains materials for the talk "Great Scott! Discover What Really Matters in Optimizing Gradle Builds" by Francesco Bonnì.

## Repository Contents

- 📊 `/presentation`: Slides and additional resources from the talk
- 🏗️ `/project`: A sample project demonstrating Gradle optimization techniques
  - `/android-build-eval`: Submodule containing the Uber project used for demonstrations
- 📈 `/benchmarks`: Benchmark results and scripts

## Getting Started

To clone this repository and its submodules:

```bash
git clone --recursive https://github.com/your-username/gradle-optimization-delorean.git
```

If you've already cloned the repository without the `--recursive` flag:

```bash
git submodule update --init --recursive
```

## Key Topics

1. Gradle 101: Understanding Gradle projects and build lifecycle
2. Build Analysis: Tools for identifying optimization opportunities
3. Build Maximization: Common mistakes and how to correct them
4. Future of Gradle: Upcoming features and optimizations

## Gradle Optimization Techniques Covered

- JVM heap size optimization
- Parallel execution
- Build cache utilization
- Incremental compilation
- Modularization strategies
- Configuration cache

## Additional Resources

- [Gradle Profiler](https://github.com/gradle/gradle-profiler)
- [Gradle Develocity](https://gradle.com/develocity/)

## About the Author

Francesco Bonnì is a Senior Android Engineer at Subito.it with 10 years of android mobile experience and the founder of BeerTechGroup's Community Tech.

## License

This repository contains materials under two different licenses:

### Demo Project

The demo project in the `/project` directory is licensed under the Apache License, Version 2.0. This project is based on work by Uber and retains their original license.

You may obtain a copy of the Apache License at:

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the Apache License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.

### Presentation Materials

The presentation slides and additional resources in the `/presentation` directory are licensed under the Creative Commons Attribution 4.0 International License.

You are free to:
- Share — copy and redistribute the material in any medium or format
- Adapt — remix, transform, and build upon the material for any purpose, even commercially

Under the following terms:
- Attribution — You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.

To view a copy of this license, visit:
https://creativecommons.org/licenses/by/4.0/

## Acknowledgements

The demo project is based on work by Uber. We gratefully acknowledge their contribution to the open-source community.

Remember, when optimizing Gradle builds: "If you put your mind to it, you can accomplish anything!" 🚀⏱️