## **프로젝트 개요:**

이 프로젝트는 **Spring Framework**를 사용하여 **카카오 로그인 API**를 구현한 시스템으로, 사용자가 카카오 계정을 통해 로그인하고 **JWT(Json Web Token)**를 발급받는 과정을 다룹니다. 로그인 성공 후, 사용자 정보를 **MongoDB**에 저장하고, 클라이언트에 전달하는 기능을 포함합니다.

**구현된 주요 기능:**
1. **카카오 로그인 성공 처리**: 사용자가 카카오 계정으로 로그인에 성공한 후, 인증된 사용자 정보를 처리합니다.
2. **JWT 발급 및 쿠키 저장**: 로그인 성공 시 **JWT**를 발급하고, 이를 **쿠키**에 저장하여 사용자의 인증 상태를 유지합니다.
3. **사용자 정보 MongoDB 저장**: 로그인한 사용자의 정보를 **MongoDB** 데이터베이스에 저장합니다.
4. **클라이언트에 사용자 정보 전달**: 저장된 사용자 정보를 클라이언트에 전달하여, 이후 응용 프로그램에서 활용할 수 있도록 합니다.
