**What is Azure Update Maanger?**
Azure Update Manager is a unified service to help manage and govern updates for all your machines that run a server operating system. With Update Manager, you can monitor Windows and Linux update compliance across your machines in Azure, on-premises, or in other cloud environments (connected by Azure Arc) from a single pane of management. You can also use Update Manager to make real-time updates or schedule updates within a defined maintenance window.

**Features**

**Unified update management:** Monitor update compliance across Windows and Linux servers from a single dashboard.

**Flexible patching options:**

Schedule updates within customer-defined maintenance for both Azure virtual machines (VMs) and Azure Arc-connected machines.
Apply updates in real time.
Use automatic guest patching to automatically apply updates to Azure VMs without requiring manual intervention.
Use hotpatching to apply critical updates to Azure VMs without requiring a restart, minimizing downtime.
Security and compliance tracking: Apply security and critical patches with enhanced security measures and compliance tracking.

**Periodic update assessments:** Enable periodic assessments to check for updates every 24 hours.

**Dynamic scoping:** Group machines based on criteria and apply updates at scale.

**Granular access control:** Use role-based access control (RBAC) to delegate permissions for patch management tasks at a per-resource level.

**Software updates, including application updates:**

Apply updates that are available in Microsoft Update.
Apply updates that are available in Linux packages.
Apply updates that are published to Windows Server Update Services (WSUS).

**Patching diverse resources:**

Patch Windows and Linux VMs in Azure (including SQL servers).
Patch hybrid machines, including deployments of SQL Server enabled by Azure Arc and Windows IoT Enterprise on Azure Arc-enabled servers.
Patch Azure Local clusters.
Perform cross-subscription patching.
**Reports:**

Build custom reporting dashboards through Azure Workbooks to monitor the update compliance of your infrastructure.
These features make Update Manager a powerful tool for maintaining the security and performance of your IT infrastructure.


**Key benefits**
Here are some of the benefits of Update Manager:

**Provides native experience with zero onboarding:**

Built as native functionality on Azure VMs and Azure Arc-enabled servers for ease of use.
No dependency on Log Analytics and Azure Automation.
Azure Policy support.
Available in most Azure VMs and Azure Arc regions.

**Works with Azure roles and identity:**

Granular access control at per-resource level instead of access control at the level of the Azure Automation account and Log Analytics workspace.
Azure Resource Manager-based operations. Update Manager allows role-based access control and roles based on Resource Manager in Azure.
Enhanced flexibility:
Take immediate action by either installing updates immediately or scheduling them for a later date.
Check updates automatically or on demand.
Secure machines with new ways of patching, such as automatic VM guest patching in Azure, hotpatching, or custom maintenance schedules.
Sync patch cycles in relation to patch Tuesday, the unofficial term for Microsoft's scheduled release of security fixes on the second Tuesday of each month.

