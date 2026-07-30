# Reference
## AuthLinks
<details><summary><code>client.authLinks.<a href="/src/api/resources/authLinks/client/Client.ts">getTaxesPage</a>({ ...params }) -> ZealApi.GetTaxesPageAuthLinksResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Generates an authenticated link that can be hosted as a UI component for the Company Taxes Page.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.authLinks.getTaxesPage({
    partnerID: "c133ecdere9b3445a2f22Cc258b23445a",
    companyID: "fc235f012bae46222ca3444cc2215bcfa",
    showSidebar: true
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.GetTaxesPageAuthLinksRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AuthLinksClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.authLinks.<a href="/src/api/resources/authLinks/client/Client.ts">company</a>({ ...params }) -> ZealApi.CompanyAuthLinksResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Generates a link that automatically signs in an employer into their Zeal Company Dashboard.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.authLinks.company({
    partnerID: "c133ecdere9b3445a2f22Cc258b23445a",
    companyID: "fc235f012bae46222ca3444cc2215bcfa"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.CompanyAuthLinksRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AuthLinksClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.authLinks.<a href="/src/api/resources/authLinks/client/Client.ts">getReportsPage</a>({ ...params }) -> ZealApi.GetReportsPageAuthLinksResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Generates a link that signs in an employer to their Zeal Reports Dashboard.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.authLinks.getReportsPage({
    partnerID: "c133eed233c9b8419ba4452cc059bd445a",
    companyID: "fc2ccf012b2342cc342ca082f357715bcfa"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.GetReportsPageAuthLinksRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AuthLinksClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## PaystubLink
<details><summary><code>client.paystubLink.<a href="/src/api/resources/paystubLink/client/Client.ts">get</a>({ ...params }) -> ZealApi.GetPaystubLinkResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Fetches an expirable link that displays an employee paystub.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.paystubLink.get({
    companyID: "companyID",
    employeeCheckID: "employeeCheckID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.GetPaystubLinkRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PaystubLinkClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Companies
<details><summary><code>client.companies.<a href="/src/api/resources/companies/client/Client.ts">list</a>({ ...params }) -> ZealApi.ListCompaniesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Get information for all companies under a partner.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.companies.list({
    partnerID: "partnerID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.ListCompaniesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CompaniesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.companies.<a href="/src/api/resources/companies/client/Client.ts">create</a>({ ...params }) -> ZealApi.CreateCompaniesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Creates a company within Zeal.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.companies.create({
    partnerID: "partnerID",
    first_name: "first_name",
    last_name: "last_name",
    email: "email",
    business_name: "business_name",
    business_ein: "business_ein",
    business_address: "business_address",
    business_city: "business_city",
    business_state: "business_state",
    business_zip: "business_zip",
    business_phone: "business_phone",
    mail_address: "mail_address",
    mail_city: "mail_city",
    mail_state: "mail_state",
    mail_zip: "mail_zip",
    ssn: "ssn",
    ownership_percentage: 1,
    legal_structure: "ccorp",
    dob: "dob",
    address: "address",
    city: "city",
    state: "state",
    zip: "zip"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.CreateCompaniesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CompaniesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.companies.<a href="/src/api/resources/companies/client/Client.ts">update</a>({ ...params }) -> ZealApi.UpdateCompaniesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Update the Company Object
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.companies.update({
    companyID: "companyID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.UpdateCompaniesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CompaniesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.companies.<a href="/src/api/resources/companies/client/Client.ts">getOnboardingLink</a>({ ...params }) -> ZealApi.GetOnboardingLinkCompaniesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Get a link to Zeal's web-based company onboarding.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.companies.getOnboardingLink({
    partnerID: "partnerID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.GetOnboardingLinkCompaniesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CompaniesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.companies.<a href="/src/api/resources/companies/client/Client.ts">createBankAccount</a>({ ...params }) -> ZealApi.CreateBankAccountCompaniesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Creates a bank account for the specified company.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.companies.createBankAccount({
    companyID: "182bb035e9ad422238c5e2cb386e19dd",
    account_number: "12345678",
    routing_number: "021000021"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.CreateBankAccountCompaniesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CompaniesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.companies.<a href="/src/api/resources/companies/client/Client.ts">triggerMicrodeposits</a>({ ...params }) -> ZealApi.TriggerMicrodepositsCompaniesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Trigger Micro-deposits in order to verify a company bank account.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.companies.triggerMicrodeposits({
    companyID: "companyID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.TriggerMicrodepositsCompaniesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CompaniesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.companies.<a href="/src/api/resources/companies/client/Client.ts">verifyMicrodeposits</a>({ ...params }) -> ZealApi.VerifyMicrodepositsCompaniesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Submit Microdeposit values in order to verify a company bank account.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.companies.verifyMicrodeposits({
    companyID: "182bb035e9ad41bea8c5e2cb386e19dd",
    deposits: ["1", "1"]
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.VerifyMicrodepositsCompaniesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CompaniesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.companies.<a href="/src/api/resources/companies/client/Client.ts">getAuthorizationDocuments</a>({ ...params }) -> ZealApi.GetAuthorizationDocumentsCompaniesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Fetch and view Company Authorization Documents.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.companies.getAuthorizationDocuments({
    companyID: "companyID",
    document_key: "8655"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.GetAuthorizationDocumentsCompaniesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CompaniesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.companies.<a href="/src/api/resources/companies/client/Client.ts">createAuthorizationDocuments</a>({ ...params }) -> ZealApi.CreateAuthorizationDocumentsCompaniesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Sign Authorization Documents necessary to onboard a company.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.companies.createAuthorizationDocuments({
    companyID: "238cc39eui4xc873kej94",
    document_key: "8655",
    signature: "WmVhbA=="
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.CreateAuthorizationDocumentsCompaniesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CompaniesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.companies.<a href="/src/api/resources/companies/client/Client.ts">setStatusToOnboarded</a>({ ...params }) -> ZealApi.SetStatusToOnboardedCompaniesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Sets a Company to onboarded if all requirements are met.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.companies.setStatusToOnboarded({
    companyID: "12349eee40588c3948e312ww"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.SetStatusToOnboardedCompaniesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CompaniesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## ProviderAccounts
<details><summary><code>client.providerAccounts.<a href="/src/api/resources/providerAccounts/client/Client.ts">getBalance</a>({ ...params }) -> ZealApi.GetBalanceProviderAccountsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.providerAccounts.getBalance({
    companyID: "companyID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.GetBalanceProviderAccountsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ProviderAccountsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## CustomerAccounts
<details><summary><code>client.customerAccounts.<a href="/src/api/resources/customerAccounts/client/Client.ts">list</a>({ ...params }) -> ZealApi.ListCustomerAccountsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customerAccounts.list({
    companyID: "companyID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.ListCustomerAccountsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CustomerAccountsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customerAccounts.<a href="/src/api/resources/customerAccounts/client/Client.ts">create</a>({ ...params }) -> ZealApi.CreateCustomerAccountsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customerAccounts.create({
    companyID: "dzxzll3b45rtrtrtad41c98bbc2b4d566388a44",
    code: "customer-code10",
    business_name: "Hooli"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.CreateCustomerAccountsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CustomerAccountsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customerAccounts.<a href="/src/api/resources/customerAccounts/client/Client.ts">update</a>({ ...params }) -> ZealApi.UpdateCustomerAccountsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customerAccounts.update({
    id: "id",
    companyID: "dzxzll3b45rtrtrtad41c98bbc2b4d566388a44",
    code: "customer-code-2"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.UpdateCustomerAccountsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CustomerAccountsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customerAccounts.<a href="/src/api/resources/customerAccounts/client/Client.ts">generateOnboardingLink</a>({ ...params }) -> ZealApi.GenerateOnboardingLinkCustomerAccountsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customerAccounts.generateOnboardingLink({
    companyID: "f8c887b155574458971236fef2149c9a",
    customerAccountID: "3f686bf64c144a53bb6e622197546227"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.GenerateOnboardingLinkCustomerAccountsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CustomerAccountsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customerAccounts.<a href="/src/api/resources/customerAccounts/client/Client.ts">setOnboardedToTrue</a>({ ...params }) -> ZealApi.SetOnboardedToTrueCustomerAccountsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customerAccounts.setOnboardedToTrue({
    customerAccountID: "customerAccountID",
    companyID: "12349eee40588c3948e312bb"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.SetOnboardedToTrueCustomerAccountsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CustomerAccountsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customerAccounts.<a href="/src/api/resources/customerAccounts/client/Client.ts">createFundingSource</a>({ ...params }) -> ZealApi.CreateFundingSourceCustomerAccountsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customerAccounts.createFundingSource({
    id: "id",
    account_number: "849201923",
    account_type: "checking",
    routing_number: "314074269",
    companyID: "dzxzll3b45rtrtrtad41c98bbc2b4d566388a44",
    customerAccountID: "23l9ada7ce49eb1496c1cb953e8c"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.CreateFundingSourceCustomerAccountsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CustomerAccountsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customerAccounts.<a href="/src/api/resources/customerAccounts/client/Client.ts">triggerCaMicrodeposits</a>({ ...params }) -> ZealApi.TriggerCaMicrodepositsCustomerAccountsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customerAccounts.triggerCaMicrodeposits({
    customerAccountID: "customerAccountID",
    companyID: "companyID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.TriggerCaMicrodepositsCustomerAccountsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CustomerAccountsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customerAccounts.<a href="/src/api/resources/customerAccounts/client/Client.ts">verifyMicrodeposits</a>({ ...params }) -> ZealApi.VerifyMicrodepositsCustomerAccountsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customerAccounts.verifyMicrodeposits({
    customerAccountID: "customerAccountID",
    companyID: "companyID",
    deposits: ["deposits"]
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.VerifyMicrodepositsCustomerAccountsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CustomerAccountsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customerAccounts.<a href="/src/api/resources/customerAccounts/client/Client.ts">get</a>({ ...params }) -> ZealApi.GetCustomerAccountsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customerAccounts.get({
    customerAccountID: "customerAccountID",
    companyID: "companyID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.GetCustomerAccountsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CustomerAccountsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## TaxableLocations
<details><summary><code>client.taxableLocations.<a href="/src/api/resources/taxableLocations/client/Client.ts">get</a>({ ...params }) -> ZealApi.GetTaxableLocationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Get a taxable location by ID.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.taxableLocations.get({
    taxableLocationID: "taxableLocationID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.GetTaxableLocationsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `TaxableLocationsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.taxableLocations.<a href="/src/api/resources/taxableLocations/client/Client.ts">create</a>({ ...params }) -> ZealApi.CreateTaxableLocationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Create or get a taxable location.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.taxableLocations.create({
    street1: "street1",
    city: "city",
    state: "state",
    zip: "zip"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.CreateTaxableLocationsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `TaxableLocationsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## WorkLocations
<details><summary><code>client.workLocations.<a href="/src/api/resources/workLocations/client/Client.ts">get</a>({ ...params }) -> ZealApi.GetWorkLocationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Fetch Work Location(s) by company and/or specific parameters.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.workLocations.get({
    companyID: "companyID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.GetWorkLocationsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `WorkLocationsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.workLocations.<a href="/src/api/resources/workLocations/client/Client.ts">create</a>({ ...params }) -> ZealApi.CreateWorkLocationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Creates a Work Location for a company within Zeal.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.workLocations.create({
    companyID: "1234567890",
    taxableLocationID: "609ffdf81a5f9c4c10b0c443",
    name: "SF Office",
    work_site_id: "SF"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.CreateWorkLocationsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `WorkLocationsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.workLocations.<a href="/src/api/resources/workLocations/client/Client.ts">update</a>({ ...params }) -> ZealApi.UpdateWorkLocationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Update's a Work Location in Zeal.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.workLocations.update({
    companyID: "24b5b29f07924840b119c34d1351940c",
    workLocationID: "624c898d94de2a0034869f8b",
    name: "Miami Office",
    work_site_id: "MIA"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.UpdateWorkLocationsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `WorkLocationsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Employees
<details><summary><code>client.employees.<a href="/src/api/resources/employees/client/Client.ts">get</a>({ ...params }) -> ZealApi.GetEmployeesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Get a specific employee's information.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.employees.get({
    companyID: "companyID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.GetEmployeesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EmployeesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.employees.<a href="/src/api/resources/employees/client/Client.ts">create</a>({ ...params }) -> unknown</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Create a W-2 employee.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.employees.create({
    companyID: "companyID",
    new_employees: [{
            email: "email",
            first_name: "first_name",
            last_name: "last_name",
            title: "title",
            default_pay_schedule: "default_pay_schedule",
            default_wage: 1.1,
            workLocationID: "workLocationID"
        }]
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.CreateEmployeesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EmployeesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.employees.<a href="/src/api/resources/employees/client/Client.ts">update</a>({ ...params }) -> ZealApi.UpdateEmployeesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Update a specific employee record.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.employees.update({
    companyID: "0987654321",
    employee: {
        employeeID: "employeeID"
    }
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.UpdateEmployeesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EmployeesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.employees.<a href="/src/api/resources/employees/client/Client.ts">uploadGovernmentId</a>({ ...params }) -> ZealApi.UploadGovernmentIdEmployeesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Uploads a government issued ID for a specified employee in Zeal.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.employees.uploadGovernmentId({
    employeeID: "z133222c924yba2f332dc059bd445a",
    companyID: "fccc35f014446aa8a082f357715bcfa",
    id_type: "passport",
    id_base64: "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"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.UploadGovernmentIdEmployeesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EmployeesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.employees.<a href="/src/api/resources/employees/client/Client.ts">generateOnboardingLink</a>({ ...params }) -> ZealApi.GenerateOnboardingLinkEmployeesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Generates an expirable link to Zeal's employee payroll onboarding for a specified employee.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.employees.generateOnboardingLink({
    companyID: "123456789",
    employeeID: "123456789",
    employee_acct: false,
    i9_form: false,
    id_scan: false
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.GenerateOnboardingLinkEmployeesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EmployeesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.employees.<a href="/src/api/resources/employees/client/Client.ts">sendOnboardingLink</a>({ ...params }) -> ZealApi.SendOnboardingLinkEmployeesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Sends an employee onboarding link to the specified employee's email.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.employees.sendOnboardingLink({
    companyID: "1eeec343485723ee58ufefhz",
    employees: [{
            employeeID: "cc4482374ee49487ruzieun",
            profile: false,
            employee_acct: false,
            i9_form: false,
            id_scan: false,
            paperwork: false
        }, {
            employeeID: "dd5582374ee494ccru998eun",
            profile: true,
            employee_acct: false,
            i9_form: false,
            id_scan: false,
            paperwork: false
        }]
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.SendOnboardingLinkEmployeesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EmployeesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.employees.<a href="/src/api/resources/employees/client/Client.ts">getTaxParameterDefinitions</a>({ ...params }) -> ZealApi.GetTaxParameterDefinitionsEmployeesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Retrieve all tax parameters used for withholding calculations.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.employees.getTaxParameterDefinitions({
    jurisdictions: ["CA"]
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.GetTaxParameterDefinitionsEmployeesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EmployeesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.employees.<a href="/src/api/resources/employees/client/Client.ts">setTaxParameters</a>({ ...params }) -> ZealApi.SetTaxParametersEmployeesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Set an employee's tax withholding parameters.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.employees.setTaxParameters({
    employeeID: "employeeID",
    companyID: "companyID",
    federalParameters: [{}]
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.SetTaxParametersEmployeesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EmployeesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.employees.<a href="/src/api/resources/employees/client/Client.ts">getTaxParameters</a>({ ...params }) -> ZealApi.GetTaxParametersEmployeesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Retrieve a list of an employee's tax withholding parameters.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.employees.getTaxParameters({
    employeeID: "employeeID",
    companyID: "companyID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.GetTaxParametersEmployeesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EmployeesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.employees.<a href="/src/api/resources/employees/client/Client.ts">setOnboardedStatusToTrue</a>({ ...params }) -> ZealApi.SetOnboardedStatusToTrueEmployeesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Set an employee as onboarded.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.employees.setOnboardedStatusToTrue({
    employeeID: "62350595e7f1225023b3b824",
    companyID: "24b5b29f07924840b119c34c13522940c"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.SetOnboardedStatusToTrueEmployeesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EmployeesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.employees.<a href="/src/api/resources/employees/client/Client.ts">createProfileInformationCollectionLink</a>({ ...params }) -> ZealApi.CreateProfileInformationCollectionLinkEmployeesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.employees.createProfileInformationCollectionLink({
    companyID: "3f5c2afcc5ea40c87a2c8f3f7e5a1cb1",
    employeeID: "c2fc3a5fe5c74ca08a38f5f7b1a2ec15"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.CreateProfileInformationCollectionLinkEmployeesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EmployeesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.employees.<a href="/src/api/resources/employees/client/Client.ts">createAccountSetupLink</a>({ ...params }) -> ZealApi.CreateAccountSetupLinkEmployeesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.employees.createAccountSetupLink({
    companyID: "3f5c2afcc5ea40c87a2c8f3f7e5a1cb1",
    employeeID: "c2fc3a5fe5c74ca08a38f5f7b1a2ec15"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.CreateAccountSetupLinkEmployeesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EmployeesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.employees.<a href="/src/api/resources/employees/client/Client.ts">createI9Link</a>({ ...params }) -> ZealApi.CreateI9LinkEmployeesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.employees.createI9Link({
    companyID: "1eeec343485723ee58ufefhz",
    employeeID: "cc4482374ee49487ruzieun"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.CreateI9LinkEmployeesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EmployeesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.employees.<a href="/src/api/resources/employees/client/Client.ts">createCustomPaperworkLink</a>({ ...params }) -> ZealApi.CreateCustomPaperworkLinkEmployeesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.employees.createCustomPaperworkLink({
    companyID: "companyID",
    employeeID: "employeeID",
    formTemplateIDs: ["formTemplateIDs"]
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.CreateCustomPaperworkLinkEmployeesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EmployeesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.employees.<a href="/src/api/resources/employees/client/Client.ts">createW4Link</a>({ ...params }) -> ZealApi.CreateW4LinkEmployeesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.employees.createW4Link({
    companyID: "3f5c2afcc5ea40c87a2c8f3f7e5a1cb1",
    employeeID: "c2fc3a5fe5c74ca08a38f5f7b1a2ec15",
    jurisdiction: "CA"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.CreateW4LinkEmployeesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EmployeesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.employees.<a href="/src/api/resources/employees/client/Client.ts">createPaycardEnrollmentLink</a>({ ...params }) -> ZealApi.CreatePaycardEnrollmentLinkEmployeesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.employees.createPaycardEnrollmentLink({
    companyID: "3f5c2afcc5ea40c87a2c8f3f7e5a1cb1",
    employeeID: "c2fc3a5fe5c74ca08a38f5f7b1a2ec15"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.CreatePaycardEnrollmentLinkEmployeesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EmployeesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.employees.<a href="/src/api/resources/employees/client/Client.ts">getI9Status</a>({ ...params }) -> unknown</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Get the status of an I9's completion
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.employees.getI9Status({
    companyID: "companyID",
    employeeID: "employeeID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.GetI9StatusEmployeesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EmployeesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.employees.<a href="/src/api/resources/employees/client/Client.ts">createInstantPayEnrollmentLink</a>({ ...params }) -> ZealApi.CreateInstantPayEnrollmentLinkEmployeesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.employees.createInstantPayEnrollmentLink({
    companyID: "3f5c2afcc5ea40c87a2c8f3f7e5a1cb1",
    employeeID: "c2fc3a5fe5c74ca08a38f5f7b1a2ec15"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.CreateInstantPayEnrollmentLinkEmployeesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EmployeesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.employees.<a href="/src/api/resources/employees/client/Client.ts">createBankAccountLink</a>({ ...params }) -> ZealApi.CreateBankAccountLinkEmployeesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.employees.createBankAccountLink({
    companyID: "3f5c2afcc5ea40c87a2c8f3f7e5a1cb1",
    employeeID: "c2fc3a5fe5c74ca08a38f5f7b1a2ec15"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.CreateBankAccountLinkEmployeesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EmployeesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.employees.<a href="/src/api/resources/employees/client/Client.ts">createIdVerificationLink</a>({ ...params }) -> unknown</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.employees.createIdVerificationLink({
    companyID: "companyID",
    employeeID: "employeeID",
    document_type: ["document_type"]
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.CreateIdVerificationLinkEmployeesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EmployeesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## EmployeeRequirements
<details><summary><code>client.employeeRequirements.<a href="/src/api/resources/employeeRequirements/client/Client.ts">get</a>({ ...params }) -> ZealApi.GetEmployeeRequirementsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Get additional tax requirements for an employee
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.employeeRequirements.get({
    companyID: "companyID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.GetEmployeeRequirementsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EmployeeRequirementsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.employeeRequirements.<a href="/src/api/resources/employeeRequirements/client/Client.ts">getLink</a>({ ...params }) -> ZealApi.GetLinkEmployeeRequirementsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Get links to submit additional tax requirements for an employee. (Early Access - please contact the Zeal team to learn more)
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.employeeRequirements.getLink({
    companyID: "companyID",
    employeeID: "employeeID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.GetLinkEmployeeRequirementsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EmployeeRequirementsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Forms
<details><summary><code>client.forms.<a href="/src/api/resources/forms/client/Client.ts">list</a>() -> ZealApi.ListFormsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.forms.list();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `FormsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.forms.<a href="/src/api/resources/forms/client/Client.ts">getTemplate</a>({ ...params }) -> ZealApi.GetTemplateFormsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.forms.getTemplate({
    media_type: "media_type",
    formTemplateID: "formTemplateID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.GetTemplateFormsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `FormsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.forms.<a href="/src/api/resources/forms/client/Client.ts">get</a>({ ...params }) -> ZealApi.GetFormsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.forms.get({
    media_type: "media_type",
    formID: "formID",
    companyID: "companyID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.GetFormsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `FormsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.forms.<a href="/src/api/resources/forms/client/Client.ts">create</a>({ ...params }) -> unknown</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.forms.create({
    companyID: "23942428ee349ze49545qq33c",
    formTemplateID: "formTemplateID",
    employeeID: "23550cce4984eezeweo4845v"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.CreateFormsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `FormsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Bankaccounts
<details><summary><code>client.bankaccounts.<a href="/src/api/resources/bankaccounts/client/Client.ts">get</a>({ ...params }) -> ZealApi.GetBankaccountsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Retrieve a single bank account object by its Zeal bank account ID.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.bankaccounts.get({
    companyID: "companyID",
    bankAccountID: "bankAccountID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.GetBankaccountsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `BankaccountsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.bankaccounts.<a href="/src/api/resources/bankaccounts/client/Client.ts">create</a>({ ...params }) -> ZealApi.CreateBankaccountsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Create's a bank account for a specified worker in Zeal.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.bankaccounts.create({
    companyID: "fc235fcccee46aa8a082f357715bcfa",
    id: "624ccccca41ba35c05c256a66e",
    institution_name: "Chase",
    account_number: "1243686537",
    routing_number: "267084131",
    type: "checking"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.CreateBankaccountsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `BankaccountsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.bankaccounts.<a href="/src/api/resources/bankaccounts/client/Client.ts">update</a>({ ...params }) -> ZealApi.UpdateBankaccountsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Updates an existing bank account for a specified worker.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.bankaccounts.update({
    companyID: "fc235f012tay46aa8a082f357715bcfa",
    bankAccountID: "61d3f2c3a8593140cda7c5cb",
    account_number: "123124215",
    routing_number: "061092387",
    institution_name: "PNS",
    type: "checking"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.UpdateBankaccountsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `BankaccountsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.bankaccounts.<a href="/src/api/resources/bankaccounts/client/Client.ts">getByWorkerId</a>({ ...params }) -> ZealApi.GetByWorkerIdBankaccountsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Retrieve all bank account objects belonging to a worker (employee or contractor) by their Zeal Employee ID or Contractor ID.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.bankaccounts.getByWorkerId({
    companyID: "companyID",
    id: "id"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.GetByWorkerIdBankaccountsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `BankaccountsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Paperwork
<details><summary><code>client.paperwork.<a href="/src/api/resources/paperwork/client/Client.ts">createEmployee</a>({ ...params }) -> unknown</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

View/sign paperwork for a specified employee and specified jurisdiction.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.paperwork.createEmployee({
    companyID: "55b5b29f07934820b119c34c1358940c",
    employeeID: "6222222ccc8f221f9b0024b6f6c1",
    jurisdiction: "US",
    signature_text: "Base64 Test Signature"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.CreateEmployeePaperworkRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PaperworkClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.paperwork.<a href="/src/api/resources/paperwork/client/Client.ts">getContractor</a>({ ...params }) -> unknown</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

View/sign paperwork for a specified contractor and specified jurisdiction.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.paperwork.getContractor({
    companyID: "55b5b29f07934820b119c34c1358940c",
    contractorID: "6222222ccc8f221f9b0024b6f6c1",
    signature_text: "Base64 test Signature"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.GetContractorPaperworkRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PaperworkClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.paperwork.<a href="/src/api/resources/paperwork/client/Client.ts">createTemplates</a>({ ...params }) -> ZealApi.CreateTemplatesPaperworkResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Gets one or more Paperwork Template(s) by companyID or various filters.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.paperwork.createTemplates({
    companyID: "companyID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.CreateTemplatesPaperworkRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PaperworkClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.paperwork.<a href="/src/api/resources/paperwork/client/Client.ts">getTemplates</a>({ ...params }) -> ZealApi.GetTemplatesPaperworkResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Fetches a specified Paperwork Template by templateID.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.paperwork.getTemplates({
    templateID: "templateID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.GetTemplatesPaperworkRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PaperworkClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.paperwork.<a href="/src/api/resources/paperwork/client/Client.ts">createSubmissions</a>({ ...params }) -> ZealApi.CreateSubmissionsPaperworkResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Gets one or more Paperwork Submission(s) by companyID or various filters.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.paperwork.createSubmissions({
    companyID: "companyID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.CreateSubmissionsPaperworkRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PaperworkClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.paperwork.<a href="/src/api/resources/paperwork/client/Client.ts">updateSubmissions</a>({ ...params }) -> ZealApi.UpdateSubmissionsPaperworkResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Create a Paperwork Submission(s) for an employee or contractor from a Paperwork Template.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.paperwork.updateSubmissions({
    templateID: "templateID",
    worker_type: "Employee",
    companyID: "companyID",
    fields: {
        "key": "value"
    }
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.UpdateSubmissionsPaperworkRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PaperworkClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.paperwork.<a href="/src/api/resources/paperwork/client/Client.ts">getSubmissions</a>({ ...params }) -> ZealApi.GetSubmissionsPaperworkResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Gets a specific Paperwork Submission(s) by its submissionID.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.paperwork.getSubmissions({
    submissionID: "submissionID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.GetSubmissionsPaperworkRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PaperworkClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## ReportingPeriod
<details><summary><code>client.reportingPeriod.<a href="/src/api/resources/reportingPeriod/client/Client.ts">get</a>({ ...params }) -> ZealApi.GetReportingPeriodResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.reportingPeriod.get({
    companyID: "companyID",
    reportingPeriodID: "reportingPeriodID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.GetReportingPeriodRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ReportingPeriodClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reportingPeriod.<a href="/src/api/resources/reportingPeriod/client/Client.ts">list</a>({ ...params }) -> ZealApi.ListReportingPeriodResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.reportingPeriod.list({
    companyID: "companyID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.ListReportingPeriodRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ReportingPeriodClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## EmployeeChecks
<details><summary><code>client.employeeChecks.<a href="/src/api/resources/employeeChecks/client/Client.ts">get</a>({ ...params }) -> unknown</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.employeeChecks.get({
    companyID: "companyID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.GetEmployeeChecksRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EmployeeChecksClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.employeeChecks.<a href="/src/api/resources/employeeChecks/client/Client.ts">create</a>({ ...params }) -> ZealApi.CreateEmployeeChecksResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Create a check for an employee.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.employeeChecks.create({
    companyID: "fc235f012bae46aa8a082f347715bcfa",
    employeeID: "62547a2228a58200241e2b42",
    reportingPeriodID: "61d5533c8fc6b7af3bfc2ff3",
    check_date: "2022-02-15",
    approval_required: true,
    disbursement: {
        method: "direct_deposit"
    },
    shifts: [{
            time: "2022-02-10T00:00:00Z",
            hourly: {
                hours: 20,
                wage: 30
            }
        }]
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.CreateEmployeeChecksRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EmployeeChecksClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.employeeChecks.<a href="/src/api/resources/employeeChecks/client/Client.ts">delete</a>({ ...params }) -> string</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Delete a pending employee check.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.employeeChecks.delete({
    companyID: "companyID",
    employeeCheckID: "employeeCheckID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.DeleteEmployeeChecksRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EmployeeChecksClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.employeeChecks.<a href="/src/api/resources/employeeChecks/client/Client.ts">update</a>({ ...params }) -> ZealApi.UpdateEmployeeChecksResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Update a pending employee check.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.employeeChecks.update({
    companyID: "companyID",
    employeeCheckID: "employeeCheckID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.UpdateEmployeeChecksRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EmployeeChecksClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.employeeChecks.<a href="/src/api/resources/employeeChecks/client/Client.ts">createBulk</a>({ ...params }) -> ZealApi.CreateBulkEmployeeChecksResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Create a batch of employee checks.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.employeeChecks.createBulk({
    companyID: "fc235fcc12ae4c6cce4082f357715bcfa",
    employeeChecks: [{
            employeeID: "6cc3cc3f37c91f5f123c25cde490e",
            reportingPeriodID: "235ccd0c9291f5f2b00c25de490e",
            check_date: "2024-03-27",
            approval_required: true,
            shifts: [{
                    time: "2024-03-27T19:38:55Z",
                    hourly: {
                        hours: 5,
                        wage: 40,
                        custom_name: "example"
                    }
                }]
        }, {
            employeeID: "5cc33f3791f52325d2e490e",
            reportingPeriodID: "235cd09291f5f2b0025de490e",
            check_date: "2022-09-27",
            approval_required: true,
            shifts: [{
                    time: "2024-03-27T19:38:55Z",
                    hourly: {
                        hours: 4,
                        wage: 20,
                        custom_name: "example"
                    }
                }]
        }]
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.CreateBulkEmployeeChecksRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EmployeeChecksClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Paystub
<details><summary><code>client.paystub.<a href="/src/api/resources/paystub/client/Client.ts">downloadPdf</a>({ ...params }) -> unknown</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Download an employee's paystub in PDF.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.paystub.downloadPdf({
    companyID: "companyID",
    employeeCheckID: "employeeCheckID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.DownloadPdfPaystubRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PaystubClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Payroll
<details><summary><code>client.payroll.<a href="/src/api/resources/payroll/client/Client.ts">setup</a>({ ...params }) -> ZealApi.SetupPayrollResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.payroll.setup({
    companyID: "companyID",
    firstCheckDate: "2023-01-15",
    paySchedule: "daily",
    reportingPeriodID: "reportingPeriodID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.SetupPayrollRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PayrollClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.payroll.<a href="/src/api/resources/payroll/client/Client.ts">getUpcomingRegular</a>({ ...params }) -> ZealApi.GetUpcomingRegularPayrollResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Get the upcoming “regularly” scheduled check date for the company and associated reporting period information.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.payroll.getUpcomingRegular({
    companyID: "companyID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.GetUpcomingRegularPayrollRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PayrollClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## DeductionTemplate
<details><summary><code>client.deductionTemplate.<a href="/src/api/resources/deductionTemplate/client/Client.ts">getDefinitions</a>({ ...params }) -> ZealApi.GetDefinitionsDeductionTemplateResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Get a definition for a deduction template.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.deductionTemplate.getDefinitions({
    deduction_type: "401k"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.GetDefinitionsDeductionTemplateRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `DeductionTemplateClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.deductionTemplate.<a href="/src/api/resources/deductionTemplate/client/Client.ts">get</a>({ ...params }) -> ZealApi.GetDeductionTemplateResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Get a deduction template.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.deductionTemplate.get({
    companyID: "companyID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.GetDeductionTemplateRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `DeductionTemplateClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.deductionTemplate.<a href="/src/api/resources/deductionTemplate/client/Client.ts">create</a>({ ...params }) -> ZealApi.CreateDeductionTemplateResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Create a deduction template.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.deductionTemplate.create({
    companyID: "fc235f012baa12312asdasdaseda",
    custom_name: "Zeal Testing 401k",
    deduction_type: "401k",
    employee_contribution: {
        override_type: "overridable",
        contribution_type: "dollars",
        value: 20
    },
    employer_contribution: {
        override_type: "overridable",
        contribution_type: "dollars",
        value: 30
    }
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.CreateDeductionTemplateRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `DeductionTemplateClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Deductions
<details><summary><code>client.deductions.<a href="/src/api/resources/deductions/client/Client.ts">get</a>({ ...params }) -> ZealApi.GetDeductionsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Get a specific deduction.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.deductions.get({
    deductionID: "deductionID",
    companyID: "companyID",
    employeeCheckID: "employeeCheckID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.GetDeductionsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `DeductionsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.deductions.<a href="/src/api/resources/deductions/client/Client.ts">create</a>({ ...params }) -> ZealApi.CreateDeductionsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Create a deduction.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.deductions.create({
    companyID: "fc235f012bae46aa8a082f3",
    employeeCheckID: "7f0da5e428324c049ae6a6bac2e62f88",
    deductionTemplateID: "61d12e74db7df700237de5d4",
    deduction: {
        employee_contribution: {
            value: 1.33
        },
        employer_contribution: {
            value: 2.66
        }
    }
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.CreateDeductionsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `DeductionsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.deductions.<a href="/src/api/resources/deductions/client/Client.ts">delete</a>({ ...params }) -> ZealApi.DeleteDeductionsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Delete a deduction.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.deductions.delete({
    companyID: "fc235f012bae46aa8a082f3",
    deductionID: "61d32bb356fdba0023fafa57",
    employeeCheckID: "7f0da5e428324c049ae6a6bac2e62f88"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.DeleteDeductionsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `DeductionsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.deductions.<a href="/src/api/resources/deductions/client/Client.ts">update</a>({ ...params }) -> ZealApi.UpdateDeductionsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Update a deduction.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.deductions.update({
    companyID: "fc235f012bae46aa8a082f3",
    employeeCheckID: "7f0da5e428324c049ae6a6bac2e62f88",
    deductionID: "61d12e74db7df700237de5d4",
    deduction: [{}]
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.UpdateDeductionsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `DeductionsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Shifts
<details><summary><code>client.shifts.<a href="/src/api/resources/shifts/client/Client.ts">get</a>({ ...params }) -> ZealApi.GetShiftsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.shifts.get({
    companyID: "companyID",
    shiftID: "shiftID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.GetShiftsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ShiftsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.shifts.<a href="/src/api/resources/shifts/client/Client.ts">create</a>({ ...params }) -> unknown</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.shifts.create({
    shifts: [{
            time: "2023-03-29T00:00:00Z",
            hourly: {
                hours: 10,
                wage: 33,
                custom_name: "hourly"
            }
        }],
    companyID: "fc235f092bwe46aa8a082f357715bcfa",
    employeeCheckID: "f251842623e942d6bab6ad2bca436d95"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.CreateShiftsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ShiftsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.shifts.<a href="/src/api/resources/shifts/client/Client.ts">delete</a>({ ...params }) -> ZealApi.DeleteShiftsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.shifts.delete({
    companyID: "companyID",
    shiftID: "shiftID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.DeleteShiftsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ShiftsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.shifts.<a href="/src/api/resources/shifts/client/Client.ts">update</a>({ ...params }) -> unknown</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.shifts.update({
    companyID: "ccf239880ccmneu847zefze84",
    shifts: ["shifts"]
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.UpdateShiftsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ShiftsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Paycards
<details><summary><code>client.paycards.<a href="/src/api/resources/paycards/client/Client.ts">get</a>({ ...params }) -> unknown</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.paycards.get({
    companyID: "companyID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.GetPaycardsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PaycardsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Card
<details><summary><code>client.card.<a href="/src/api/resources/card/client/Client.ts">get</a>({ ...params }) -> ZealApi.GetCardResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.card.get({
    companyID: "companyID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.GetCardRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CardClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Wallet
<details><summary><code>client.wallet.<a href="/src/api/resources/wallet/client/Client.ts">get</a>({ ...params }) -> ZealApi.GetWalletResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.wallet.get({
    companyID: "companyID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.GetWalletRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `WalletClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.wallet.<a href="/src/api/resources/wallet/client/Client.ts">createTransfer</a>({ ...params }) -> ZealApi.CreateTransferWalletResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.wallet.createTransfer({
    companyID: "companyID",
    amount: 1.1
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.CreateTransferWalletRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `WalletClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.wallet.<a href="/src/api/resources/wallet/client/Client.ts">getTransactions</a>({ ...params }) -> ZealApi.GetTransactionsWalletResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.wallet.getTransactions({
    companyID: "companyID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.GetTransactionsWalletRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `WalletClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## DirectPayments
<details><summary><code>client.directPayments.<a href="/src/api/resources/directPayments/client/Client.ts">get</a>({ ...params }) -> ZealApi.GetDirectPaymentsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.directPayments.get({
    companyID: "companyID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.GetDirectPaymentsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `DirectPaymentsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.directPayments.<a href="/src/api/resources/directPayments/client/Client.ts">create</a>({ ...params }) -> ZealApi.CreateDirectPaymentsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.directPayments.create({
    companyID: "companyID",
    amount: "amount"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.CreateDirectPaymentsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `DirectPaymentsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## EmployerCheck
<details><summary><code>client.employerCheck.<a href="/src/api/resources/employerCheck/client/Client.ts">list</a>({ ...params }) -> ZealApi.ListEmployerCheckResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.employerCheck.list({
    companyID: "companyID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.ListEmployerCheckRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EmployerCheckClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Preview
<details><summary><code>client.preview.<a href="/src/api/resources/preview/client/Client.ts">createPayrollByCheckid</a>({ ...params }) -> ZealApi.CreatePayrollByCheckidPreviewResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preview.createPayrollByCheckid({
    companyID: "h0c56cc41q1040ac8a3322342a3bbb462",
    checks: ["c614c5ff59d7cc22eae4c9442f315", "22cdbd897e3345a55c3fa22b1712be52", "3942348bd453410485cd783ef1ce8391"]
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.CreatePayrollByCheckidPreviewRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PreviewClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.preview.<a href="/src/api/resources/preview/client/Client.ts">createPayrollByCheckDate</a>({ ...params }) -> ZealApi.CreatePayrollByCheckDatePreviewResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preview.createPayrollByCheckDate({
    companyID: "fcce6cc41440ac8a33e13223bbb462",
    check_date: "2023-04-29T18:21:28.951Z"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.CreatePayrollByCheckDatePreviewRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PreviewClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.preview.<a href="/src/api/resources/preview/client/Client.ts">createCheckData</a>({ ...params }) -> ZealApi.CreateCheckDataPreviewResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preview.createCheckData({
    companyID: "232414e556443cvc34558vv",
    employeeID: "3412eee0494585vvrt39485",
    reportingPeriodID: "5b3948753ere93484c",
    check_date: "2023-12-24",
    deductions: {
        deductionTemplateID: "deductionTemplateID"
    },
    shifts: [{
            time: "2023-11-15T00:00:00Z"
        }, {
            time: "2023-11-15T00:00:00Z"
        }, {
            time: "2023-11-15T00:00:00Z"
        }]
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.CreateCheckDataPreviewRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PreviewClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.preview.<a href="/src/api/resources/preview/client/Client.ts">get</a>({ ...params }) -> ZealApi.GetPreviewResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preview.get({
    job_id: "job_id"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.GetPreviewRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PreviewClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.preview.<a href="/src/api/resources/preview/client/Client.ts">getAvailableDate</a>({ ...params }) -> ZealApi.GetAvailableDatePreviewResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preview.getAvailableDate({
    companyID: "companyID",
    speed: "speed",
    disbursement_method: "disbursement_method"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.GetAvailableDatePreviewRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PreviewClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.preview.<a href="/src/api/resources/preview/client/Client.ts">createOvertimeChecks</a>({ ...params }) -> ZealApi.CreateOvertimeChecksPreviewResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.preview.createOvertimeChecks({
    companyID: "companyID",
    checks: ["checks"]
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.CreateOvertimeChecksPreviewRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PreviewClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## MinimumWageRules
<details><summary><code>client.minimumWageRules.<a href="/src/api/resources/minimumWageRules/client/Client.ts">get</a>({ ...params }) -> ZealApi.GetMinimumWageRulesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Fetches Minimum Wage Rules for a specified Work Location.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.minimumWageRules.get({
    workLocationID: "workLocationID",
    companyID: "companyID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.GetMinimumWageRulesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `MinimumWageRulesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## AccrualPolicy
<details><summary><code>client.accrualPolicy.<a href="/src/api/resources/accrualPolicy/client/Client.ts">get</a>({ ...params }) -> ZealApi.GetAccrualPolicyResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.accrualPolicy.get({
    companyID: "companyID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.GetAccrualPolicyRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AccrualPolicyClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.accrualPolicy.<a href="/src/api/resources/accrualPolicy/client/Client.ts">create</a>({ ...params }) -> ZealApi.CreateAccrualPolicyResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.accrualPolicy.create({
    companyID: "123er534efrerwwe3444e",
    policy_code: "001",
    policy_type: "pto",
    policy_name: "test name",
    policy_effective_date: "2023-03-01",
    accrual_rate_hours: 10,
    accrual_period_hours: 40,
    immediate_balance: 0,
    include_doubletime: true,
    include_overtime: true,
    accrual_waiting_period: 0,
    accrual_cap: 40,
    rollover_cap: 40,
    rollover_date: "01-01"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.CreateAccrualPolicyRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AccrualPolicyClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.accrualPolicy.<a href="/src/api/resources/accrualPolicy/client/Client.ts">update</a>({ ...params }) -> ZealApi.UpdateAccrualPolicyResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.accrualPolicy.update({
    companyID: "123er534efrerwwe3444e",
    policy_code: "001",
    policy_type: "pto",
    policy_effective_date: "2023-03-01",
    accrual_rate_hours: 10,
    accrual_period_hours: 40,
    immediate_balance: 50,
    include_doubletime: true,
    include_overtime: true,
    accrual_waiting_period: 0,
    accrual_cap: 50,
    rollover_cap: 90,
    rollover_date: "01-01",
    policy_status: "live"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.UpdateAccrualPolicyRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AccrualPolicyClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.accrualPolicy.<a href="/src/api/resources/accrualPolicy/client/Client.ts">addOrRemoveEmployees</a>({ ...params }) -> ZealApi.AddOrRemoveEmployeesAccrualPolicyResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.accrualPolicy.addOrRemoveEmployees({
    companyID: "cc3344747eee494857rrc9458nb3948",
    policy_code: "001",
    add_employees: ["3343eree4394785ec3334cc"],
    remove_employees: ["remove_employees"]
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.AddOrRemoveEmployeesAccrualPolicyRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AccrualPolicyClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.accrualPolicy.<a href="/src/api/resources/accrualPolicy/client/Client.ts">addUsage</a>({ ...params }) -> unknown</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Manage usage amounts for employees based on specific accrual policies within a company
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.accrualPolicy.addUsage({
    policyCode: "policyCode",
    companyID: "6181b78dba4\u00A3479c8dc23f046b32bc28",
    employees: [{
            employeeID: "66c7738bbabb2213d7628c02",
            start_date: "2024-12-10",
            end_date: "2024-12-11",
            amount: 4
        }]
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.AddUsageAccrualPolicyRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AccrualPolicyClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## SickTimeCompliance
<details><summary><code>client.sickTimeCompliance.<a href="/src/api/resources/sickTimeCompliance/client/Client.ts">get</a>({ ...params }) -> ZealApi.GetSickTimeComplianceResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.sickTimeCompliance.get({
    state: "state"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.GetSickTimeComplianceRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `SickTimeComplianceClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## AccrualBalance
<details><summary><code>client.accrualBalance.<a href="/src/api/resources/accrualBalance/client/Client.ts">get</a>({ ...params }) -> ZealApi.GetAccrualBalanceResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.accrualBalance.get({
    companyID: "companyID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.GetAccrualBalanceRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AccrualBalanceClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.accrualBalance.<a href="/src/api/resources/accrualBalance/client/Client.ts">update</a>({ ...params }) -> ZealApi.UpdateAccrualBalanceResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.accrualBalance.update({
    companyID: "cc3344747eee494857rrc9458nb3948",
    policy_code: "001",
    employees: [{
            employeeID: "3578439f85h4",
            accrual_balance: 40
        }, {
            employeeID: "y54vy54y5b4y",
            accrual_balance: 35
        }]
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.UpdateAccrualBalanceRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AccrualBalanceClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.accrualBalance.<a href="/src/api/resources/accrualBalance/client/Client.ts">getHistory</a>({ ...params }) -> ZealApi.GetHistoryAccrualBalanceResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

View accrual balance history specific filters within a company
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.accrualBalance.getHistory({
    companyID: "companyID",
    policyCode: "policyCode",
    employeeIDs: ["employeeIDs"],
    endDate: "2023-01-15"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.GetHistoryAccrualBalanceRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AccrualBalanceClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Contractors
<details><summary><code>client.contractors.<a href="/src/api/resources/contractors/client/Client.ts">get</a>({ ...params }) -> ZealApi.GetContractorsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Request key information from The Contractor Object
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.contractors.get({
    companyID: "companyID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.GetContractorsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ContractorsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.contractors.<a href="/src/api/resources/contractors/client/Client.ts">create</a>({ ...params }) -> ZealApi.CreateContractorsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.contractors.create({
    companyID: "1weertirur238eec39482",
    new_contractors: [{
            email: "erlich@zeal.com",
            working_state: "CA",
            first_name: "Erlich",
            last_name: "Bachman",
            dob: "1998-05-05",
            type: "s_corporation",
            ein: "098765432",
            business_name: "Aviato"
        }]
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.CreateContractorsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ContractorsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.contractors.<a href="/src/api/resources/contractors/client/Client.ts">update</a>({ ...params }) -> unknown</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.contractors.update({
    companyID: "1b5n28nrideucd24",
    contractor: {
        contractorID: "contractorID"
    }
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.UpdateContractorsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ContractorsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.contractors.<a href="/src/api/resources/contractors/client/Client.ts">uploadGovernmentId</a>({ ...params }) -> ZealApi.UploadGovernmentIdContractorsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.contractors.uploadGovernmentId({
    contractorID: "618036cbee0d53002343911b",
    companyID: "fc23jk12bae46aa8a082f3577eacfa",
    id_type: "passport",
    id_base64: "iVBORw23goAAAANSUhEUgAAAtsAAABdCAYAAAB0Bq"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.UploadGovernmentIdContractorsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ContractorsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.contractors.<a href="/src/api/resources/contractors/client/Client.ts">createPaycardEnrollmentLink</a>({ ...params }) -> ZealApi.CreatePaycardEnrollmentLinkContractorsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.contractors.createPaycardEnrollmentLink({
    companyID: "3f5c2afcc5ea40c87a2c8f3f7e5a1cb1",
    contractorID: "d2fc3a5fe5c34ca08a38f5f7b1a2eb39"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.CreatePaycardEnrollmentLinkContractorsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ContractorsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.contractors.<a href="/src/api/resources/contractors/client/Client.ts">postAvailablePay</a>({ ...params }) -> ZealApi.PostAvailablePayContractorsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.contractors.postAvailablePay({
    companyID: "3f5c2afcc5ea40c87a2c8f3f7e5a1cb1",
    contractorID: "d2fc3a5fe5c34ca08a38f5f7b1a2eb39"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.PostAvailablePayContractorsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ContractorsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.contractors.<a href="/src/api/resources/contractors/client/Client.ts">getOnboardingLink</a>({ ...params }) -> ZealApi.GetOnboardingLinkContractorsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Generate a secure onboarding link for a contractor.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.contractors.getOnboardingLink({
    companyID: "eeeee434343553413eccc34534",
    contractorID: "874759t85785745748e3847"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.GetOnboardingLinkContractorsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ContractorsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.contractors.<a href="/src/api/resources/contractors/client/Client.ts">createIdVerificationLink</a>({ ...params }) -> ZealApi.CreateIdVerificationLinkContractorsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Creates a shareable link for contractors to submit their ID verification information when they receive an id_verification_required status.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.contractors.createIdVerificationLink({
    companyID: "company_123",
    contractorID: "contractor_456",
    send_to_worker: false,
    document_type: ["document_type"]
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.CreateIdVerificationLinkContractorsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ContractorsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.contractors.<a href="/src/api/resources/contractors/client/Client.ts">createInstantPayEnrollmentLink</a>({ ...params }) -> unknown</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.contractors.createInstantPayEnrollmentLink({
    companyID: "companyID",
    contractorID: "contractorID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.CreateInstantPayEnrollmentLinkContractorsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ContractorsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.contractors.<a href="/src/api/resources/contractors/client/Client.ts">setOnboardedStatusToTrue</a>({ ...params }) -> ZealApi.SetOnboardedStatusToTrueContractorsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Set onboarded status to true if the contractor has all legally required information.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.contractors.setOnboardedStatusToTrue({
    contractorID: "contractorID",
    companyID: "companyID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.SetOnboardedStatusToTrueContractorsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ContractorsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## ContractorPayment
<details><summary><code>client.contractorPayment.<a href="/src/api/resources/contractorPayment/client/Client.ts">get</a>({ ...params }) -> unknown</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.contractorPayment.get({
    companyID: "companyID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.GetContractorPaymentRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ContractorPaymentClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.contractorPayment.<a href="/src/api/resources/contractorPayment/client/Client.ts">create</a>({ ...params }) -> ZealApi.CreateContractorPaymentResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.contractorPayment.create({
    companyID: "24b5b29f05234840b119c34c1358940c",
    contractorID: "62350595e7f1222323b3b824",
    approval_required: false,
    pay_date: "2023-07-25",
    amount: 21,
    disbursement: {
        method: "prepaid"
    }
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.CreateContractorPaymentRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ContractorPaymentClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.contractorPayment.<a href="/src/api/resources/contractorPayment/client/Client.ts">delete</a>({ ...params }) -> ZealApi.DeleteContractorPaymentResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.contractorPayment.delete({
    companyID: "companyID",
    contractorPaymentID: "contractorPaymentID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.DeleteContractorPaymentRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ContractorPaymentClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.contractorPayment.<a href="/src/api/resources/contractorPayment/client/Client.ts">update</a>({ ...params }) -> ZealApi.UpdateContractorPaymentResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.contractorPayment.update({
    companyID: "companyID",
    contractorPaymentID: "contractorPaymentID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.UpdateContractorPaymentRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ContractorPaymentClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.contractorPayment.<a href="/src/api/resources/contractorPayment/client/Client.ts">triggerDisbursement</a>({ ...params }) -> ZealApi.TriggerDisbursementContractorPaymentResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.contractorPayment.triggerDisbursement({
    companyID: "24b5b29f05234840b119c34c1358940c",
    contractorPaymentID: "62350595e7f1222323b3b824"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.TriggerDisbursementContractorPaymentRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ContractorPaymentClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Reports
<details><summary><code>client.reports.<a href="/src/api/resources/reports/client/Client.ts">createPayrollJournal</a>({ ...params }) -> ZealApi.CreatePayrollJournalReportsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Create a payroll journal report.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.reports.createPayrollJournal({
    start_date: "2022-01-01",
    end_date: "2022-03-28",
    companyID: "fc235f012bae46aa8a082f357715bcfa",
    media_type: "csv",
    include_migrated: false
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.CreatePayrollJournalReportsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ReportsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reports.<a href="/src/api/resources/reports/client/Client.ts">createCustomPayrollJournal</a>({ ...params }) -> ZealApi.CreateCustomPayrollJournalReportsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Create a custom payroll journal report.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.reports.createCustomPayrollJournal({
    companyID: "24b5b29f07924840b119c34c1358940c",
    media_type: "pdf",
    start_date: "2022-03-22",
    end_date: "2022-04-10",
    fields: {
        employee_taxes: false,
        employer_taxes: false,
        deductions: false,
        net_pay: false,
        earnings: false,
        disbursement: false,
        gross_pay: false
    }
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.CreateCustomPayrollJournalReportsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ReportsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reports.<a href="/src/api/resources/reports/client/Client.ts">createWorkerSummary</a>({ ...params }) -> ZealApi.CreateWorkerSummaryReportsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Create a worker summary report.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.reports.createWorkerSummary({
    companyID: "fc235f012bae46aa8a082f357715bcfa",
    worker_type: "employee",
    media_type: "csv",
    active_workers: true
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.CreateWorkerSummaryReportsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ReportsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reports.<a href="/src/api/resources/reports/client/Client.ts">createCashRequirements</a>({ ...params }) -> ZealApi.CreateCashRequirementsReportsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Create a cash requirements report
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.reports.createCashRequirements({
    companyID: "fc235f012bae46aa8a082f357715bcfa",
    check_date: "2023-12-22",
    media_type: "pdf"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.CreateCashRequirementsReportsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ReportsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reports.<a href="/src/api/resources/reports/client/Client.ts">createPaymentSummary</a>({ ...params }) -> ZealApi.CreatePaymentSummaryReportsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Create a payment summary report.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.reports.createPaymentSummary({
    pay_start_date: "2023-12-01",
    pay_end_date: "2023-12-28",
    companyID: "fc235f012bae46aa8a082f357715bcfa",
    media_type: "pdf"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.CreatePaymentSummaryReportsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ReportsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reports.<a href="/src/api/resources/reports/client/Client.ts">createLaborAllocation</a>({ ...params }) -> unknown</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Create a labor allocation report.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.reports.createLaborAllocation({
    start_date: "2023-12-01",
    end_date: "2024-12-20",
    companyID: "24b5b29f07924230b119c34c1358940c",
    media_type: "csv",
    include_migrated: false
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.CreateLaborAllocationReportsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ReportsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reports.<a href="/src/api/resources/reports/client/Client.ts">createPaystub</a>({ ...params }) -> ZealApi.CreatePaystubReportsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Create paystub report.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.reports.createPaystub({
    companyID: "0f2341ee141040acea333e132a3ccb462",
    start_date: "2023-12-20",
    end_date: "2023-12-06",
    media_type: "pdf"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.CreatePaystubReportsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ReportsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reports.<a href="/src/api/resources/reports/client/Client.ts">createYearToDate</a>({ ...params }) -> ZealApi.CreateYearToDateReportsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Create a year-to-date report.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.reports.createYearToDate({
    companyID: "fcc26cc444450ac8a33ry32a3z34462",
    employeeID: ["6266y546eyecc34458aef1", "6556fabfcf2eab26e23331"],
    year: "2023",
    media_type: "json"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.CreateYearToDateReportsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ReportsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reports.<a href="/src/api/resources/reports/client/Client.ts">createQuarterToDate</a>({ ...params }) -> ZealApi.CreateQuarterToDateReportsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Create a quarter to date report.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.reports.createQuarterToDate({
    companyID: "fcc26cc444450ac8a33ry32a3z34462",
    employeeID: ["6266y546eyecc34458aef1", "6556fabfcf2eab26e23331"],
    quarter: "q1",
    media_type: "json"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.CreateQuarterToDateReportsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ReportsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reports.<a href="/src/api/resources/reports/client/Client.ts">createDeductionSummary</a>({ ...params }) -> ZealApi.CreateDeductionSummaryReportsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Create a summary report outlining deductions within a given timeframe
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.reports.createDeductionSummary({
    companyID: "f3cc3ec1fb1e144bd39504ue80cf3e20612",
    media_type: "csv",
    start_date: "2024-04-01",
    end_date: "2024-05-30"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.CreateDeductionSummaryReportsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ReportsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reports.<a href="/src/api/resources/reports/client/Client.ts">get</a>({ ...params }) -> ZealApi.GetReportsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Get status for a job.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.reports.get({
    job_id: "job_id",
    companyID: "companyID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.GetReportsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ReportsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reports.<a href="/src/api/resources/reports/client/Client.ts">download</a>({ ...params }) -> ZealApi.DownloadReportsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Download a report.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.reports.download({
    job_id: "job_id"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.DownloadReportsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ReportsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.reports.<a href="/src/api/resources/reports/client/Client.ts">createKycSummary</a>({ ...params }) -> ZealApi.CreateKycSummaryReportsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Create a report containing KYC flagged workers by company.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.reports.createKycSummary({
    companyID: "companyID",
    employment_status: "live",
    media_type: "media_type"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.CreateKycSummaryReportsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ReportsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Documents
<details><summary><code>client.documents.<a href="/src/api/resources/documents/client/Client.ts">get</a>({ ...params }) -> ZealApi.GetDocumentsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Fetch tax/payroll documents such as tax returns and W-2s for an employer/employee.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.documents.get({
    companyID: "companyID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.GetDocumentsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `DocumentsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## InternationalContractors
<details><summary><code>client.internationalContractors.<a href="/src/api/resources/internationalContractors/client/Client.ts">get</a>({ ...params }) -> ZealApi.GetInternationalContractorsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Get international contractors for a company or a specific contractor.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.internationalContractors.get({
    companyID: "companyID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.GetInternationalContractorsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `InternationalContractorsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.internationalContractors.<a href="/src/api/resources/internationalContractors/client/Client.ts">create</a>({ ...params }) -> ZealApi.CreateInternationalContractorsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Create an international contractor.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.internationalContractors.create({
    companyID: "24b5b29f07924840b119c34c",
    new_international_contractors: [{
            email: "erlich@aviato.com",
            onboarded: true,
            start_date: "2023-08-20",
            tax_rate: 30,
            employment_status: "live"
        }, {
            email: "richard@piedpiper.com",
            onboarded: true,
            start_date: "2023-08-20",
            tax_rate: 20,
            employment_status: "terminated"
        }]
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.CreateInternationalContractorsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `InternationalContractorsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.internationalContractors.<a href="/src/api/resources/internationalContractors/client/Client.ts">update</a>({ ...params }) -> ZealApi.UpdateInternationalContractorsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Update an international contractor.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.internationalContractors.update({
    companyID: "24b5b29f07924840b119c34c1358940c",
    international_contractor: {
        intlContractorID: "b6bda6912c434b8295de48fe2f0f3663",
        email: "erlich+bachman@aviato.com",
        onboarded: true,
        start_date: "2023-12-20",
        tax_rate: 1.1
    }
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.UpdateInternationalContractorsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `InternationalContractorsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.internationalContractors.<a href="/src/api/resources/internationalContractors/client/Client.ts">generateOnboardingLink</a>({ ...params }) -> ZealApi.GenerateOnboardingLinkInternationalContractorsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Generate a secure onboarding link for an international contractor.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.internationalContractors.generateOnboardingLink({
    companyID: "24b5b29f0334eec3840b119c34c1358940c",
    intlContractorID: "b6bda6912c434b8295de48fe2f0f3663"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.GenerateOnboardingLinkInternationalContractorsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `InternationalContractorsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.internationalContractors.<a href="/src/api/resources/internationalContractors/client/Client.ts">createPayment</a>({ ...params }) -> ZealApi.CreatePaymentInternationalContractorsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Create an international contractor payment record.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.internationalContractors.createPayment({
    companyID: "789456123",
    intlContractorID: "123456789",
    pay_date: "2023-09-26",
    gross_amount: 1.1
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.CreatePaymentInternationalContractorsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `InternationalContractorsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Attributes
<details><summary><code>client.attributes.<a href="/src/api/resources/attributes/client/Client.ts">list</a>({ ...params }) -> unknown</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.attributes.list({
    companyID: "companyID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.ListAttributesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AttributesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.attributes.<a href="/src/api/resources/attributes/client/Client.ts">update</a>({ ...params }) -> unknown</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.attributes.update({
    companyID: "companyID",
    attributes: [{
            attributeID: "attributeID",
            value: "value"
        }]
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.UpdateAttributesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AttributesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## EmployeeCheck
<details><summary><code>client.employeeCheck.<a href="/src/api/resources/employeeCheck/client/Client.ts">triggerDisbursement</a>({ ...params }) -> unknown</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.employeeCheck.triggerDisbursement({
    companyID: "companyID",
    employeeCheckID: "employeeCheckID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.TriggerDisbursementEmployeeCheckRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EmployeeCheckClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Orders
<details><summary><code>client.orders.<a href="/src/api/resources/orders/client/Client.ts">list</a>({ ...params }) -> ZealApi.ListOrdersResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.orders.list({
    companyID: "companyID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.ListOrdersRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `OrdersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.orders.<a href="/src/api/resources/orders/client/Client.ts">create</a>({ ...params }) -> ZealApi.CreateOrdersResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.orders.create({
    companyID: "companyID",
    customerAccountID: "customerAccountID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.CreateOrdersRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `OrdersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.orders.<a href="/src/api/resources/orders/client/Client.ts">submit</a>({ ...params }) -> ZealApi.SubmitOrdersResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.orders.submit({
    companyID: "companyID",
    orderID: "orderID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.SubmitOrdersRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `OrdersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## BusinessCards
<details><summary><code>client.businessCards.<a href="/src/api/resources/businessCards/client/Client.ts">update</a>({ ...params }) -> ZealApi.UpdateBusinessCardsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.businessCards.update({
    companyID: "companyID",
    businessCardID: "businessCardID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.UpdateBusinessCardsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `BusinessCardsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## ServiceTypes
<details><summary><code>client.serviceTypes.<a href="/src/api/resources/serviceTypes/client/Client.ts">get</a>({ ...params }) -> ZealApi.GetServiceTypesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.serviceTypes.get({
    companyID: "companyID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.GetServiceTypesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ServiceTypesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.serviceTypes.<a href="/src/api/resources/serviceTypes/client/Client.ts">create</a>({ ...params }) -> ZealApi.CreateServiceTypesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.serviceTypes.create({
    companyID: "companyID",
    name: "name",
    rate_type: "flat_fee"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.CreateServiceTypesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ServiceTypesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## ContractorDeductionTemplates
<details><summary><code>client.contractorDeductionTemplates.<a href="/src/api/resources/contractorDeductionTemplates/client/Client.ts">list</a>({ ...params }) -> ZealApi.ListContractorDeductionTemplatesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.contractorDeductionTemplates.list({
    companyID: "companyID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.ListContractorDeductionTemplatesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ContractorDeductionTemplatesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.contractorDeductionTemplates.<a href="/src/api/resources/contractorDeductionTemplates/client/Client.ts">create</a>({ ...params }) -> ZealApi.CreateContractorDeductionTemplatesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.contractorDeductionTemplates.create({
    companyID: "companyID",
    contractorID: "contractorID",
    custom_name: "custom_name",
    deduction_type: "garnishment",
    effective_start_date: "effective_start_date"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.CreateContractorDeductionTemplatesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ContractorDeductionTemplatesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.contractorDeductionTemplates.<a href="/src/api/resources/contractorDeductionTemplates/client/Client.ts">delete</a>({ ...params }) -> ZealApi.DeleteContractorDeductionTemplatesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.contractorDeductionTemplates.delete({
    companyID: "companyID",
    deductionTemplateID: "deductionTemplateID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.DeleteContractorDeductionTemplatesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ContractorDeductionTemplatesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.contractorDeductionTemplates.<a href="/src/api/resources/contractorDeductionTemplates/client/Client.ts">update</a>({ ...params }) -> ZealApi.UpdateContractorDeductionTemplatesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.contractorDeductionTemplates.update({
    deductionTemplateID: "deductionTemplateID",
    companyID: "companyID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.UpdateContractorDeductionTemplatesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ContractorDeductionTemplatesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## PaymentItems
<details><summary><code>client.paymentItems.<a href="/src/api/resources/paymentItems/client/Client.ts">create</a>({ ...params }) -> ZealApi.CreatePaymentItemsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.paymentItems.create({
    companyID: "companyID",
    contractorID: "contractorID",
    contractorPaymentID: "contractorPaymentID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.CreatePaymentItemsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PaymentItemsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.paymentItems.<a href="/src/api/resources/paymentItems/client/Client.ts">update</a>({ ...params }) -> ZealApi.UpdatePaymentItemsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>


</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.paymentItems.update({
    companyID: "companyID",
    paymentItemID: "paymentItemID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.UpdatePaymentItemsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PaymentItemsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## PaymentLink
<details><summary><code>client.paymentLink.<a href="/src/api/resources/paymentLink/client/Client.ts">get</a>({ ...params }) -> ZealApi.GetPaymentLinkResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Fetches an expirable link that displays an employee paystub.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.paymentLink.get({
    companyID: "companyID",
    contractorPaymentID: "contractorPaymentID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.GetPaymentLinkRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PaymentLinkClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## EmployeeDeductionTemplates
<details><summary><code>client.employeeDeductionTemplates.<a href="/src/api/resources/employeeDeductionTemplates/client/Client.ts">list</a>({ ...params }) -> ZealApi.ListEmployeeDeductionTemplatesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Returns a paginated array of Employee Deduction Template objects matching the supplied filters.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.employeeDeductionTemplates.list();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.ListEmployeeDeductionTemplatesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EmployeeDeductionTemplatesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.employeeDeductionTemplates.<a href="/src/api/resources/employeeDeductionTemplates/client/Client.ts">create</a>({ ...params }) -> ZealApi.CreateEmployeeDeductionTemplatesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Creates a new deduction template for an employee.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.employeeDeductionTemplates.create({
    companyID: "companyID",
    employeeID: "employeeID",
    custom_name: "custom_name",
    deduction_type: "401k",
    effective_start_date: "2023-01-15"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.CreateEmployeeDeductionTemplatesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EmployeeDeductionTemplatesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.employeeDeductionTemplates.<a href="/src/api/resources/employeeDeductionTemplates/client/Client.ts">get</a>({ ...params }) -> ZealApi.GetEmployeeDeductionTemplatesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Returns a single Employee Deduction Template object identified by its deductionTemplateID.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.employeeDeductionTemplates.get({
    deductionTemplateID: "deductionTemplateID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.GetEmployeeDeductionTemplatesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EmployeeDeductionTemplatesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.employeeDeductionTemplates.<a href="/src/api/resources/employeeDeductionTemplates/client/Client.ts">delete</a>({ ...params }) -> ZealApi.DeleteEmployeeDeductionTemplatesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Deletes an existing Employee Deduction Template identified by its deductionTemplateID.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.employeeDeductionTemplates.delete({
    deductionTemplateID: "deductionTemplateID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.DeleteEmployeeDeductionTemplatesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EmployeeDeductionTemplatesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.employeeDeductionTemplates.<a href="/src/api/resources/employeeDeductionTemplates/client/Client.ts">update</a>({ ...params }) -> ZealApi.UpdateEmployeeDeductionTemplatesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Updates an existing Employee Deduction Template.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.employeeDeductionTemplates.update({
    deductionTemplateIDPathParam: "deductionTemplateID"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `ZealApi.UpdateEmployeeDeductionTemplatesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EmployeeDeductionTemplatesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

