# CSM Organization

CSM is a multi-disciplinary software organization focused primarily on logistics technology, delivering scalable, modular solutions that streamline operations across transportation, warehousing, routing, and supply-chain automation. Alongside our logistics core, we also support cross-industry business requirements, providing extensible platforms and reusable components adaptable to diverse enterprise needs.

## Repository Management

This section explains how organization repositories are handled, named, and organized.

### Naming Conventions

- **dbt_{name}**: Represents a *database template* repository, providing foundational logic and schema patterns for the database it models.

- **db_{name}**: Represents a *database implementation* repository, containing a functional and deployable database instance.

- **fe_{name}**: Represents a *framework or language extension* used within the CSM development ecosystem.

- **pt_{name}**: Represents a *product template*, serving as the base logic for business products and used to generate final customer-specific implementations.

#### Prefix Glossary

- **dbt** - Database Template  
- **db** - Database  
- **fe** - Framework Extension  
- **pt** - Product Template

### Project management

When a repository is created after initial files are committed, a project is created to handle their current support and work pahe state, these are **public** to keep a clear view of current state of everything.

When a project is created they will be named with the repository name it is linked to, in order to easily track at what repo the project references.

Organization already has a template for a project named **prj_template** we highly recomment using it if there is not special requirements needed, it provides all workflow recommended.

## Issues Creation

We already have different issues templates to handle request easier, if you need to requeest a check for bug, and improvement or an enhancement please use one of our current created templates:

- **enhancement_template**: issue template to create an enhancement request.

- **bug_template**: issue template to create a bug to check request.

- **improvement_template**: issue template to analyze and include and improvement in already existing features.

## Organization contacts

For any question related to permission requests or improvement comments please contact following people.

- Juan Renato Urrea Ortiz - <UsuaryRenato@hotmail.com> (**Technical Management**)
