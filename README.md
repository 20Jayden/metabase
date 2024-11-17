# Metabase

[Metabase](https://www.metabase.com) is the easy, open-source way for everyone in your company to ask questions and learn from data.

![Metabase Product Screenshot](docs/images/metabase-product-screenshot.svg)

[![Latest Release](https://img.shields.io/github/release/metabase/metabase.svg?label=latest%20release)](https://github.com/metabase/metabase/releases)
[![codecov](https://codecov.io/gh/metabase/metabase/branch/master/graph/badge.svg)](https://codecov.io/gh/metabase/metabase)
![Docker Pulls](https://img.shields.io/docker/pulls/metabase/metabase)

## Get started

The easiest way to get started with Metabase is to sign up for a free trial of [Metabase Cloud](https://store.metabase.com/checkout). You get support, backups, upgrades, an SMTP server, SSL certificate, SoC2 Type 2 security auditing, and more (plus your money goes toward improving Metabase). Check out our quick overview of [cloud vs self-hosting](https://www.metabase.com/docs/latest/cloud/cloud-vs-self-hosting). If you need to, you can always switch to [self-hosting](https://www.metabase.com/docs/latest/installation-and-operation/installing-metabase) Metabase at any time (or vice versa).

## Features

- [Set up in five minutes](https://www.metabase.com/docs/latest/setting-up-metabase.html) (we're not kidding).
- Let anyone on your team [ask questions](https://www.metabase.com/docs/latest/users-guide/04-asking-questions.html) without knowing SQL.
- Use the [SQL editor](https://www.metabase.com/docs/latest/questions/native-editor/writing-sql) for more complex queries.
- Build handsome, interactive [dashboards](https://www.metabase.com/docs/latest/users-guide/07-dashboards.html) with filters, auto-refresh, fullscreen, and custom click behavior.
- Create [models](https://www.metabase.com/learn/getting-started/models) that clean up, annotate, and/or combine raw tables.
- Define canonical [segments and metrics](https://www.metabase.com/docs/latest/administration-guide/07-segments-and-metrics.html) for your team to use.
- Send data to Slack or email on a schedule with [dashboard subscriptions](https://www.metabase.com/docs/latest/users-guide/dashboard-subscriptions).
- Set up [alerts](https://www.metabase.com/docs/latest/users-guide/15-alerts.html) to have Metabase notify you when your data changes.
- [Embed charts and dashboards](https://www.metabase.com/docs/latest/administration-guide/13-embedding.html) in your app, or even [your entire Metabase](https://www.metabase.com/docs/latest/enterprise-guide/full-app-embedding.html).

Take a [tour of Metabase](https://www.metabase.com/learn/getting-started/tour-of-metabase).

## Supported databases

- [Officially supported databases](./docs/databases/connecting.md#connecting-to-supported-databases)
- [Partner and Community drivers](./docs/developers-guide/partner-and-community-drivers.md)

## Installation

Metabase can be run just about anywhere. Check out our [Installation Guides](https://www.metabase.com/docs/latest/operations-guide/installing-metabase).

## Contributing

## Quick Setup: Dev environment

In order to spin up a development environment, you need to start the front end and the backend as follows:

### Frontend quick setup

The following command will install the Javascript dependencies:

```
$ yarn install
```

To build and run without watching changes:

```
$ yarn build
```

To build and run with hot-reload:

```
$ yarn build-hot
```

### Backend  quick setup

In order to run the backend, you'll need to build the drivers first, and then start the backend:

```
$ ./bin/build-drivers.sh
$ clojure -M:run
```

For a more detailed setup of a dev environment for Metabase, check out our [Developers Guide](./docs/developers-guide/start.md).

## Internationalization

We want Metabase to be available in as many languages as possible. See which translations are available and help contribute to internationalization using our project over at [POEditor](https://poeditor.com/join/project/ynjQmwSsGh). You can also check out our [policies on translations](https://www.metabase.com/docs/latest/administration-guide/localization.html).

## Extending Metabase

Hit our Query API from Javascript to integrate analytics. Metabase enables your application to:

- Build moderation interfaces.
- Export subsets of your users to third party marketing automation software.
- Provide a custom customer lookup application for the people in your company.

Check out our guide, [Working with the Metabase API](https://www.metabase.com/learn/administration/metabase-api).

## Security Disclosure

See [SECURITY.md](./SECURITY.md) for details.

## License

This repository contains the source code for both the Open Source edition of Metabase, released under the AGPL, as well as the [commercial editions of Metabase](https://www.metabase.com/pricing), which are released under the Metabase Commercial Software License.

See [LICENSE.txt](./LICENSE.txt) for details.

Unless otherwise noted, all files © 2024 Metabase, Inc.

## [Metabase Experts](https://www.metabase.com/partners/)

If you’d like more technical resources to set up your data stack with Metabase, connect with a [Metabase Expert](https://www.metabase.com/partners/?utm_source=readme&utm_medium=metabase-expetrs&utm_campaign=readme).














# Metabase

[Metabase](https://www.metabase.com)는 회사의 모든 구성원이 데이터에 대해 질문하고 배울 수 있는 쉽고 오픈소스인 방법입니다.

![Metabase 제품 스크린샷](docs/images/metabase-product-screenshot.svg)

[![최신 릴리즈](https://img.shields.io/github/release/metabase/metabase.svg?label=latest%20release)](https://github.com/metabase/metabase/releases)
[![codecov](https://codecov.io/gh/metabase/metabase/branch/master/graph/badge.svg)](https://codecov.io/gh/metabase/metabase)
![Docker Pulls](https://img.shields.io/docker/pulls/metabase/metabase)

## 시작하기

Metabase를 시작하는 가장 쉬운 방법은 [Metabase Cloud](https://store.metabase.com/checkout)의 무료 체험판에 가입하는 것입니다. 지원, 백업, 업그레이드, SMTP 서버, SSL 인증서, SoC2 Type 2 보안 감사 등을 제공받을 수 있습니다(또한 여러분의 비용은 Metabase 개선에 사용됩니다). [클라우드와 자체 호스팅 비교](https://www.metabase.com/docs/latest/cloud/cloud-vs-self-hosting)를 확인해보세요. 필요한 경우 언제든지 Metabase를 [자체 호스팅](https://www.metabase.com/docs/latest/installation-and-operation/installing-metabase)으로 전환할 수 있습니다(또는 그 반대도 가능).

## 주요 기능

- [5분 안에 설정 완료](https://www.metabase.com/docs/latest/setting-up-metabase.html) (농담이 아닙니다).
- SQL을 모르더라도 팀원 누구나 [질문할 수 있습니다](https://www.metabase.com/docs/latest/users-guide/04-asking-questions.html).
- 더 복잡한 쿼리를 위한 [SQL 에디터](https://www.metabase.com/docs/latest/questions/native-editor/writing-sql) 제공.
- 필터, 자동 새로고침, 전체화면, 맞춤형 클릭 동작이 포함된 멋진 인터랙티브 [대시보드](https://www.metabase.com/docs/latest/users-guide/07-dashboards.html) 구축.
- 원시 테이블을 정리, 주석 처리 및/또는 결합하는 [모델](https://www.metabase.com/learn/getting-started/models) 생성.
- 팀이 사용할 표준 [세그먼트와 메트릭](https://www.metabase.com/docs/latest/administration-guide/07-segments-and-metrics.html) 정의.
- [대시보드 구독](https://www.metabase.com/docs/latest/users-guide/dashboard-subscriptions)으로 일정에 따라 Slack이나 이메일로 데이터 전송.
- 데이터가 변경될 때 Metabase가 알림을 보내도록 [알림](https://www.metabase.com/docs/latest/users-guide/15-alerts.html) 설정.
- 앱에 [차트와 대시보드를 임베드](https://www.metabase.com/docs/latest/administration-guide/13-embedding.html)하거나 [전체 Metabase](https://www.metabase.com/docs/latest/enterprise-guide/full-app-embedding.html)를 임베드할 수 있습니다.

[Metabase 둘러보기](https://www.metabase.com/learn/getting-started/tour-of-metabase)를 확인해보세요.

## 지원되는 데이터베이스

- [공식 지원 데이터베이스](./docs/databases/connecting.md#connecting-to-supported-databases)
- [파트너 및 커뮤니티 드라이버](./docs/developers-guide/partner-and-community-drivers.md)

## 설치

Metabase는 거의 모든 곳에서 실행될 수 있습니다. [설치 가이드](https://www.metabase.com/docs/latest/operations-guide/installing-metabase)를 확인해보세요.

## 기여하기

## 빠른 설정: 개발 환경

개발 환경을 구축하려면 다음과 같이 프론트엔드와 백엔드를 시작해야 합니다:

### 프론트엔드 빠른 설정

다음 명령어로 Javascript 의존성을 설치합니다:

```
$ yarn install
```

변경 사항 감시 없이 빌드하고 실행하려면:

```
$ yarn build
```

핫 리로드로 빌드하고 실행하려면:

```
$ yarn build-hot
```

### 백엔드 빠른 설정

백엔드를 실행하려면 먼저 드라이버를 빌드한 다음 백엔드를 시작해야 합니다:

```
$ ./bin/build-drivers.sh
$ clojure -M:run
```

Metabase의 개발 환경 설정에 대한 자세한 내용은 [개발자 가이드](./docs/developers-guide/start.md)를 확인하세요.

## 국제화

우리는 Metabase를 가능한 한 많은 언어로 제공하고자 합니다. [POEditor](https://poeditor.com/join/project/ynjQmwSsGh)에서 어떤 번역이 가능한지 확인하고 국제화에 기여해주세요. [번역 정책](https://www.metabase.com/docs/latest/administration-guide/localization.html)도 확인할 수 있습니다.

## Metabase 확장

Javascript에서 Query API를 사용하여 분석을 통합하세요. Metabase를 통해 애플리케이션에서 다음을 수행할 수 있습니다:

- 중재 인터페이스 구축.
- 사용자 하위 집합을 서드파티 마케팅 자동화 소프트웨어로 내보내기.
- 회사 직원을 위한 맞춤형 고객 조회 애플리케이션 제공.

[Metabase API 작업하기](https://www.metabase.com/learn/administration/metabase-api) 가이드를 확인하세요.

## 보안 공개

자세한 내용은 [SECURITY.md](./SECURITY.md)를 참조하세요.

## 라이선스

이 저장소는 AGPL 라이선스로 제공되는 Metabase 오픈소스 에디션과 Metabase 상업용 소프트웨어 라이선스로 제공되는 [Metabase 상업용 에디션](https://www.metabase.com/pricing)의 소스 코드를 모두 포함하고 있습니다.

자세한 내용은 [LICENSE.txt](./LICENSE.txt)를 참조하세요.

별도로 명시되지 않은 한 모든 파일은 © 2024 Metabase, Inc.의 소유입니다.

## [Metabase 전문가](https://www.metabase.com/partners/)

Metabase로 데이터 스택을 설정하는 데 더 많은 기술 리소스가 필요하다면 [Metabase 전문가](https://www.metabase.com/partners/?utm_source=readme&utm_medium=metabase-expetrs&utm_campaign=readme)와 연결하세요.