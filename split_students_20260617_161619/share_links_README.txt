Share Link Template Guide

1) Open share_links_template.csv
2) Replace <DASHBOARD_URL> with your hosted chartjs_student_dashboard.html URL
3) Replace <TOKEN_PACKAGES_BASE_URL> with your hosted split_students.../token_packages URL
4) Send each student their own Dashboard Share URL Template value

Example
- Dashboard URL: https://school.example.com/chartjs_student_dashboard.html
- Token base URL: https://school.example.com/split_students_20260617_120000/token_packages
- Final link format: <dashboard>?base=<encoded-token-base>&token=<student-token>