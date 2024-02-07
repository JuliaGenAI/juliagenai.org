@def title = "JuliaGenAI"
@def tags = ["syntax", "code"]

# JuliaGenAI

JuliaGenAI is a [GitHub organization](https://github.com/JuliaGenAI/juliagenai.org) created to promote [Julia](https://julialang.org/) as a tool for generative artificial intelligence applications, development, and research. The organization is not intended to usurp robust tools like [llama.cpp](https://github.com/ggerganov/llama.cpp), [ggml](https://github.com/ggerganov/ggml), [ollama](https://github.com/ollama/ollama), etc.

Rather, JuliaGenAI is intended to provide a platform for furthering access to these tools in Julia, as well as to motivate the development of new tools and libraries for generative AI.

You can see which language models tend to perform best on Julia code generation [here](https://siml.earth/Julia-LLM-Leaderboard/stable/).

## Google Summer of Code 2024 with JuliaGenAI

JuliaGenAI [is participating](https://julialang.org/jsoc/gsoc/juliagenai/) in Google Summer of Code 2024 and is currently seeking students to work on a variety of projects. Leap into JuliaGenAI's Google Summer of Code: Unleash your potential, learn about practical applications, and make pivotal contributions in the exciting world of generative AI with Julia—a chance to grow, impact, and thrive in an expanding ecosystem.

[Learn more!](https://julialang.org/jsoc/gsoc/juliagenai/)

## Related packages

JuliaGenAI is a new organization, and as such, it is still in the process of developing its first packages. However, we have several packages that represent the type of work we hope to promote. Please see the [Awesome List for GenAI meets Julia Language](https://github.com/svilupp/awesome-generative-ai-meets-julia-language).

### Interfaces to existing tools

- [PromptingTools.jl](https://github.com/svilupp/PromptingTools.jl). Streamline your life using PromptingTools.jl, the Julia package that simplifies interacting with large language models.
- [LLMTextAnalysis.jl](https://github.com/svilupp/LLMTextAnalysis.jl). Effortlessly uncover and label thematic insights in large document collections using the power of Large Language Models and Julia Language.
- [OpenAI.jl](https://github.com/JuliaML/OpenAI.jl). A community-maintained Julia wrapper to the OpenAI API.
- [BytePairEncoding.jl](https://github.com/chengchingwen/BytePairEncoding.jl). Pure Julia implementation of Byte Pair Encoding (BPE) algorithm. It's used by Transformers.jl to tokenize text.
- [Llama.jl](https://github.com/marcom/Llama.jl/). Julia interface to llama.cpp, a C/C++ library for running language models locally. Supports a wide range of models.
- [AIHelpMe.jl](https://github.com/svilupp/AIHelpMe.jl). AIHelpMe harnesses the power of Julia's extensive documentation and advanced AI models to provide tailored coding guidance. By integrating with PromptingTools.jl, it offers a unique, AI-assisted approach to answering your coding queries directly in Julia's environment.

### Model training and inference

- [Lux.jl](https://github.com/LuxDL/Lux.jl). A modern deep learning framework for Julia, intended for training large models. It is a modern approach to Flux.jl, and will eventually supersede Flux. Lux supports [many predefined layers](https://lux.csail.mit.edu/dev/api/Lux/layers), including attention layers through [Boltz](https://lux.csail.mit.edu/dev/api/Domain_Specific_Modeling/Boltz).
- [Flux.jl](https://github.com/FluxML/Flux.jl). Flux is a machine-learning library for Julia that is flexible and allows the building of complex models. However, at the time of writing, We're not aware of any Large Language Models (LLMs) that have been trained in Flux.
- [Llama2.jl](https://github.com/cafaxo/Llama2.jl). Llama2.jl provides simple code for inference and training of llama2-based language models based on [llama2.c](https://github.com/karpathy/llama2.c). It supports loading quantized weights in GGUF format (`q4_K_S` variant). Training is only experimental at this stage.
- [Transformers.jl](https://github.com/chengchingwen/Transformers.jl). Transformers.jl is a Julia package that provides a high-level API for using pre-trained transformer models. It also allows to download any model from the Hugging Face hub with `@hgf_str` macro string.
- [GraphNeuralNetworks.jl](https://github.com/CarloLucibello/GraphNeuralNetworks.jl). GraphNeuralNetworks.jl is a Julia package for graph neural networks. It is a high-level API for using pre-trained graph neural network models.

## Why Julia?

Julia is a fantastic tool for generative AI, for several reasons.

1. **Expressiveness**. Julia is a high-level language with a powerful syntax that is token-cheap -- that is, you get a lot of "program" per token. It's not unlikely that AI agents will be writing code on their own in a lightly monitored way, and Julia's syntax is well-suited to low-cost AI code generation.
2. **Interactiveness**. Julia is a just-in-time compiled language, which means that it's fast to run, but also fast to develop in. This is important for AI development, where the ability to quickly prototype and test ideas is crucial. It has first-in-class REPL (read-eval-print loop) support, which could potentially be very important for rapid prototype development.
3. **Performance**. Julia is fast. Nuff' said.
4. **Community**. Julia has a fantastic community, and it's growing. This is important for the development of AI tools, as it means that there are more people to help develop and maintain the tools that we need.
5. **Ecosystem**. Julia has a fantastic and growing ecosystem built by a wonderful community of developers.

## How to contribute

We are always looking for new contributors. If you have an idea for a package, or if you would like to contribute to an existing package, please feel free to reach out to us. We are also looking for people to help with documentation, testing, and other non-coding tasks.

Alternatively, you might be interested in participating in the [Google Summer of Code 2024 with JuliaGenAI](https://julialang.org/jsoc/gsoc/juliagenai/).

## Contact

You can reach out to the organizing committee:

- Cameron Pfiffer at [cameron@pfiffer.org](mailto:cameron@pfiffer.org)
- Jan Siml (Slack: @svilup / Zulip: Jan Siml)

You can reach us on the Julia [Slack](https://julialang.org/slack/) & [Zulip](https://julialang.zulipchat.com/) at the `#generative-ai` channel. You can also find us at the [Discord](https://discord.gg/mm2kYjB) server, or the discussion forum at [discourse.julialang.org](https://discourse.julialang.org/).
