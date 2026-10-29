# SQL Toolkit

Reusable SQL Server scripts, T-SQL queries, and database utilities for administration, diagnostics, data analysis, and development.

Created and maintained by **Kael Dowdy**, Senior Business Intelligence and Data Analytics Consultant and owner of **Maverick DataWorks LLC**.

This collection shares practical SQL examples with documentation to help you understand their purpose, requirements, and behavior. Scripts are published incrementally as they are reviewed and documented.

## Browse by purpose

Scripts are organized by purpose, with category folders directly under the repository root. The collection focuses on SQL Server and T-SQL.

| Planned category | What it covers |
| --- | --- |
| `administration` | Server and database properties, configuration inspection, and administrative utilities. |
| `diagnostics` | Sessions, connections, query text, and troubleshooting queries. |
| `data-analysis` | Queries for exploring, summarizing, and validating data. |
| `query-patterns` | Reusable examples of joins, window functions, aggregation, and other T-SQL techniques. |
| `database-development` | Examples involving tables, views, stored procedures, and functions. |
| `performance` | Query performance investigation and optimization examples. |

This table describes the planned organization. Folders appear as their first scripts are published. Links to available scripts will be added as the collection grows.

## Getting started

1. Read the script's comments and any accompanying documentation.
2. Check the required SQL Server version, database context, permissions, and dependencies.
3. Identify whether the script only reads information or changes data, database objects, or configuration.
4. Copy the script or download its `.sql` file and open it in SQL Server Management Studio or another compatible SQL editor.
5. Replace documented placeholders and confirm the target server and database.
6. Test in a suitable development environment and review the results before production use.

You can use individual scripts without cloning the repository. Some files contain multiple batches or independent queries; review the whole file before executing it.

## Documentation and dependencies

Where applicable, script comments or accompanying documentation explain:

- Purpose and intended use.
- Required parameters and placeholders.
- SQL Server version and platform requirements.
- Permissions and required database objects.
- Expected results, side effects, and limitations.
- Validation status and testing notes.

Sample database, schema, table, and column names may need to be adapted to your environment.

## Compatibility and execution

SQL dialects and features vary. Unless a script says otherwise, treat it as SQL Server T-SQL rather than portable SQL.

Any Azure-specific versions or requirements will be identified in the individual script or its accompanying documentation. Compatibility with Azure SQL Database, Azure SQL Managed Instance, Synapse, or Fabric must be checked per script. Diagnostic queries can require elevated permissions, and available metadata can vary by version and permissions.

Syntax checking does not establish runtime correctness. Even read-only queries can consume resources or affect concurrency. Review scripts that modify data, objects, or settings carefully, including their transaction and recovery requirements.

## Questions and contributions

Use this repository's Issues feature, where enabled, for questions, bug reports, and suggestions. Include the script name, SQL Server version, relevant error messages, and a small anonymized example showing expected and actual results.

Contributions are welcome. Explain the proposed change and how it was tested. Do not include credentials, confidential data, or private connection details.

## Author and contact

**Kael Dowdy**  
Senior Business Intelligence and Data Analytics Consultant  
Owner, Maverick DataWorks LLC

Connect with me on [LinkedIn](https://www.linkedin.com/in/kaeldowdy/) for professional networking and consulting inquiries.

## License

Licensed under the MIT License. See the `LICENSE` file for the full terms, including the warranty disclaimer and limitation of liability.

Retain the required copyright and license notices when redistributing copies or substantial portions of the code. Preserve any applicable third-party notices.
