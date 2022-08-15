# CMPG-323-Overview-32084463
```mermaid
graph TD;
    Repository-->Databaselike;
    Databaselike-->containsFiles;
    containsFiles-->StoreChanges;
    StoreChanges-->StoresProjects;
    Project-->OrganisesIssues;
    OrganisesIssues-->ManageWorkflow;
    Manageworkflow--> VisualiseProgress;
    VisualiseProgress-->StoredinRepository;
    Project-->StoredinRepository;
```
