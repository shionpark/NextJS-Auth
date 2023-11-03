# NextJS-Auth

### 사용 기술

- React Hook Form
- Prisma
- SWR
- API Routes
- iron-session

### 페이지

- Sign Up: 유저는 계정을 생성할 수 있습니다.
- Sign In: 유저는 로그인 할 수 있습니다.
- Home: 유저는 프로필을 볼 수 있습니다.

### 기능

- 유저가 **로그인 되어있지 않으면** `/` 페이지는 `/create-account` 페이지로 리다이렉트
- 유저가 계정을 생성한 후에는. `/log-in` 페이지로 리다이렉트
- 유저가 **로그인 할 때에는** `/` 으로 리다이렉트 하여 그들의 프로필을 볼 수 있음
