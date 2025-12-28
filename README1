# MLC-LLM DevOps Pipeline

A production-quality CI/CD pipeline for MLC-LLM with local development, automated testing, and cross-platform builds.

## Prerequisites

<table>
<thead>
<tr>
<th>Category</th>
<th>Requirement</th>
<th>Version</th>
<th>Notes</th>
</tr>
</thead>
<tbody>
<tr>
<td rowspan="3"><strong>Core Tools</strong></td>
<td>Docker & Docker Compose</td>
<td>20.10+</td>
<td>Required for containerized builds</td>
</tr>
<tr>
<td>Git with Git LFS</td>
<td>2.30+</td>
<td>For cloning repositories with large files</td>
</tr>
<tr>
<td>GitHub Account</td>
<td>-</td>
<td>Access to GitHub Container Registry (GHCR)</td>
</tr>
<tr>
<td rowspan="4"><strong>Development</strong></td>
<td>Python</td>
<td>3.11+</td>
<td>Primary language for MLC-LLM</td>
</tr>
<tr>
<td>CMake</td>
<td>3.20+</td>
<td>Build system configuration</td>
</tr>
<tr>
<td>LLVM</td>
<td>14+</td>
<td>Compiler infrastructure</td>
</tr>
<tr>
<td>Rust Toolchain</td>
<td>stable</td>
<td>Required for tokenizers</td>
</tr>
<tr>
<td><strong>CI/CD</strong></td>
<td>GitHub Actions</td>
<td>-</td>
<td>Self-hosted runners or GitHub-hosted</td>
</tr>
</tbody>
</table>

## 📦 Dependencies

<table>
<thead>
<tr>
<th>Component</th>
<th>Package</th>
<th>Installation</th>
<th>Purpose</th>
</tr>
</thead>
<tbody>
<tr>
<td rowspan="5"><strong>System Libraries</strong></td>
<td>build-essential</td>
<td><code>apt-get install build-essential</code></td>
<td>C/C++ compiler toolchain</td>
</tr>
<tr>
<td>llvm-dev</td>
<td><code>apt-get install llvm-dev</code></td>
<td>LLVM development files</td>
</tr>
<tr>
<td>libclang-dev</td>
<td><code>apt-get install libclang-dev</code></td>
<td>Clang library bindings</td>
</tr>
<tr>
<td>libvulkan-dev</td>
<td><code>apt-get install libvulkan-dev</code></td>
<td>Vulkan graphics API</td>
</tr>
<tr>
<td>git-lfs</td>
<td><code>apt-get install git-lfs</code></td>
<td>Git Large File Storage</td>
</tr>
<tr>
<td rowspan="4"><strong>Python Packages</strong></td>
<td>wheel</td>
<td><code>pip install wheel</code></td>
<td>Package building</td>
</tr>
<tr>
<td>setuptools</td>
<td><code>pip install setuptools</code></td>
<td>Package distribution</td>
</tr>
<tr>
<td>cmake</td>
<td><code>conda install cmake</code></td>
<td>CMake Python bindings</td>
</tr>
<tr>
<td>conda packages</td>
<td><code>conda install -c conda-forge ...</code></td>
<td>Various scientific packages</td>
</tr>
<tr>
<td><strong>Rust Crates</strong></td>
<td>rust toolchain</td>
<td><code>curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh</code></td>
<td>Rust compiler and cargo</td>
</tr>
</tbody>
</table>

## Quick Start

### 1. Clone Repository
```bash
git clone --recursive https://github.com/your-username/mlc-llm-devops.git
cd mlc-llm-devops
