# CinemaReady

CinemaReady is an educational Microsoft Excel operational prototype for checking whether a cinema hall is technically ready for a screening.

The workbook combines screening details, simulated equipment and network checks, automatic readiness calculations, issue diagnosis, incident tracking, and a simple network map.

> **Important:** CinemaReady does not communicate with real cinema equipment. Device and network statuses are entered manually for demonstration and learning purposes.

## Dashboard

![CinemaReady dashboard](screenshots/dashboard.png)

## Main features

- Screening details for hall, movie, date, and start time
- Status tracking for projector, sound system, and CCTV camera
- Simulated IP addressing and ping results
- Automatic readiness score and final screening decision
- Automatic diagnosis of network and functional issues
- Incident log with priority, status, resolution, and notes
- Visual network map
- Project documentation inside the workbook

## Incident tracking

![Incident log](screenshots/incident-log.png)

The incident log demonstrates a simple IT support workflow:

1. Record the issue
2. Assign a priority
3. Track its status
4. Document the resolution

## Excel features used

- `IF`
- `AND`
- `COUNTIF`
- Data Validation dropdown lists
- Conditional Formatting
- Cell references and percentage calculations
- Structured operational tables

## Project information

![Project information](screenshots/project-info.png)

## How to use

1. Download `CinemaReady.xlsx`.
2. Open it in Microsoft Excel.
3. Select the hall and enter the screening details.
4. Update the equipment ping and functional statuses.
5. Review the readiness score, diagnosis, and recommended action.
6. Record technical problems in the **Incident Log** worksheet.

## Repository contents

```text
CinemaReady/
├── CinemaReady.xlsx
├── README.md
└── screenshots/
    ├── dashboard.png
    ├── incident-log.png
    └── project-info.png
```

## Skills demonstrated

- Microsoft Excel
- Basic networking concepts
- IT support workflow
- Technical troubleshooting logic
- Incident documentation
- Operational reporting

## Limitations

- No live network scanning
- No connection to real projectors, audio systems, or CCTV equipment
- Equipment statuses are entered manually
- Designed as a beginner-level educational portfolio project

## Author

Boyan Nikolov
