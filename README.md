# CredenceLend

A multi-tenant cooperative lending platform available on both **Web** and **Mobile**. Designed to streamline loan management, member onboarding, and cooperative operations across multiple tenants.


## Developers

- **Engay, John Lloyd S.** — Mobile Developer
- **Estrella, John Senen H.** — Backend and Database
- **Olivarez, Alliah Marie O.** — Web Developer
***

## Project URLs

| Platform | URL |
|----------|-----|
| **Web (Tenant Dashboard)** | [credencelendv1-production.up.railway.app](https://credencelendv1-production.up.railway.app/) |
| **Mobile App (Customer)** | [credencelend-mobile.up.railway.app](https://credencelend-mobile.up.railway.app/) |

***

## Source Code Repositories

| Repository | Link |
|------------|------|
| **Web (CredenceLendV1)** | [CredenceLendV1](https://nationalueduph-my.sharepoint.com/:u:/g/personal/olivarezamo_students_nu-baliwag_edu_ph/IQA4oovQ-WsPRZQQFf4PddP_AZXv3hHN8uISsC6a1jRxR0s?e=NNejZb) |
| **Mobile (CredenceLend-mobile)** | [CredenceLend-mobile](https://github.com/Blaizy20/CredenceLend-mobile) |

***

## Credentials

### Superadmin
| Field | Value |
|-------|-------|
| **Username** | `admin` |
| **Password** | `admin123` |

> The superadmin account has full access to the platform, including tenant management, user oversight, and system configuration.

***

### Tenant
| Field | Value |
|-------|-------|
| **Username** | `test_admin_1` |
| **Password** | `Password123!` |

***

### Staff Accounts (Web)

#### Manager
| Field | Value |
|-------|-------|
| **Username** | `test_manager` |
| **Password** | `Password123!` |

***

#### CI
| Field | Value |
|-------|-------|
| **Username** | `test_cii` |
| **Password** | `Password123!` |

***

#### Cashier
| Field | Value |
|-------|-------|
| **Username** | `test_cashier` |
| **Password** | `Password123!` |

***

#### Loan Officer
| Field | Value |
|-------|-------|
| **Username** | `test_loan_officer` |
| **Password** | `Password123!` |

***

### Customer (Mobile App)

Customers access the platform through the mobile app. The onboarding flow requires a **Cooperative Code** to identify which tenant they belong to.

#### How to Log In as a Customer

1. Launch the mobile app
2. Enter the **Cooperative Code** to select your cooperative/tenant
3. If the code is valid, you will be redirected to the **Login Page**
4. New users may **Register** freely — no invite required
5. After registration or login, you will have full access to your member dashboard

#### Example Customer Credentials

| Field | Value |
|-------|-------|
| **Cooperative Code** | `QU5633` |
| **Username** | `testuser` |
| **Password** | `testpassword` |

***

## Tech Stack

| Layer | Technology |
|-------|------------|
| **Web** | PHP + CSS |
| **Backend** | Node.js + Express |
| **Database** | MySQL |
| **Mobile** | React + Capacitor |
| **Deployment** | Railway |
| **File Storage** | AWS S3 |

***

## Notes

- This is a **multi-tenant** system — each cooperative operates under its own isolated tenant environment.
- The mobile app serves **customers/members**, while the web dashboard is used by **staff and administrators**.
- Placeholder credentials marked with `[BRACKETS]` are pending updates from the development team.
