# References

# References

This document contains links to all sub-repositories and external resources for learning Internal Development Platforms (IDP).

## Sub-Repositories

### Core IDP Concepts

#### 1. Platform Engineering
**Repository**: [learning-idp-platform-engineering](https://github.com/vanHeemstraSystems/learning-idp-platform-engineering)

**Topics**:
- Platform Engineering principles and practices
- IDP architecture patterns
- Service catalogs and Golden Paths
- Backstage.io exploration
- Developer Experience (DevEx) optimization

**Status**: 🔴 Not started

---

#### 2. Infrastructure as Code
**Repository**: [learning-idp-infrastructure-as-code](https://github.com/vanHeemstraSystems/learning-idp-infrastructure-as-code)

**Topics**:
- Bicep templates
- ARM templates
- Azure SDK Infrastructure provisioning
- Terraform basics (context)
- Infrastructure testing strategies

**Status**: 🔴 Not started

---

### Development Practices

#### 3. Test-Driven Development
**Repository**: [learning-idp-test-driven-development](https://github.com/vanHeemstraSystems/learning-idp-test-driven-development)

**Topics**:
- TDD principles for infrastructure
- Pytest setup and patterns
- Mocking Azure SDK
- Unit vs Integration vs E2E tests
- CI/CD for tests
- Test fixtures and helpers

**Status**: 🔴 Not started   
**Priority**: 🔥 HIGH

---

#### 4. Python Azure SDK
**Repository**: [learning-idp-python-azure-sdk](https://github.com/vanHeemstraSystems/learning-idp-python-azure-sdk)

**Topics**:
- Azure SDK modules per service
- Authentication patterns (azure-identity)
- Resource management examples
- Best practices and patterns
- Error handling
- Performance optimization

**Status**: 🔴 Not started   
**Priority**: 🔥 HIGH

---

### Azure Services

#### 5. Azure Compute
**Repository**: [learning-idp-azure-compute](https://github.com/vanHeemstraSystems/learning-idp-azure-compute)

**Topics**:
- Virtual Machines
- Container Instances
- Azure Kubernetes Service (AKS)
- Azure SDK compute management
- Deployment patterns
- Scaling strategies

**Status**: 🔴 Not started

---

#### 6. Azure Networking
**Repository**: [learning-idp-azure-networking](https://github.com/vanHeemstraSystems/learning-idp-azure-networking)

**Topics**:
- Virtual Networks (VNets)
- Subnets and Network Security Groups (NSGs)
- Load Balancers
- Application Gateway
- Private Endpoints
- Network security patterns

**Status**: 🔴 Not started

---

#### 7. Azure Storage
**Repository**: [learning-idp-azure-storage](https://github.com/vanHeemstraSystems/learning-idp-azure-storage)

**Topics**:
- Storage Accounts
- Blob, File, Queue, Table storage
- Azure Data Lake
- Access policies and security
- SDK integration patterns

**Status**: 🔴 Not started

---

#### 8. Azure Security
**Repository**: [learning-idp-azure-security](https://github.com/vanHeemstraSystems/learning-idp-azure-security)

**Topics**:
- Azure Key Vault integration
- Managed Identities
- Azure Policy
- Role-Based Access Control (RBAC)
- Security best practices
- Compliance patterns

**Status**: 🔴 Not started

---

### DevOps & Automation

#### 9. CI/CD Pipelines
**Repository**: [learning-idp-cicd-pipelines](https://github.com/vanHeemstraSystems/learning-idp-cicd-pipelines)

**Topics**:
- Azure DevOps pipelines
- GitHub Actions
- Pipeline-as-Code
- Deployment strategies
- Testing in pipelines
- GitOps patterns

**Status**: 🔴 Not started

---

#### 10. Observability
**Repository**: [learning-idp-observability](https://github.com/vanHeemstraSystems/learning-idp-observability)

**Topics**:
- Azure Monitor
- Application Insights
- Log Analytics
- Alerting strategies
- Dashboard automation
- Distributed tracing

**Status**: 🔴 Not started

---

### Advanced Topics

#### 11. API Development
**Repository**: [learning-idp-api-development](https://github.com/vanHeemstraSystems/learning-idp-api-development)

**Topics**:
- Python FastAPI/Flask for IDP APIs
- Azure API Management integration
- Authentication/Authorization
- OpenAPI/Swagger
- API versioning
- Rate limiting

**Status**: 🔴 Not started

---

#### 12. Containerization
**Repository**: [learning-idp-containerization](https://github.com/vanHeemstraSystems/learning-idp-containerization)

**Topics**:
- Docker for IDP components
- AKS deployment patterns
- Helm charts
- Container security
- Multi-stage builds
- Container registries (ACR)

**Status**: 🔴 Not started

---

## External Resources

### Official Documentation

#### Microsoft Azure
- [Azure SDK for Python Documentation](https://learn.microsoft.com/en-us/azure/developer/python/)
- [Azure Architecture Center](https://learn.microsoft.com/en-us/azure/architecture/)
- [Azure Well-Architected Framework](https://learn.microsoft.com/en-us/azure/well-architected/)
- [Azure DevOps Documentation](https://learn.microsoft.com/en-us/azure/devops/)

#### Platform Engineering
- [Backstage.io Official Docs](https://backstage.io/docs/overview/what-is-backstage)
- [CNCF Platform Engineering](https://www.cncf.io/blog/2023/05/17/what-is-platform-engineering/)
- [Team Topologies](https://teamtopologies.com/)

#### Python & Testing
- [Pytest Documentation](https://docs.pytest.org/)
- [Python Testing Best Practices](https://realpython.com/pytest-python-testing/)
- [Azure SDK for Python GitHub](https://github.com/Azure/azure-sdk-for-python)

---

### Books

#### Platform Engineering
- **"Team Topologies"** by Matthew Skelton and Manuel Pais
- **"Platform Engineering on Kubernetes"** by Mauricio Salatino
- **"Building Evolutionary Architectures"** by Neal Ford, Rebecca Parsons, Patrick Kua

#### Cloud & Azure
- **"Azure for Architects"** by Ritesh Modi
- **"Infrastructure as Code"** by Kief Morris
- **"Cloud Native DevOps with Kubernetes"** by John Arundel and Justin Domingus

#### Testing
- **"Test Driven Development: By Example"** by Kent Beck
- **"Python Testing with pytest"** by Brian Okken
- **"Unit Testing Principles, Practices, and Patterns"** by Vladimir Khorikov

---

### Articles & Blog Posts

#### Platform Engineering
- [What is Platform Engineering?](https://platformengineering.org/blog/what-is-platform-engineering) - Platform Engineering Community
- [Building an Internal Developer Platform](https://www.thoughtworks.com/insights/articles/building-internal-developer-platform) - ThoughtWorks
- [Platform as a Product](https://martinfowler.com/articles/platform-prerequisites.html) - Martin Fowler

#### Azure & IDP
- [Azure Landing Zones](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/ready/landing-zone/) - Microsoft
- [Building an IDP on Azure](https://techcommunity.microsoft.com/blog/) - Microsoft Tech Community

#### Test-Driven Development
- [TDD for Infrastructure](https://www.hashicorp.com/resources/test-driven-development-tdd-for-infrastructure) - HashiCorp
- [Testing Infrastructure as Code](https://www.infoq.com/articles/testing-infrastructure-as-code/) - InfoQ

---

### Video Resources

#### Conferences & Talks
- [Platform Engineering on Azure - Microsoft Build](https://build.microsoft.com/)
- [PlatformCon Talks](https://platformcon.com/talks) - Platform Engineering Conference
- [KubeCon + CloudNativeCon](https://www.cncf.io/kubecon-cloudnativecon-events/)

#### YouTube Channels
- [Microsoft Azure](https://www.youtube.com/@MicrosoftAzure)
- [Azure DevOps](https://www.youtube.com/@AzureDevOps)
- [CNCF](https://www.youtube.com/@cncf)

---

### Online Courses

#### Microsoft Learn
- [AZ-305: Azure Solutions Architect Expert](https://learn.microsoft.com/en-us/credentials/certifications/azure-solutions-architect/)
- [AZ-700: Azure Network Engineer Associate](https://learn.microsoft.com/en-us/credentials/certifications/azure-network-engineer-associate/)
- [Azure SDK for Python Learning Path](https://learn.microsoft.com/en-us/training/paths/azure-python-sdk/)

#### Other Platforms
- [Platform Engineering Fundamentals](https://www.pluralsight.com/) - Pluralsight
- [Azure DevOps: The Complete Guide](https://www.udemy.com/) - Udemy
- [Test-Driven Development with Python](https://testdriven.io/) - TestDriven.io

---

### Community & Forums

- [Platform Engineering Slack](https://platformengineering.org/slack-rd) - Platform Engineering Community
- [Azure Community](https://techcommunity.microsoft.com/t5/azure/ct-p/Azure) - Microsoft Tech Community
- [r/AZURE](https://www.reddit.com/r/AZURE/) - Reddit
- [Stack Overflow - Azure Tag](https://stackoverflow.com/questions/tagged/azure)
- [CNCF Slack](https://slack.cncf.io/)

---

### Tools & Frameworks

#### IDP Platforms
- [Backstage](https://backstage.io/) - Open source developer portal
- [Port](https://www.getport.io/) - Internal developer portal
- [Kratix](https://kratix.io/) - Platform-as-a-Product framework

#### Testing Tools
- [pytest](https://pytest.org/) - Python testing framework
- [pytest-azurepipelines](https://pypi.org/project/pytest-azurepipelines/) - Azure Pipelines integration
- [moto](https://github.com/getmoto/moto) - Mock AWS services (reference for patterns)

#### Infrastructure Tools
- [Bicep](https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/) - Azure IaC
- [Terraform](https://www.terraform.io/) - Multi-cloud IaC
- [Pulumi](https://www.pulumi.com/) - Modern IaC with real programming languages

---

## Learning Status Legend

- 🔴 Not started
- 🟡 In progress
- 🟢 Completed
- 🔥 HIGH priority
- ⭐ MEDIUM priority
- 💡 LOW priority

---

*Last updated: December 18, 2025*

