# AWS-ML-Tools
1. Development Environments
Amazon SageMaker Studio: Web-based IDE for ML development (supports JupyterLab, VS Code OSS editor, RStudio, shared spaces).
Amazon SageMaker Studio Classic: Legacy IDE environment.
Amazon SageMaker Notebook Instances: Managed Jupyter notebook servers.
Amazon SageMaker Studio Lab: Free JupyterLab-based environment for quick experimentation.
Amazon SageMaker Code Editor: Enhanced code editor within SageMaker Studio for better workflow management.
Amazon SageMaker Multiple Spaces: Support for multiple workspaces per user per project.

2. Data Preparation & Feature Management
Amazon SageMaker Data Wrangler: Visual interface for data cleaning, transformation, and feature engineering.
Amazon SageMaker Feature Store: Central repository for storing, retrieving, and sharing ML features.

3. Model Training & Building
Amazon SageMaker Built-in Algorithms: Pre-optimized algorithms for common ML tasks.
Amazon SageMaker Automatic Model Tuning (AMT): Hyperparameter optimization.
Amazon SageMaker Training Compiler: Accelerates deep learning training on GPUs.
Amazon SageMaker Model Parallelism Library: Enables pipeline/tensor parallel training of very large models.
Amazon SageMaker Large Model Inference (LMI): Container for deploying large language models with high performance.

4. Model Tracking & Governance
Amazon SageMaker Experiments: Track training runs, parameters, and metrics.
Amazon SageMaker Model Registry: Manage model versions, approvals, and deployment lifecycle.
Amazon SageMaker Model Cards: Document model metadata for governance and reporting.
Amazon SageMaker ML Lineage Tracking: Trace datasets, code, and models throughout lifecycle.
Amazon SageMaker Model Dashboard: Unified view of deployed models and performance.

5. Workflows & Orchestration
Amazon SageMaker Pipelines: End-to-end ML workflow automation and CI/CD for ML.
Amazon SageMaker Projects: Prebuilt templates with best practices for secure ML projects.
Amazon SageMaker Notebook Workflows: Schedule and run Studio notebooks programmatically.
Amazon SageMaker Components for Kubeflow Pipelines: Integration with Kubeflow ML pipelines.

6. Model Deployment & Inference
Amazon SageMaker Neo: Optimize models for multiple hardware targets (cloud + edge).
Amazon SageMaker Edge Manager: Manage and monitor ML models on fleets of edge devices.
Amazon SageMaker Inference Recommender: Suggest best instance types/configs for model deployment.
Amazon SageMaker Batch Transform: Run large-scale offline inferences without endpoints.
Amazon SageMaker Inference Shadow Tests: Compare new infrastructure to production endpoints safely.
sagemaker endpoints
sagemaker severless inference
sagemaker asynchronous inference

7. Model Monitoring & Explainability
Amazon SageMaker Model Monitor: Detect drift, anomalies, and data quality issues in deployed models.
Amazon SageMaker Clarify: Bias detection, fairness analysis, and explainability tools for ML models.

8. Automation & Assisted ML
Amazon SageMaker Autopilot: End-to-end AutoML (automates training, tuning, and deployment).
Amazon SageMaker JumpStart: Prebuilt models, use-case templates, and example notebooks.
Amazon SageMaker Augmented AI (A2I): Human-in-the-loop workflows for review of predictions.
Amazon SageMaker AutoML Step for Pipelines: Integrate AutoML jobs into workflows.

9. Governance & Data Discovery
Amazon SageMaker Catalog: Discovery and governance of ML assets.
Amazon SageMaker Data and AI Governance: Security, lineage, compliance, and guardrails for AI workflows.

10. Analytics & Data Integration
Amazon SageMaker Unified Studio + Lakehouse Architecture: Combine analytics and ML workflows.
Amazon SageMaker SQL Analytics & Processing: Query and unify data across Amazon S3, Amazon Redshift, and federated sources.
Amazon SageMaker adds support for three new data sources: Direct connectivity to Oracle, Amazon DocumentDB, and Microsoft SQL Server databases.

11. Infrastructure & Scaling
Amazon SageMaker HyperPod: GPU clusters optimized for large-scale model training.
Amazon SageMaker Training Plans: Reserve GPU/compute for predictable workloads.

12. Generative AI & AI Assistants
Amazon SageMaker Partner AI Apps: Generative AI tools from AWS partners.
Amazon SageMaker Q Developer & Amazon SageMaker Canvas: Natural language assistants for coding and data workflows.
Amazon SageMaker with Amazon Bedrock Integration: Build generative AI apps using foundation models directly inside Studio.
Amazon Q Developer: Generative AI assistant for software development within SageMaker Unified Studio.
