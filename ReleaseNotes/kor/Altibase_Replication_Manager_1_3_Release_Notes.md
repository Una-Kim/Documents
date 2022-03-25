- [Altibase Replication Manager 1.3 Release Notes](#altibase-replication-manager-13-release-notes)
  - [1. 개요](#1-%EA%B0%9C%EC%9A%94)
    - [1.1 시스템 요구사항](#11-%EC%8B%9C%EC%8A%A4%ED%85%9C-%EC%9A%94%EA%B5%AC%EC%82%AC%ED%95%AD)
    - [1.2 지원하는 OS 및 플랫폼](#12-%EC%A7%80%EC%9B%90%ED%95%98%EB%8A%94-os-%EB%B0%8F-%ED%94%8C%EB%9E%AB%ED%8F%BC)
  - [2. 릴리즈 정보](#2-%EB%A6%B4%EB%A6%AC%EC%A6%88-%EC%A0%95%EB%B3%B4)
    - [2.1 Altibase Replication Manager](#21-altibase-replication-manager)
    - [2.2 변경사항](#22-%EB%B3%80%EA%B2%BD%EC%82%AC%ED%95%AD)
    - [2.3 오픈소스 라이브러리](#23-%EC%98%A4%ED%94%88%EC%86%8C%EC%8A%A4-%EB%9D%BC%EC%9D%B4%EB%B8%8C%EB%9F%AC%EB%A6%AC)
    - [2.4 패키지](#24-%ED%8C%A8%ED%82%A4%EC%A7%80)
    - [2.5 다운로드](#25-%EB%8B%A4%EC%9A%B4%EB%A1%9C%EB%93%9C)



Altibase Replication Manager 1.3 Release Notes
===============================

**(March 31, 2022)**


## 1. 개요

### 1.1 시스템 요구사항

#### 하드웨어 최저 사양

* 프로세서: 800MHz Pentium III 이상
* 메모리: 512 MB 이상
* 디스크: 50MB 이상 여유공간 (JRE를 위한 별도의 저장 공간 필요)
* 화면 해상도: 1024 * 768 픽셀 이상

### 1.2 지원하는 OS 및 플랫폼

| OS                 | CPU  | 그래픽 라이브러리 | Bit   | JRE         |
| ------------------ | ---- | ----------------- | ----- | ----------- |
| Windows XP Vista 7 | x86  | Win32             | 32bit | Java 6 이상 |
| LINUX              | x86  | GTK               | 32bit | Java 6 이상 |

## 2. 릴리즈 정보

### 2.1 Altibase Replication Manager

Replication Manager는 Alitbase의 이중화를 효율적으로 관리하기 위한 GUI 툴이다.

#### 2.1.1 새로운 기능

| 버그 번호 | 제목 |
| :-------: | :--: |

#### 2.1.2  수정된 버그

| 버그 번호 |                             제목                             |
| :-------: | :----------------------------------------------------------: |
| BUG-49500 | CVE-2021-44832 보안 이슈로 로깅시스템을 log4j에서 JUL (java.util.logging)로 변경한다. |

### 2.2 변경사항

Replication Manager에 추가, 삭제 또는 변경된 기능들은 다음과 같다.

#### 2.2.1 버전 업데이트

- Replication Manager 버전: 1.3

#### 2.2.2 호환성

- Altibase: Altibase 4.3.9 이상

#### 2.2.3 프로퍼티

#### 2.2.4 에러 메시지

### 2.3 오픈소스 라이브러리

Replication Manager는 아래의 오픈소스 라이브러리와 로열티 프리 이미지에 기반한다. 라이선스는 텍스트 파일 형식으로 Replication Manager와 함께 제공된다.

| 라이브러리         | 오픈소스 라이선스                                            |
| ------------------ | ------------------------------------------------------------ |
| blancoSqlFormatter | Homepage: http://www.igapyon.jp/blanco/blancosqlformatter.html </br>License: LGPL (http://www.gnu.org/licenses/lgpl-3.0.txt) |
| Eclipse            | Homepage: http://www.eclipse.org <br/>License: Eclipse Public License (http://www.eclipse.org/legal/epl-v10.html) |
| JDOM               | Homepage: http://www.jfree.org/jfreechart/) <br/>License: LGPL (http://www.gnu.org/licenses/lgpl-3.0.txt) |
| JFreeChart         | Homepage: http://www.jfree.org/jfreechart/) <br/>License: LGPL (http://www.gnu.org/licenses/lgpl-3.0.txt) |
| SLF4J              | Homepage: https://www.slf4j.org/<br/>License: MIT (https://www.slf4j.org/license.html) |

| 라이브러리                | 로열티 프리 이미지                         |
| ------------------------- | ------------------------------------------ |
| asp.net_commercial_free2  | Homepage: www.asp.net                      |
| www.famfamfam.com         | Homepage: www.famfamfam.com                |
| fatcow-hosting-icons-2400 | Homepage: http://www.fatcow.com/free-icons |

### 2.4 패키지

| OS          | CPU | Archive Name                           |
| ----------- | --- | -------------------------------------- |
| Linux/glibc | x86 | ReplicationManager-linux.gtk.x86.zip   |
| Windows     | x86 | ReplicationManager-win32.win32.x86.zip |

### 2.5 다운로드

#### 2.5.1 패키지

<http://support.altibase.com>

#### 2.5.2 매뉴얼

[Replication Manager User's Manual.md](https://github.com/ALTIBASE/Documents/blob/master/Manuals/Tools/kor/Replication%20Manager%20User's%20Manual.md)

#### 2.5.3 Installation

Replication Manager User's Manual을 참고한다.