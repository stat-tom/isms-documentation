# Password Policy

## 1. Purpose

The purpose of this policy is to ensure an appropriate level of security through the use of rules for creating, storing, and managing passwords.

## 2. Scope

This policy applies to:

- all employees
- contractors and collaborators
- the organization's information systems
- user accounts, both internal and external

## 3. Password Requirements

### 3.1 Password Creation

Passwords must meet the following requirements:

- minimum length: 12 characters
- must contain at least:
    - one uppercase letter
    - one lowercase letter
    - one number
    - one special character
- must not contain:
    - the user's name
    - the company name
    - common words or patterns such as `password` or `123456`

The use of passphrases is recommended.

### 3.2 Password Uniqueness

- each account must have a unique password
- reusing passwords across different systems is prohibited

### 3.3 Password Validity Period

- passwords should be changed every 90 days
- password validity period may be extended if MFA is enabled
- the system should prevent reuse of the last 5 passwords

### 3.4 Password Storage

- passwords must not be stored in plain text
- systems must use secure hashing algorithms such as `bcrypt` or `Argon2`
- storing passwords in text files or on paper is prohibited

### 3.5 Password Sharing

- sharing passwords with other individuals is prohibited
- administrators must not ask users for their passwords

### 3.6 Multi-Factor Authentication (MFA)

MFA is required for:

- administrative access
- remote access, including VPN
- critical systems

## 4. Account Lockout

- an account must be locked after 5 failed login attempts
- unlocking must occur after 15 minutes or by an administrator

## 5. Incident Management

In the event of suspected password compromise:

- the user must immediately change the password
- the incident must be reported to the security team

## 6. Responsibilities

- users are responsible for maintaining the security of their passwords
- the IT department is responsible for implementing and enforcing this policy

## 7. Compliance

Failure to comply with this policy may result in:

- restricted access
- disciplinary action

## 8. Policy Review

This policy must be reviewed at least once per year.
