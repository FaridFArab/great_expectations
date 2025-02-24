---
title: Install additional dependencies
---
import GxData from '../_core_components/_data.jsx';
import TabItem from '@theme/TabItem';
import Tabs from '@theme/Tabs';
import PrereqPythonInstalled from '../_core_components/prerequisites/_python_installation.md';
import InstallAmazon from './_install_additional_dependencies/_amazon_s3.md'
import InstallAzureBlobStorage from './_install_additional_dependencies/_azure_blob_storage.md'
import InstallGoogleCloudPlatform from './_install_additional_dependencies/_google_cloud_platform.md'
import InstallSql from './_install_additional_dependencies/_sql.md'

Some environments and Data Sources require additional Python libraries or third party utilities that are not included in the base installation of
{GxData.product_name}. Use the information provided here to install the necessary dependencies for Amazon S3, Azure Blob Storage, Google Cloud Storage, and SQL databases.

<Tabs queryString="dependencies" groupId="additional-dependencies" defaultValue='amazon' values={[{value: 'amazon', label: 'Amazon S3'}, {label: 'Microsoft Azure Blob Storage', value:'azure'}, {label: 'Google Cloud Storage', value:'gcs'}, {label: 'SQL databases', value:'sql'}]}>

  <TabItem value="amazon" label="Amazon S3">
<InstallAmazon/>
  </TabItem>

  <TabItem value="azure">
<InstallAzureBlobStorage/>
  </TabItem>

  <TabItem value="gcs">
<InstallGoogleCloudPlatform/>
  </TabItem>

  <TabItem value="sql">
<InstallSql/>
  </TabItem>

</Tabs>

## Next steps

<Tabs className="hidden" queryString="dependencies" groupId="additional-dependencies" defaultValue='amazon' values={[{value: 'amazon', label: 'Amazon S3'}, {label: 'Microsoft Azure Blob Storage', value:'azure'}, {label: 'Google Cloud Storage', value:'gcs'}, {label: 'SQL databases', value:'sql'}]}>

<TabItem value="amazon" label="Amazon S3">

- [Manage Data Contexts](/core/installation_and_setup/manage_data_contexts.md)

</TabItem>

<TabItem value="azure">

- [Manage Data Contexts](/core/installation_and_setup/manage_data_contexts.md)

</TabItem>

<TabItem value="gcs">

- [Manage Data Contexts](/core/installation_and_setup/manage_data_contexts.md)

</TabItem>

<TabItem value="sql">

- [Manage Data Contexts](/core/installation_and_setup/manage_data_contexts.md)

</TabItem>

</Tabs>
