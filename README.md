# CinemaReady

CinemaReady is an educational Microsoft Excel operational prototype for checking whether a cinema hall is technically ready for a screening.

The workbook combines screening details, simulated equipment and network checks, automatic readiness calculations, issue diagnosis, incident tracking, and a visual network topology.

> **Important:** CinemaReady does not communicate with real cinema equipment. Device and network statuses are entered manually for demonstration and learning purposes.

## Download

[Download the CinemaReady Excel workbook](./CinemaReady.xlsx)

## Main Dashboard

The main dashboard contains the screening details, simulated network configuration, equipment checks, live readiness score, automatic diagnosis, and recommended action.

![CinemaReady main dashboard](screenshots/dashboard-overview.png)

The lower dashboard section displays the final screening decision, project limitations, and example Command Prompt ping tests.

![CinemaReady readiness decision](screenshots/dashboard-readiness.png)

## Main Features

- Screening details for hall, movie, date, and start time
- Status tracking for the projector, sound system, and CCTV camera
- Simulated IP addressing and ping results
- Automatic readiness score
- Final screening readiness decision
- Automatic diagnosis of network and functional issues
- Recommended operator action
- Technical incident tracking
- Visual network topology
- Project documentation inside the workbook

## Incident Tracking

The Incident Log worksheet demonstrates a simple IT support process for documenting equipment problems, priorities, status updates, and final resolutions.

![CinemaReady incident log](screenshots/incident-log.png)

The incident workflow is:

1. Record the technical issue
2. Select the affected hall and device
3. Assign a priority
4. Track the incident status
5. Document the final resolution

## Simulated Network Topology

The Network Map worksheet visualizes the example connection between the support PC, network switch, projector, sound system, and CCTV camera.

![CinemaReady simulated network topology](screenshots/network-map.png)

Example network configuration:

| Component | Address |
|---|---|
| Network | `192.168.10.0/24` |
| Subnet Mask | `255.255.255.0` |
| Gateway | `192.168.10.1` |
| Support PC | `192.168.10.100` |
| Projector | `192.168.10.10` |
| Sound System | `192.168.10.20` |
| CCTV Camera | `192.168.10.30` |

All addresses are simulated private IP addresses used only for educational purposes.

## Project Information

The Project Information worksheet explains the purpose of CinemaReady, its main functions, and the operational workflow.

![CinemaReady project overview](screenshots/project-info-overview.png)

It also documents the Excel features used, the simple project explanation, and the project scope and limitations.

![CinemaReady project details](screenshots/project-info-details.png)

## Excel Features Used

- `IF`
- `AND`
- `COUNTIF`
- Data Validation dropdown lists
- Conditional Formatting
- Cell references
- Percentage calculations
- Merged sections and dashboard formatting
- Structured operational tables

## How to Use

1. Download `CinemaReady.xlsx`.
2. Open it in Microsoft Excel.
3. Select the hall.
4. Enter the movie, date, and screening start time.
5. Update the equipment ping results and functional statuses.
6. Review the readiness score and automatic diagnosis.
7. Check the recommended action and final readiness decision.
8. Record technical problems in the **Incident Log** worksheet.
9. Document the incident resolution after troubleshooting.

## Operational Workflow

```text
Pre-screening check
        ↓
Enter device status
        ↓
Review automatic diagnosis
        ↓
Receive readiness decision
        ↓
Record an incident when required
        ↓
Document the resolution
```

## Repository Contents

```text
CinemaReady/
├── CinemaReady.xlsx
├── README.md
└── screenshots/
    ├── dashboard-overview.png
    ├── dashboard-readiness.png
    ├── incident-log.png
    ├── network-map.png
    ├── project-info-overview.png
    └── project-info-details.png
```

## Skills Demonstrated

- Microsoft Excel
- Excel formulas and conditional logic
- Basic IP addressing
- Basic ICMP and ping concepts
- IT support workflow
- Technical troubleshooting logic
- Incident classification
- Incident documentation
- Operational reporting
- Technical project documentation

## Project Scope and Limitations

CinemaReady is a beginner-level educational operational prototype.

- It does not perform live network scanning.
- It does not connect to real projectors, sound systems, or CCTV equipment.
- Ping and functional statuses are entered manually.
- A successful ping confirms only basic ICMP reachability.
- A successful ping does not prove that the device itself is functioning correctly.
- The network addresses and cinema equipment are simulated.

## Author

**Boyan Nikolov**

Aspiring IT Support and System Administration professional based in Sofia, Bulgaria.

[GitHub Profile](https://github.com/boyan-nk)
