# DAY 1

## Tạo mới project

```typescript
ng new [tên_project];
```

## Angular 9 node 16 làm theo cách sau để tạo project

```typescript
ng new [tên_project] --skip-install
cd [tên_project]
npm install --legacy-peer-deps
```

## Chạy project

```typescript
ng serve
Hoặc
npm start
```

## Sửa auto format

Tạo file .prettierrc và thêm như sau

```typescript
  {
    "printWidth": 160,
    "singleQuote": true,
    "trailingComma": "es5",
    "htmlWhitespaceSensitivity": "ignore",
    "singleAttributePerLine": false
  }
```

Mở Command Palette (Ctrl+Shift+P) > Preferences: Open Settings (JSON) thêm

```typescript
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "[html]": {
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.formatOnSave": true
  }
```

## Sửa lỗi trong file tsconfig.json

Thêm đoạn sau vào compilerOptions trong file tsconfig.json

```typescript
    "types": [],
    "ignoreDeprecations": "6.0"
```

123123123
