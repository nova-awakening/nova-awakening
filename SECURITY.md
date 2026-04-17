# Security Policy / 安全策略

## Supported Versions / 受支持版本

| Version | Supported |
|---------|-----------|
| Latest (master branch) | Yes |
| Older releases | No |

仅最新版本（master 分支）接受安全修复。

## Reporting a Vulnerability / 报告安全漏洞

**DO NOT** report security vulnerabilities through public GitHub Issues.
**请勿**通过公开的 GitHub Issues 报告安全漏洞。

Instead, please report security vulnerabilities by emailing
the project maintainer or by creating a **private** security advisory
on GitHub:

请通过以下方式报告安全漏洞：

1. **GitHub Security Advisories** (preferred / 首选):
   Go to the repository → Security tab → "Report a vulnerability"
   进入仓库 → Security 标签 → "Report a vulnerability"

2. **GitHub Issue with [安全] tag** (for non-critical issues):
   For issues that are not immediately exploitable, you may open
   an Issue tagged `[安全]`.
   对于不可立即利用的问题，可提交标注 `[安全]` 的 Issue。

## Response Timeline / 响应时间

- **Acknowledgment**: Within 72 hours of report
  **确认收到**：报告后72小时内
- **Initial assessment**: Within 7 days
  **初步评估**：7日内
- **Fix or mitigation**: Best effort, depending on severity
  **修复或缓解**：尽力而为，取决于严重程度

## Scope / 范围

The following are in scope for security reports:
以下属于安全报告范围：

- Vulnerabilities in the Nova compiler that could lead to
  arbitrary code execution during compilation
  Nova 编译器中可能导致编译期间任意代码执行的漏洞
- Vulnerabilities in the generated binary output
  生成的二进制输出中的漏洞
- Vulnerabilities in the Pure System (纯净版系统) components
  纯净版系统组件中的漏洞

## Disclosure Policy / 披露政策

We follow coordinated disclosure:
我们遵循协调披露原则：

1. Reporter notifies maintainer privately
   报告者私下通知维护者
2. Maintainer confirms and develops fix
   维护者确认并开发修复
3. Fix is released
   发布修复
4. Public disclosure after fix is available
   修复发布后公开披露

Thank you for helping keep Nova secure.
感谢您帮助保护 Nova 的安全。
