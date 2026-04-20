# Slim Linter

Slim Linter is another take on the universal linter. Whereas [Super Linter](https://github.com/super-linter/super-linter) or [Mega Linter](https://github.com/oxsecurity/megalinter) are monolithic applications that embed all linter tools in a single Docker image, Slim Linter is a simple driver application that wraps thin plugins around individual Docker images, one per supported linter. This approach promises a smaller main image, smaller downloads upon version upgrades and reliance on the OS to run multiple linters in parallel.
