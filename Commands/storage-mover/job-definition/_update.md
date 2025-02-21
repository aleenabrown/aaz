# [Command] _storage-mover job-definition update_

Update a Job Definition resource, which contains configuration for a single unit of managed data transfer.

## Versions

### [2023-03-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5zdG9yYWdlbW92ZXIvc3RvcmFnZW1vdmVycy97fS9wcm9qZWN0cy97fS9qb2JkZWZpbml0aW9ucy97fQ==/2023-03-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.storagemover/storagemovers/{}/projects/{}/jobdefinitions/{} 2023-03-01 -->

#### examples

- job-definition update
    ```bash
        storage-mover job-definition update -g {rg} -n {job_definition} --project-name {project_name} --storage-mover-name {mover_name} --copy-mode Mirror --agent-name {agent_name} --description JobDefinitionDescription2
    ```

### [2023-07-01-preview](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5zdG9yYWdlbW92ZXIvc3RvcmFnZW1vdmVycy97fS9wcm9qZWN0cy97fS9qb2JkZWZpbml0aW9ucy97fQ==/2023-07-01-preview.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.storagemover/storagemovers/{}/projects/{}/jobdefinitions/{} 2023-07-01-preview -->

#### examples

- job-definition update
    ```bash
        storage-mover job-definition update -g {rg} -n {job_definition} --project-name {project_name} --storage-mover-name {mover_name} --copy-mode Mirror --agent-name {agent_name} --description JobDefinitionDescription2
    ```

### [2023-10-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5zdG9yYWdlbW92ZXIvc3RvcmFnZW1vdmVycy97fS9wcm9qZWN0cy97fS9qb2JkZWZpbml0aW9ucy97fQ==/2023-10-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.storagemover/storagemovers/{}/projects/{}/jobdefinitions/{} 2023-10-01 -->

#### examples

- job-definition update
    ```bash
        storage-mover job-definition update -g {rg} -n {job_definition} --project-name {project_name} --storage-mover-name {mover_name} --copy-mode Mirror --agent-name {agent_name} --description JobDefinitionDescription2
    ```
