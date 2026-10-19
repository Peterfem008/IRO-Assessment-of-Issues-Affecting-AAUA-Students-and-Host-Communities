# IRO: Issues Reporting Outlet
A minimal PHP + SQLite web application for AAUA students and host communities.

## Run
Requirements: PHP 8.0+ with PDO SQLite extension enabled.

From this directory:

```bash
php -S localhost:8000
```

Open http://localhost:8000/index.php

The `iro.sqlite` database is created automatically on first page load. Make sure the project directory is writable by PHP.

## Demonstration
1. Submit a report using the form.
2. Copy the generated reference (`IRO-XXXXXXXX`).
3. Enter it under **Track your report** to view its status.

## Scope and safety
This is an academic demonstration, not an active emergency or official complaint service. There is no administrator portal or real complaint-resolution workflow. All reports remain `Pending`. Do not use real sensitive personal information. SQLite data must not be published or committed. Deploy only with appropriate privacy controls, authorization and operational arrangements.
