# jbang-catalog

JBang catalog for [beehive-lab](https://github.com/beehive-lab) projects.

## Usage

```bash
# Install JBang (if not already installed)
curl -Ls https://sh.jbang.dev | bash -s - app setup

# Run GPULlama3.java CLI
jbang gpullama3@beehive-lab -m model.gguf -p "Tell me a joke"

# Or install it as a command
jbang app install gpullama3@beehive-lab
gpullama3 -m model.gguf -p "Hello!"
```

## Available Aliases

| Alias | Description |
|-------|-------------|
| `gpullama3` | GPU-accelerated LLM inference for Java, powered by TornadoVM |

## Requirements

- Java 21+
- TornadoVM (for GPU acceleration)

## Links

- [GPULlama3.java](https://github.com/beehive-lab/GPULlama3.java)
- [TornadoVM](https://github.com/beehive-lab/TornadoVM)
- [JBang](https://www.jbang.dev/)
