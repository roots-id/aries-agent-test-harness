# Findy Agent Interoperability

## Runsets with Findy

| Runset | ACME<br>(Issuer) | Bob<br>(Holder) | Faber<br>(Verifier) | Mallory<br>(Holder) | Scope | Results | 
| ------ | :--------------: | :-------------: | :----------------: | :-----------------: | ----- | :-----: | 
| [acapy-findy](#runset-acapy-findy) | acapy-main<br>1.0.0-rc1 | findy<br>0.30.53 | acapy-main<br>1.0.0-rc1 | acapy-main<br>1.0.0-rc1 | AIP 1.0 | [**17 / 17<br>100%**](https://allure.vonx.io/api/allure-docker-service/projects/acapy-b-findy/reports/latest/index.html?redirect=false#behaviors) |
| [afj-findy](#runset-afj-findy) | javascript<br>0.3.4-alpha.5 | findy<br>0.30.53 | javascript<br>0.3.4-alpha.5 | javascript<br>0.3.4-alpha.5 | AIP 1.0 | [**17 / 17<br>100%**](https://allure.vonx.io/api/allure-docker-service/projects/javascript-b-findy/reports/latest/index.html?redirect=false#behaviors) |
| [dotnet-findy](#runset-dotnet-findy) | dotnet<br> | findy<br>0.30.53 | dotnet<br> | dotnet<br> | AIP 1.0 | [**0 / 10<br>0%**](https://allure.vonx.io/api/allure-docker-service/projects/dotnet-b-findy/reports/latest/index.html?redirect=false#behaviors) |
| [findy-acapy](#runset-findy-acapy) | findy<br>0.30.53 | acapy-main<br>1.0.0-rc1 | findy<br>0.30.53 | findy<br>0.30.53 | AIP 1.0 | [**17 / 17<br>100%**](https://allure.vonx.io/api/allure-docker-service/projects/findy-b-acapy/reports/latest/index.html?redirect=false#behaviors) |
| [findy-dotnet](#runset-findy-dotnet) | findy<br>0.30.53 | dotnet<br> | findy<br>0.30.53 | findy<br>0.30.53 | AIP 1.0 | [**12 / 12<br>100%**](https://allure.vonx.io/api/allure-docker-service/projects/findy-b-dotnet/reports/latest/index.html?redirect=false#behaviors) |
| [findy-javascript-dotnet](#runset-findy-javascript-dotnet) | findy<br>0.30.53 | javascript<br>0.3.4-alpha.5 | dotnet<br> | findy<br>0.30.53 | AIP 1.0 | [**17 / 17<br>100%**](https://allure.vonx.io/api/allure-docker-service/projects/findy-b-javascript-f-dotnet/reports/latest/index.html?redirect=false#behaviors) |
| [findy-javascript](#runset-findy-javascript) | findy<br>0.30.53 | javascript<br>0.3.4-alpha.5 | findy<br>0.30.53 | findy<br>0.30.53 | AIP 1.0 | [**17 / 17<br>100%**](https://allure.vonx.io/api/allure-docker-service/projects/findy-b-javascript/reports/latest/index.html?redirect=false#behaviors) |
| [findy](#runset-findy) | findy<br>0.30.53 | findy<br>0.30.53 | findy<br>0.30.53 | findy<br>0.30.53 | AIP 1.0 | [**17 / 17<br>100%**](https://allure.vonx.io/api/allure-docker-service/projects/findy/reports/latest/index.html?redirect=false#behaviors) |

## Runset Notes

### Runset **acapy-findy**

Runset Name: ACA-PY to findy

```tip
**Latest results: 17 out of 17 (100%)**


*Last run: Tue Jan 31 01:16:06 UTC 2023*
```

#### Current Runset Status

All of the tests being executed in this runset are passing.

*Status Note Updated: 2021.09.14*

#### Runset Details

- [Results by executed Aries RFCs](https://allure.vonx.io/api/allure-docker-service/projects/acapy-b-findy/reports/latest/index.html?redirect=false#behaviors)
- [Test execution history](https://allure.vonx.io/allure-docker-service-ui/projects/acapy-b-findy/reports/latest)


### Runset **afj-findy**

Runset Name: AFJ to findy

```tip
**Latest results: 17 out of 17 (100%)**


*Last run: Tue Jan 31 01:51:07 UTC 2023*
```

#### Current Runset Status

All of the tests being executed in this runset are failing. There is an issue with afj sending the connection
response, and throws an error processing inbound message.

*Status Note Updated: 2021.09.28*

#### Runset Details

- [Results by executed Aries RFCs](https://allure.vonx.io/api/allure-docker-service/projects/javascript-b-findy/reports/latest/index.html?redirect=false#behaviors)
- [Test execution history](https://allure.vonx.io/allure-docker-service-ui/projects/javascript-b-findy/reports/latest)


### Runset **dotnet-findy**

Runset Name: dotnet to findy

```tip
**Latest results: 0 out of 10 (0%)**


*Last run: Tue Jan 31 02:24:15 UTC 2023*
```

#### Current Runset Status

Two connection tests are passing out of Nineteen total. There are multiple issues in Issue Credential and Proof
with dotnet as the issuer and findy as the holder. Removed a large portion of Proof tests since jobs were getting cancelled.
These will be added back when tests or agents are fixed and stability has returned.

*Status Note Updated: 2022.01.28*

#### Runset Details

- [Results by executed Aries RFCs](https://allure.vonx.io/api/allure-docker-service/projects/dotnet-b-findy/reports/latest/index.html?redirect=false#behaviors)
- [Test execution history](https://allure.vonx.io/allure-docker-service-ui/projects/dotnet-b-findy/reports/latest)


### Runset **findy-acapy**

Runset Name: findy to ACA-PY

```tip
**Latest results: 17 out of 17 (100%)**


*Last run: Tue Jan 31 02:47:50 UTC 2023*
```

#### Current Runset Status

All of the tests being executed in this runset are passing.

*Status Note Updated: 2021.09.14*

#### Runset Details

- [Results by executed Aries RFCs](https://allure.vonx.io/api/allure-docker-service/projects/findy-b-acapy/reports/latest/index.html?redirect=false#behaviors)
- [Test execution history](https://allure.vonx.io/allure-docker-service-ui/projects/findy-b-acapy/reports/latest)


### Runset **findy-dotnet**

Runset Name: findy to dotnet

```tip
**Latest results: 12 out of 12 (100%)**


*Last run: Tue Jan 31 02:43:20 UTC 2023*
```

#### Current Runset Status

All test scenarios are passing. 

*Status Note Updated: 2021.10.15*

#### Runset Details

- [Results by executed Aries RFCs](https://allure.vonx.io/api/allure-docker-service/projects/findy-b-dotnet/reports/latest/index.html?redirect=false#behaviors)
- [Test execution history](https://allure.vonx.io/allure-docker-service-ui/projects/findy-b-dotnet/reports/latest)


### Runset **findy-javascript-dotnet**

Runset Name: findy to AFJ to AF-.NET

```tip
**Latest results: 17 out of 17 (100%)**


*Last run: Tue Jan 31 03:03:42 UTC 2023*
```

#### Current Runset Status

All of the tests being executed in this runset are passing. 

*Status Note Updated: 2021.10.15*

#### Runset Details

- [Results by executed Aries RFCs](https://allure.vonx.io/api/allure-docker-service/projects/findy-b-javascript-f-dotnet/reports/latest/index.html?redirect=false#behaviors)
- [Test execution history](https://allure.vonx.io/allure-docker-service-ui/projects/findy-b-javascript-f-dotnet/reports/latest)


### Runset **findy-javascript**

Runset Name: findy to AFJ

```tip
**Latest results: 17 out of 17 (100%)**


*Last run: Tue Jan 31 03:01:17 UTC 2023*
```

#### Current Runset Status

All of the tests being executed in this runset are passing. 

*Status Note Updated: 2021.10.15*

#### Runset Details

- [Results by executed Aries RFCs](https://allure.vonx.io/api/allure-docker-service/projects/findy-b-javascript/reports/latest/index.html?redirect=false#behaviors)
- [Test execution history](https://allure.vonx.io/allure-docker-service-ui/projects/findy-b-javascript/reports/latest)


### Runset **findy**

Runset Name: findy to findy

```tip
**Latest results: 17 out of 17 (100%)**


*Last run: Tue Jan 31 02:57:46 UTC 2023*
```

#### Current Runset Status

All of the tests being executed in this runset are passing.

*Status Note Updated: 2021.09.14*

#### Runset Details

- [Results by executed Aries RFCs](https://allure.vonx.io/api/allure-docker-service/projects/findy/reports/latest/index.html?redirect=false#behaviors)
- [Test execution history](https://allure.vonx.io/allure-docker-service-ui/projects/findy/reports/latest)

Jump back to the [interoperability summary](./README.md).

