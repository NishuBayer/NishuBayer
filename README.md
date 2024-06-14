### Detailed Points on Selected Topics

#### 1. File Transfer -- **Ongoing** PGP Key for File Transfers to be Replaced

- **Overview:**
  - SAP Concur will replace the current PGP key (ID 9AFF10B5) used for encrypting files transferred to their solutions.
  - The new PGP key (ID 8C51C89E) will be available by May 24, 2024.
  - The current key will expire on September 4, 2024, and should not be used after this date.

- **Key Details:**
  - Clients must migrate to the new PGP key before the expiration of the current key.
  - The new PGP key can be retrieved from the client’s root folder under the file name `concursolutions.asc`.
  - If clients cannot migrate in time, they can manually upload files using the Import / Extract Monitor feature.

- **Admin Instructions:**
  - Administrators should log into the file transfer site to retrieve the new public PGP key.
  - The new key should be added to the internal PGP keyring for continued encrypted file transfers.
  - Assistance can be sought from SAP Concur support if needed.

- **References:**
  - For more information, refer to the "Shared: File Transfer for Customers and Vendors User Guide."
  - Detailed migration steps will be provided in the June 2024 release notes.

#### 2. Planned Changes -- Annual Certificate Renewal -- **Planned Changes** New SSL certificate for *.concursolutions.com and *api.concursolutions.com

- **Overview:**
  - SAP Concur will update the SSL certificates for `*.concursolutions.com` and `*.api.concursolutions.com`.
  - These updates are part of the regular annual renewal process to ensure ongoing security.

- **Key Dates:**
  - The new SSL certificate for `*.concursolutions.com` will be issued on June 20, 2024.
  - The new SSL certificate for `*.api.concursolutions.com` will be issued on July 25, 2024.
  - The current certificates will expire on July 11, 2024 (`*.concursolutions.com`) and August 11, 2024 (`*.api.concursolutions.com`).

- **Client Action:**
  - Clients who have pinned the current SSL certificates must update to the new certificates before the issuance dates.
  - Most clients do not pin certificates and hence will not need to take any action.

- **Recommendations:**
  - Certificate pinning is not recommended due to the risk of service disruption if not updated in time.
  - If unsure about certificate pinning, clients should consult their IT departments.

- **References:**
  - Clients can obtain the new certificates from the specified SAP Concur web pages for both `*.concursolutions.com` and `*.api.concursolutions.com`.
  - Further details are available in SAP Note 2914977 - FAQ: Concur Certificates, Authentication, and Connectivity.

#### 3. File Transfer -- **Planned Changes** New IP Addresses for DNS Endpoints

- **Overview:**
  - SAP Concur will introduce new IP addresses for DNS endpoints used in file transfers.

- **Implementation:**
  - This change is planned to enhance security and improve the reliability of file transfers.
  - The specific new IP addresses and their deployment schedule will be provided closer to the implementation date.

- **Client Action:**
  - Clients should ensure their firewall and network configurations allow connections to the new IP addresses once they are released.
  - IT departments should be informed to prepare for these changes.

- **References:**
  - Detailed instructions and the list of new IP addresses will be communicated in subsequent release notes or technical documentation updates.

#### 4. SAP Concur -- **Planned Changes** New SAP Concur Outbound IP Addresses to be Added

- **Overview:**
  - New outbound IP addresses will be added to SAP Concur’s infrastructure.

- **Implementation:**
  - This addition aims to support enhanced performance and increased capacity for outbound connections from SAP Concur.

- **Client Action:**
  - Clients need to update their network and security configurations to accommodate the new outbound IP addresses.
  - Ensure that these new IP addresses are whitelisted to avoid disruption in service.

- **References:**
  - Further details including the specific IP addresses and implementation timelines will be shared in future release notes.
  - Clients should monitor upcoming updates for precise information and necessary actions.

These details summarize the selected topics from the May 2024 SAP Concur release notes, providing specific action points and timelines for administrators and IT departments.
