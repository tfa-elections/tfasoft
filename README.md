# tfasoft
Open-source platform for real-time citizen-led election monitoring in Cameroon

TFASOFT is an open-source, citizen-driven electoral monitoring platform designed to ensure transparency and trust in democratic processes.
It empowers voters to securely report polling station results, validate them through a distributed consensus mechanism, and follow real-time
results — even in low-connectivity environments.

📁 Repository Structure

| Repository         | Description                                                                  | Link                                               | Technology                                                    |
|--------------------|------------------------------------------------------------------------------|----------------------------------------------------|---------------------------------------------------------------|
| tfasoft-backend/   | Core API, data models, consensus logic for the TFASOFT platform              | https://github.com/tfa-elections/tfasoft-backend   | Grails 5.2.3 (Groovy/Java)                                    |
| tfasoft-android/   | Native Android application for result submission and real time visualization | https://github.com/tfa-elections/tfasoft-android   | Kotlin                                                        |
| tfasoft-ios/       | Native iOS application for result submission and real time visualization     | https://github.com/tfa-elections/tfasoft-ios       | Swift                                                         |
| tfasoft-web/       | Public results dashboard (real-time visualization)                           | https://github.com/tfa-elections/tfasoft-web       | React.js                                                      |
| tfasoft-ml-engine/ | CI-based fraud detection and scoring engine                                  | https://github.com/tfa-elections/tfasoft-ml-engine | Python (scikit-learn, etc.)                                   |
| tfasoft-infra/     | Infrastructure-as-code, deployment automation, CI/CD                         | https://github.com/tfa-elections/tfasoft-infra     | AWS (S3, EC2), Terraform, Bash,<br/> Postgres, GitHub Actions |
| tfasoft-test-data/ | Synthetic data and test scenarios for validation                             | https://github.com/tfa-elections/tfasoft-test-data | CSV, JSON, YAML, SQL                                          |
| tfasoft-alerts/    | Dashboard showing all alerts about frauds and suspicious submissions         | https://github.com/tfa-elections/tfasoft-alerts    | React.js                                                      |
| tfasoft-admin/     | Administrative web app to remove fraudulent reports from consensus           | https://github.com/tfa-elections/tfasoft-admin     | React.js                                                      |
| tfasoft-docs/      | Whitepapers, specs, system architecture, API docs                            | https://github.com/tfa-elections/tfasoft-docs      | Markdown, PDF, Word, Excel, etc.                              |


🔑 Key Features

🔒 Secure, tamper-resistant citizen submissions

📸 Media upload (images, video) with metadata verification

📊 Distributed consensus engine per polling station

🗺️ Real-time, color-coded result maps by region

📡 Offline-first sync via Bluetooth/Wi-Fi mesh

🧠 ML-based fraud detection and alerting


📄 License

TFASOFT is released under the GNU General Public License v3.0 (GPLv3).

See the license in the LICENSE file or read the full license online at https://www.gnu.org/licenses/gpl-3.0.html.


📬 Contact

For questions, contributions, or to get involved:

📧 Email: contact@tfacam.org

🌍 Website: https://www.tfacam.org


🚀 Get Started

Each repository contains its own setup guide and build instructions. Please refer to individual README.md files within each repo to begin contributing or deploying.

💡 To propose changes to this README or the project structure, open an issue in the tfasoft-docs/ repository.
