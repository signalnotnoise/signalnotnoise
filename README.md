I'm a Technical Lead at Recursive Labs and an Associate Course Director at Full Sail University. I build developer tools, multi-agent AI systems, and live products, then measure whether they actually run. I also run Outward Labs.

### What I'm building

Live products:

- [Collab](https://collab.voizel.com): A realtime collaboration app (Vue and WebRTC).
- [Structure Lab](https://labs.voizel.com): A work-in-progress app for learning data structures.

Open source:

- [ui-framework](https://github.com/signalnotnoise/ui-framework): A SwiftUI-inspired C# UI kit whose first backend renders native WPF controls, with no XAML. On NuGet as [SignalNotNoise.UI](https://www.nuget.org/packages/SignalNotNoise.UI) and [SignalNotNoise.UI.Wpf](https://www.nuget.org/packages/SignalNotNoise.UI.Wpf), about 800 downloads each (NuGet, Nov 2026).
- [muse-chief-relay](https://github.com/signalnotnoise/muse-chief-relay): A multi-vendor agent room where Fuse (Meta), chief (xAI), and I, the human, hand each other tasks, results, and opinions.
- [apple-mlx-foundations](https://github.com/signalnotnoise/apple-mlx-foundations): MLX-native Shap-E and TripoSR runtimes for on-device 3D generation on macOS, iOS, and visionOS.
- [shap-e-mlx-swift](https://github.com/signalnotnoise/shap-e-mlx-swift): A Swift package (v0.1.0) that runs the Shap-E text-to-3D and image-to-3D pipeline on Apple platforms with MLX.
- [triposr-mlx-swift](https://github.com/signalnotnoise/triposr-mlx-swift): A Swift package (v0.1.0) that runs an RGB image through an MLX Swift port of TripoSR and returns triplanes plus density and color, with no mesh extraction.
- [mlx-3d-runtime-swift](https://github.com/signalnotnoise/mlx-3d-runtime-swift): A Swift package (v0.1.0) for text-to-3D and image-to-3D on Apple Silicon. It is an integration layer over [shap-e-mlx-swift](https://github.com/signalnotnoise/shap-e-mlx-swift) and [triposr-mlx-swift](https://github.com/signalnotnoise/triposr-mlx-swift), returns a mesh, and can write OBJ+MTL, PLY, or USDZ (USDZ from an app host only).
- [newtron](https://github.com/n0obscertified/newtron): A desktop application framework combining Electron, Vue, and Deno.

### Models on Hugging Face

Public conversions and ports of upstream 3D models for the MLX runtimes in [apple-mlx-foundations](https://github.com/signalnotnoise/apple-mlx-foundations) and the Swift packages above.

- [TripoSR MLX](https://huggingface.co/signalNotNoise/triposr-mlx): A format and layout conversion of Stability AI's [TripoSR](https://huggingface.co/stabilityai/TripoSR) image-to-3D weights for the MLX Swift runtime, with no training or fine-tuning.
- [Shap-E MLX](https://huggingface.co/signalNotNoise/shap-e-mlx): An independent port of OpenAI's [Shap-E](https://github.com/openai/shap-e) and CLIP ViT-L/14 weights for custom Python MLX and Swift runtimes on Apple Silicon, for text-to-3D and image-to-3D (v0.1.0 release candidate, not affiliated with OpenAI or Apple).

### Stack

C#, Swift, TypeScript, Vue, Python, Rust, .NET, WPF, Electron, Deno, WebRTC, MLX, and visionOS.

[X](https://x.com/signaln0tn0ise) · [LinkedIn](https://www.linkedin.com/in/signalnotnoise) · [Hugging Face](https://huggingface.co/signalNotNoise)
