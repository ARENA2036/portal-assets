# Implementation
<br>

## 1 Get Invited Companies
<br>
Get all applications with there state and invited company name.
<br>
<br>

#### API Details

```diff
! GET api/administration/registration/applicationsWithStatus
```

Endpoints supports pagination & search by company name
<br>
<br>

## 2 Invite Companies

The invitation is the starting point of a company onboarding.
A user of the company is getting invited by the CX Admin and the invitation endpoint is triggering in the backend the creation of the identity relevant elements.
<br>
<br>
<img width="998" alt="image" src="https://user-images.githubusercontent.com/94133633/210187547-2e101125-33a5-44db-bda8-c65afef71407.png">
<br>
<br>
#### API Details

```diff
! POST api/administration/invitation
```

<br>
<br>
Please note that a standard realm config got configured inside the endpoint to ensure that all security and structural factory are considered - under following page you can find the configuration details **to be added**
<br>
<br>

## 3  Search

Search is included in Endpoint #1.

The endpoint does support search via the company name
