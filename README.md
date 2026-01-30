# sageLLM PyTorch Wheels

Pre-built PyTorch CUDA wheels for faster installation in China.

## 🚀 Quick Start

### Install from GitHub Releases

```bash
# PyTorch 2.5.1 + CUDA 12.1
pip install torch==2.5.1+cu121 torchvision torchaudio \
  --find-links https://github.com/intellistream/sagellm-pytorch-wheels/releases/download/v2.5.1-cu121/ \
  --trusted-host github.com
```

## 📦 Available Releases

| Version | CUDA | Python | Platform | Size | Release |
|---------|------|--------|----------|------|---------|
| 2.5.1 | 12.1 | 3.11 | Linux x86_64 | ~800MB | [Download](https://github.com/intellistream/sagellm-pytorch-wheels/releases/tag/v2.5.1-cu121) |

## 📥 Download Single File

```bash
wget https://github.com/intellistream/sagellm-pytorch-wheels/releases/download/v2.5.1-cu121/torch-2.5.1+cu121-cp311-cp311-linux_x86_64.whl
pip install torch-2.5.1+cu121-cp311-cp311-linux_x86_64.whl
```

## 🔨 Build Your Own

```bash
# Clone this repo
git clone https://github.com/intellistream/sagellm-pytorch-wheels.git
cd sagellm-pytorch-wheels

# Download and upload
./scripts/download_and_upload.sh 2.5.1 cu121
```

## 📝 Notes

- **Python Version**: Wheels are built for Python 3.11 (cp311)
- **Platform**: Linux x86_64 only
- **File Size**: ~800MB per PyTorch version
- **Official Source**: https://download.pytorch.org/whl/

## 🔗 Related

- [sageLLM](https://github.com/intellistream/sagellm) - Main project
- [PyTorch Official](https://pytorch.org/) - Official PyTorch website

## 📄 License

MIT License - See [LICENSE](LICENSE) for details

---

**Maintainer**: IntelliStream Team
