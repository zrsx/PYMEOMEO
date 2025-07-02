# PYMEOMEO

> **Advanced Python Obfuscation and Protection Suite**

**PYMEOMEO** is a next-generation, high-performance framework for Python code protection. It is purpose-built to safeguard proprietary source code against reverse engineering, static analysis, and decompilation in both professional and enterprise environments.

---

## Key Features

- **Comprehensive Obfuscation**: Employs advanced code transformation techniques to maximize code confidentiality and impede reverse engineering efforts.
- **Multi-Layer Protection**: Optional encryption and compression layers further increase code complexity and reduce script footprint.
- **Dynamic Code Execution**: Supports runtime code generation, enhancing unpredictability and resilience.
- **Integrated Anti-Analysis**: Incorporates robust anti-debugging and anti-decompilation features to resist both static and dynamic inspection.
- **Python Version Enforcement**: Ensures protected code executes only on authorized Python versions.
- **Intuitive Command-Line Interface**: Designed for ease of use with a streamlined, professional workflow.
- **Optimized Performance**: Engineered for efficient, large-scale obfuscation tasks.
- **Self-Contained Outputs**: Generates standalone, protected Python scripts with embedded integrity checks.
- **Traceable Build Metadata**: Supports user and build tagging for distribution control and auditing.
- **Ongoing Development**: Actively maintained and updated for continued compatibility and security enhancements.

---

## Requirements

- **Python Versions Supported**: 3.10 – 3.13  
- **Dependency**:  
  - [`pystyle`](https://pypi.org/project/pystyle/) (`pip install pystyle`)

---

## Usage

Select and execute the obfuscator script matching your Python version:

- **Python 3.10**
  ```bash
  python3.10 _bes310.py
  ```
- **Python 3.11**
  ```bash
  python3.11 _bes311.py
  ```
- **Python 3.12**
  ```bash
  python3.12 _bes312.py
  ```
- **Python 3.13**
  ```bash
  python3.13 _bes313.py
  ```

---

## Best Practices

- **Always test your obfuscated scripts** in a controlled environment matching your intended deployment.
- **Retain backup copies** of your original source code as obfuscation is a one-way process.
- **Review output scripts** for any compatibility issues specific to your Python runtime.
- **Consult documentation and changelogs** for details about updates and compatibility notes.

---

## Security & Anti-Tamper

PYMEOMEO includes advanced, proprietary anti-debugging and anti-analysis mechanisms designed to proactively detect and disrupt unauthorized inspection or tampering.  
Key defensive strategies include:

- Runtime environment verification and integrity checks.
- Defensive measures against common debugging and reverse engineering tools.
- Dynamic behavior to further complicate automated analysis and decompilation.
- Continuous enhancement to address evolving security threats.

*Details of internal security mechanisms are proprietary and not publicly disclosed to preserve effectiveness.*

---

## Example Workflow

1. **Install dependencies:**
   ```bash
   pip install pystyle
   ```

2. **Prepare your source script** (e.g., `main.py`).

3. **Run the obfuscator:**
   ```bash
   python3.10 _bes310.py --input main.py --output main_protected.py
   ```

4. **Deploy your protected script** using the same Python version as used for obfuscation.

---

## Frequently Asked Questions

**Q: Does PYMEOMEO guarantee absolute code security?**  
A: While PYMEOMEO provides state-of-the-art protection, no software obfuscation can guarantee absolute security against all possible attacks. It is a critical layer in a comprehensive security strategy.

**Q: What Python features are supported?**  
A: PYMEOMEO supports a wide range of Python code constructs and is regularly updated to maintain compatibility with the latest language features.

**Q: Can I use the obfuscated code on other platforms?**  
A: Yes, provided the target system uses a compatible Python interpreter version.

**Q: Are there any performance impacts?**  
A: Obfuscated code may incur a slight performance overhead due to added protection layers, but PYMEOMEO is optimized for minimal disruption.

**Q: How can I report issues or request features?**  
A: Please open an issue on the GitHub repository or contact the maintainers directly.

---

## Roadmap

- Ongoing improvements to obfuscation depth and complexity.
- Enhanced anti-analysis features targeting new and emerging threats.
- Broader compatibility with additional Python versions.
- Improved user interface and documentation.

---

## Contribution Guidelines

We welcome contributions that align with the project's goals and quality standards. To contribute:

1. Fork the repository and create your feature branch.
2. Commit your changes with clear, descriptive messages.
3. Submit a pull request describing your modifications and rationale.

All contributions undergo review for security, reliability, and maintainability.

---

## Authors & Maintainers

- **Original Author:**  
  [hngocuyen](https://github.com/hngocuyen)

- **Enhancements, Maintenance, and Extensions:**  
  [George](https://github.com/Aasyaco)  
  [Ahmad](https://github.com/Ansyso)

---

## License

Licensed under the [Apache License 2.0](LICENSE).

---

## Disclaimer

PYMEOMEO is a tool for ethical code protection. Use only on code for which you have legal rights.  
The maintainers assume no responsibility for misuse or damages arising from improper or unlawful application of this software.

---

> For professional support, contributions, or feature requests, please open an issue or contact the maintainers via GitHub.
