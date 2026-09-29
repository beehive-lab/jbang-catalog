# jbang-catalog

JBang catalog for [beehive-lab](https://github.com/beehive-lab) projects.

## Usage

```bash
# Install JBang (if not already installed)
curl -Ls https://sh.jbang.dev | bash -s - app setup

# Run the jitllm CLI
jbang jitllm@beehive-lab -m model.gguf -p "Tell me a joke"

# Or install it as a command
jbang app install jitllm@beehive-lab
jitllm -m model.gguf -p "Hello!"
```

## Available Aliases

| Alias | Description |
|-------|-------------|
| `jitllm` | GPU-accelerated LLM inference for Java, powered by TornadoVM |
| `gpullama3` | Former name of `jitllm`; runs the same script |

## Requirements

- Java 22+
- A TornadoVM SDK built for that JDK, with `TORNADOVM_HOME` pointing at it

## Links

- [jitllm](https://github.com/beehive-lab/jitllm)
- [TornadoVM](https://github.com/beehive-lab/TornadoVM)
- [JBang](https://www.jbang.dev/)
