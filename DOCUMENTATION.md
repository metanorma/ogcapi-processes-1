# Description provenance

Provenance of the schema descriptions in `openapi/ogcapi-processes.yaml` (and the per-schema definitions under `openapi/schemas/`): every description was authored from the standard's own requirements classes and prose — none imported.

| Schema | Source | Description (first sentence) |
|---|---|---|
| `AnyLiteralList` | OGC 18-062 requirements classes | A list of literal values permitted for an input. |
| `AnyLiteralType` | OGC 18-062 requirements classes | A literal value of any permitted type. |
| `AnyType` | OGC 18-062 requirements classes | A value of any type, unconstrained. |
| `CQL2` | OGC 18-062 requirements classes | A CQL2 filter expression, constraining the inputs of a process per the OGC CQL2 standard. |
| `CWL` | OGC 18-062 requirements classes | A Common Workflow Language (CWL) process definition embedded in an OGC App-Pkg deployment. |
| `CWLArguments` | OGC 18-062 requirements classes | The command-line arguments of a CWL tool invocation. |
| `CWLAtomic` | OGC 18-062 requirements classes | A single (non-composite) CWL value of an input or output. |
| `CWLAtomicBase` | OGC 18-062 requirements classes | The base scalar types of a CWL value. |
| `CWLAtomicNested` | OGC 18-062 requirements classes | A CWL scalar value nested inside a composite type. |
| `CWLCommand` | OGC 18-062 requirements classes | The command-line template of a CWL tool or expression tool. |
| `CWLDefault` | OGC 18-062 requirements classes | The default value of a CWL input parameter. |
| `CWLDefaultLocation` | OGC 18-062 requirements classes | A default value of a CWL input referenced by location. |
| `CWLDefaultObject` | OGC 18-062 requirements classes | A default value of a CWL input given as an object. |
| `CWLDefaultTypedConditional` | OGC 18-062 requirements classes | A default value with a conditional type in a CWL input. |
| `CWLDirectoryOnlyParametersConditional` | OGC 18-062 requirements classes | A CWL input restricted to directory values under a conditional type. |
| `CWLDocumentation` | OGC 18-062 requirements classes | The documentation field of a CWL process definition. |
| `CWLExpression` | OGC 18-062 requirements classes | A CWL expression evaluated at runtime to derive parameter values. |
| `CWLFileOnlyParameters` | OGC 18-062 requirements classes | A CWL input or output restricted to File values. |
| `CWLFileOnlyParametersConditional` | OGC 18-062 requirements classes | A CWL input or output restricted to File values under a conditional type. |
| `CWLGraph` | OGC 18-062 requirements classes | A CWL workflow graph: the steps and their dependencies. |
| `CWLHints` | OGC 18-062 requirements classes | The hints of a CWL process: optional, non-binding resource requirements. |
| `CWLHintsList` | OGC 18-062 requirements classes | The hints of a CWL process given as a list. |
| `CWLHintsMap` | OGC 18-062 requirements classes | The hints of a CWL process given as a map. |
| `CWLImport` | OGC 18-062 requirements classes | A CWL $import reference to an external definition. |
| `CWLInputItem` | OGC 18-062 requirements classes | One input parameter of a CWL process. |
| `CWLInputList` | OGC 18-062 requirements classes | The input parameters of a CWL process given as a list. |
| `CWLInputMap` | OGC 18-062 requirements classes | The input parameters of a CWL process given as a map. |
| `CWLInputStdIn` | OGC 18-062 requirements classes | Marks a CWL input taken from standard input. |
| `CWLInputStdInDefinition` | OGC 18-062 requirements classes | The definition of a CWL input taken from standard input. |
| `CWLInputStdInObjectType` | OGC 18-062 requirements classes | The object type of a CWL standard-input input. |
| `CWLInputsDefinition` | OGC 18-062 requirements classes | The inputs section of a CWL process definition. |
| `CWLMetadata` | OGC 18-062 requirements classes | The metadata fields of a CWL process definition. |
| `CWLOutputItem` | OGC 18-062 requirements classes | One output parameter of a CWL process. |
| `CWLOutputList` | OGC 18-062 requirements classes | The output parameters of a CWL process given as a list. |
| `CWLOutputMap` | OGC 18-062 requirements classes | The output parameters of a CWL process given as a map. |
| `CWLOutputObject` | OGC 18-062 requirements classes | An output of a CWL process given as an object. |
| `CWLOutputStdErr` | OGC 18-062 requirements classes | Marks a CWL output captured from standard error. |
| `CWLOutputStdErrDefinition` | OGC 18-062 requirements classes | The definition of a CWL output captured from standard error. |
| `CWLOutputStdErrObjectType` | OGC 18-062 requirements classes | The object type of a CWL standard-error output. |
| `CWLOutputStdOut` | OGC 18-062 requirements classes | Marks a CWL output captured from standard output. |
| `CWLOutputStdOutDefinition` | OGC 18-062 requirements classes | The definition of a CWL output captured from standard output. |
| `CWLOutputStdOutObjectType` | OGC 18-062 requirements classes | The object type of a CWL standard-output output. |
| `CWLOutputsDefinition` | OGC 18-062 requirements classes | The outputs section of a CWL process definition. |
| `CWLRequirements` | OGC 18-062 requirements classes | The requirements of a CWL process: mandatory features the execution platform must support. |
| `CWLRequirementsItem` | OGC 18-062 requirements classes | One requirement of a CWL process. |
| `CWLRequirementsList` | OGC 18-062 requirements classes | The requirements of a CWL process given as a list. |
| `CWLRequirementsMap` | OGC 18-062 requirements classes | The requirements of a CWL process given as a map. |
| `CWLType` | OGC 18-062 requirements classes | The type of a CWL input or output parameter. |
| `CWLTypeArray` | OGC 18-062 requirements classes | An array type of a CWL parameter. |
| `CWLTypeBase` | OGC 18-062 requirements classes | A base scalar or file type of a CWL parameter. |
| `CWLTypeDefinition` | OGC 18-062 requirements classes | The type definition of a CWL parameter. |
| `CWLTypeEnum` | OGC 18-062 requirements classes | An enumerated type of a CWL parameter. |
| `CWLTypeList` | OGC 18-062 requirements classes | A list type of a CWL parameter. |
| `CWLTypeRecordArray` | OGC 18-062 requirements classes | An array of CWL record types. |
| `CWLTypeRecordFieldDef` | OGC 18-062 requirements classes | The definition of one field of a CWL record type. |
| `CWLTypeRecordFieldDefBase` | OGC 18-062 requirements classes | The base type of a CWL record field. |
| `CWLTypeRecordFields` | OGC 18-062 requirements classes | The fields of a CWL record type. |
| `CWLTypeRecordFieldsList` | OGC 18-062 requirements classes | The fields of a CWL record type given as a list. |
| `CWLTypeRecordFieldsMap` | OGC 18-062 requirements classes | The fields of a CWL record type given as a map. |
| `CWLTypeRecordRef` | OGC 18-062 requirements classes | A reference to a CWL record type. |
| `CWLTypeRecordSchema` | OGC 18-062 requirements classes | The record schema of a CWL parameter. |
| `CWLTypeRecordSecondaryFileSchema` | OGC 18-062 requirements classes | The secondary-file schema of a CWL record type. |
| `CWLTypeRecordSecondaryFiles` | OGC 18-062 requirements classes | The secondary files associated with a CWL record type. |
| `CWLVersion` | OGC 18-062 requirements classes | The CWL specification version of the process definition. |
| `CWLWorkflow` | OGC 18-062 requirements classes | A CWL workflow: a directed graph of steps composing tools into an analysis. |
| `CWLWorkflowBase` | OGC 18-062 requirements classes | The base definition shared by CWL workflow descriptions. |
| `CWLWorkflowClass` | OGC 18-062 requirements classes | The class marker (Workflow) of a CWL workflow definition. |
| `CWLWorkflowStepDefinition` | OGC 18-062 requirements classes | The definition of one step of a CWL workflow. |
| `CWLWorkflowStepId` | OGC 18-062 requirements classes | The identifier of a CWL workflow step. |
| `CWLWorkflowStepIn` | OGC 18-062 requirements classes | The input bindings of a CWL workflow step. |
| `CWLWorkflowStepInItem` | OGC 18-062 requirements classes | One input binding of a CWL workflow step. |
| `CWLWorkflowStepInList` | OGC 18-062 requirements classes | The input bindings of a CWL workflow step given as a list. |
| `CWLWorkflowStepInMap` | OGC 18-062 requirements classes | The input bindings of a CWL workflow step given as a map. |
| `CWLWorkflowStepInputBase` | OGC 18-062 requirements classes | The base type of a CWL workflow step input. |
| `CWLWorkflowStepInputDefault` | OGC 18-062 requirements classes | The default value of a CWL workflow step input. |
| `CWLWorkflowStepInputId` | OGC 18-062 requirements classes | The identifier of a CWL workflow step input. |
| `CWLWorkflowStepList` | OGC 18-062 requirements classes | The steps of a CWL workflow given as a list. |
| `CWLWorkflowStepMap` | OGC 18-062 requirements classes | The steps of a CWL workflow given as a map. |
| `CWLWorkflowStepObject` | OGC 18-062 requirements classes | A CWL workflow step given as an object. |
| `CWLWorkflowStepOut` | OGC 18-062 requirements classes | The outputs a CWL workflow step exposes to later steps. |
| `CWLWorkflowStepRun` | OGC 18-062 requirements classes | The tool or sub-workflow a CWL workflow step runs. |
| `CWLWorkflowStepScatter` | OGC 18-062 requirements classes | The scatter specification of a CWL workflow step. |
| `CWLWorkflowStepWhen` | OGC 18-062 requirements classes | The conditional (when) expression of a CWL workflow step. |
| `CWLWorkflowSteps` | OGC 18-062 requirements classes | The steps of a CWL workflow. |
| `DirectoryListingDirent` | OGC 18-062 requirements classes | One entry of a directory listing in a CWL initial work directory. |
| `DirectoryListingFileOrDirectory` | OGC 18-062 requirements classes | A file or directory entry in a CWL directory listing. |
| `DockerRequirement` | OGC 18-062 requirements classes | A CWL requirement specifying the Docker image in which the process executes. |
| `EnvVarRequirement` | OGC 18-062 requirements classes | A CWL requirement defining environment variables for the execution. |
| `EnvironmentDef` | OGC 18-062 requirements classes | The definition of an environment variable for a CWL execution. |
| `InitialWorkDirListing` | OGC 18-062 requirements classes | The listing of files staged into the working directory before a CWL execution. |
| `InitialWorkDirRequirement` | OGC 18-062 requirements classes | A CWL requirement staging files into the initial working directory. |
| `InlineJavascriptRequirement` | OGC 18-062 requirements classes | A CWL requirement enabling inline Javascript expressions. |
| `InplaceUpdateRequirement` | OGC 18-062 requirements classes | A CWL requirement declaring in-place update semantics for nested outputs. |
| `InputBinding` | OGC 18-062 requirements classes | The command-line binding of a CWL input parameter. |
| `LoadListingRequirement` | OGC 18-062 requirements classes | A CWL requirement controlling how directory inputs are loaded into listings. |
| `MultipleInputFeatureRequirement` | OGC 18-062 requirements classes | A CWL requirement enabling an input to accept multiple values. |
| `NetworkAccess` | OGC 18-062 requirements classes | A CWL requirement declaring whether the execution requires network access. |
| `NetworkAccessRequirement` | OGC 18-062 requirements classes | A CWL requirement declaring the network access needs of the tool. |
| `ResourceQuantityOrFractional` | OGC 18-062 requirements classes | A CWL resource allocation given as a quantity or a fraction of the available resources. |
| `ResourceRequirement` | OGC 18-062 requirements classes | A CWL requirement declaring the compute resources (cores, memory, tmpdir) of the execution. |
| `ScatterFeatureRequirement` | OGC 18-062 requirements classes | A CWL requirement enabling scattering an input over multiple executions. |
| `SchemaDefRequirement` | OGC 18-062 requirements classes | A CWL requirement defining custom schemas used by the inputs and outputs. |
| `ShellCommandRequirement` | OGC 18-062 requirements classes | A CWL requirement enabling shell command expressions in the command line. |
| `SoftwarePackage` | OGC 18-062 requirements classes | A software package required by a CWL execution, with its version specs. |
| `SoftwarePackageSpecs` | OGC 18-062 requirements classes | The version specifications of a required software package. |
| `SoftwareRequirement` | OGC 18-062 requirements classes | A CWL requirement listing the software packages the execution needs. |
| `StepInputExpressionRequirement` | OGC 18-062 requirements classes | A CWL requirement enabling expressions in workflow step inputs. |
| `SubworkflowFeatureRequirement` | OGC 18-062 requirements classes | A CWL requirement enabling nested sub-workflows. |
| `ToolTimeLimitRequirement` | OGC 18-062 requirements classes | A CWL requirement limiting the tool execution time. |
| `WorkReuseRequirement` | OGC 18-062 requirements classes | A CWL requirement controlling reuse of prior execution outputs. |
| `apis` | OGC 18-062 requirements classes (Processes - Part 1: Core) | The conformance classes and entry points of the APIs advertised by this deployment. |
| `bbox-processes` | OGC 18-062 requirements classes | A bounding box constraint on the area of interest of a process input. |
| `binaryValue` | OGC 18-062 requirements classes (Processes - Part 1: Core) | A binary input or output value, encoded per its declared media type. |
| `collectionDesc` | OGC API - Common building blocks | A description of a collection that hosts the results of a job. |
| `collectionValue` | OGC 18-062 requirements classes (Processes - Part 1: Core) | A result value hosted as a collection. |
| `collections` | OGC API - Common building blocks | A list of the collections available on this API. |
| `confClasses` | OGC 19-072 (OGC API - Common - Part 1: Core) | The conformance classes the deployment implements, per the OGC API conformance declaration. |
| `crs` | OGC Topic 2 (referencing by coordinates) | The coordinate reference systems supported for spatial inputs and outputs. |
| `cwltool_CUDARequirement` | OGC 18-062 requirements classes | The cwltool CUDA requirement for GPU-accelerated executions. |
| `dataAccessAPIs` | OGC 18-062 requirements classes (Processes - Part 1: Core) | The data access APIs through which the outputs of a job can be retrieved. |
| `dataClasses` | OGC 18-062 requirements classes (Processes - Part 1: Core) | The data classes supported by a process deployment. |
| `dataType` | OGC API - Common building blocks | A data type declaration for an input or output value. |
| `descriptionType` | OGC 18-062 requirements classes (Processes - Part 1: Core) | Base type for process, input and output descriptions: identifier, title, description, metadata and additional classification information. |
| `enumeration` | OGC 18-062 requirements classes | An input whose value must be one of an enumerated set of literals. |
| `exception` | OGC 19-072 (OGC API - Common - Part 1: Core) | An exception report describing why a request failed, per the OGC API exception convention. |
| `execute-workflow` | OGC 18-062 requirements classes | An execute request for a process deployed as a workflow, combining the inputs of the nested processes. |
| `extent` | OGC API - Common building blocks | The spatial and temporal extent of a collection or deployment. |
| `extent-UAD` | OGC API - Common building blocks | The extent of a collection with unknown, unlimited or multi-dimensional axes. |
| `fieldsModifiers` | OGC 18-062 requirements classes (Processes - Part 1: Core) | Modifiers restricting the fields (properties) of an input or output object. |
| `format` | OGC 18-062 requirements classes (Processes - Part 1: Core) | The format of an input or output value: media type, encoding and schema. |
| `inlineOrRefValue` | OGC 18-062 requirements classes (Processes - Part 1: Core) | Either an inline literal, object or array value, or a reference to a remote value that is fetched at execution time. |
| `inlineOrRefValue-workflows` | OGC 18-062 requirements classes | Either an inline literal, object or array value, or a reference to a remote value, for workflow inputs and outputs. |
| `inputDescription` | OGC 18-062 requirements classes (Processes - Part 1: Core) | A description of an input of a process, including its schema, metadata and the supported input values. |
| `inputParameterized` | OGC 18-062 requirements classes | An input description with a schema that constrains the permitted values of the input. |
| `jobControlOptions` | OGC 18-062 requirements classes (Processes - Part 1: Core) | The job control options supported by this API: asynchronous execution, synchronous execution and/or dismiss of running jobs. |
| `jobList` | OGC 18-062 requirements classes (Processes - Part 1: Core) | A list of jobs created by this API for the current user. |
| `landingPage` | OGC 19-072 (OGC API - Common - Part 1: Core) | The landing page of the API: links to the conformance declaration, collections and processes. |
| `link` | OGC 19-072 (OGC API - Common - Part 1: Core) | A hyperlink with its relation type, per the OGC API link conventions. |
| `metadata` | OGC 18-062 requirements classes (Processes - Part 1: Core) | Additional metadata of a process, input or output: roles with typed values or external references. |
| `numberMatched` | OGC API - Common building blocks | The number of items matching the selection criteria, if the server can determine it. |
| `numberReturned` | OGC API - Common building blocks | The number of items returned in this response. |
| `ogcapppkg` | OGC 18-062 requirements classes | An OGC API - Processes application package (OGC App-Pkg): the deployment description of a process, referencing or embedding the executable artifacts. |
| `outputDescription` | OGC 18-062 requirements classes (Processes - Part 1: Core) | A description of an output of a process, including its schema and metadata. |
| `outputSelection` | OGC 18-062 requirements classes (Processes - Part 1: Core) | Selects the outputs of a process to be included in the results of an execution; by default all outputs are returned. |
| `process` | OGC 18-062 requirements classes (Processes - Part 1: Core) | A process that can be executed by this API. |
| `processList` | OGC 18-062 requirements classes (Processes - Part 1: Core) | A list of the processes available on this API together with their summaries. |
| `processSummary` | OGC 18-062 requirements classes (Processes - Part 1: Core) | A summary of a process that can be executed by this API, including its machine-readable and human-readable metadata. |
| `processes-list` | OGC 18-062 requirements classes | A list of the processes available on this API. |
| `qualifiedValue` | OGC 18-062 requirements classes (Processes - Part 1: Core) | A value together with the format it is encoded in, used where multiple formats are supported. |
| `reference` | OGC 18-062 requirements classes (Processes - Part 1: Core) | A reference to external metadata: the role of the reference and its URL. |
| `results` | OGC 18-062 requirements classes (Processes - Part 1: Core) | The outputs of a successfully completed job execution. |
| `schema` | OGC 18-062 requirements classes (Processes - Part 1: Core) | The schema constraining the values of an input or output. |
| `schemaAndOccurrences` | OGC 18-062 requirements classes (Processes - Part 1: Core) | A schema together with the occurrences of the input in the process. |
| `staticIndicator` | OGC 18-062 requirements classes | Indicates whether the input value of a workflow is static (identical for every nested execution) or dynamic. |
| `statusCode` | OGC 18-062 requirements classes (Processes - Part 1: Core) | The state of the job execution: accepted, running, successful, failed or dismissed. |
| `statusInfo` | OGC 18-062 requirements classes (Processes - Part 1: Core) | The status of an execution job, including its current state (accepted, running, successful, failed or dismissed) and, once available, the location of the results. |
| `subscriber` | OGC 18-062 requirements classes (Processes - Part 1: Core) | Optional subscriber endpoints the client may supply so that the API can asynchronously notify the client about job progress and completion. |
| `timeStamp` | OGC API - Common building blocks | The timestamp of the response, per RFC 3339. |
| `value` | OGC 18-062 requirements classes (Processes - Part 1: Core) | A permitted value of an input with an optional human-readable label. |
| `valueNoObject` | OGC 18-062 requirements classes (Processes - Part 1: Core) | A literal or array value of an input, excluding object values. |
| `valueNoObject-workflows` | OGC 18-062 requirements classes | A literal or array value of a workflow input, excluding object values. |
| `values` | OGC 18-062 requirements classes (Processes - Part 1: Core) | The permitted values of an input, as an enumeration, range or schema. |
| `values-workflows` | OGC 18-062 requirements classes | The permitted values of a workflow input, as an enumeration, range or schema. |

These descriptions are offered upstream as part of the model-based publication program (metanorma-ogc#153); corrections by the editors are welcome and will be tracked here.
