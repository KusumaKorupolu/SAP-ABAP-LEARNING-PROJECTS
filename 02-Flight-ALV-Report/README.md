# Flight ALV Report

## 📌 Project Overview

This is one of my SAP ABAP learning projects focused on building a Flight ALV Report.

The report works with the SAP `SFLIGHT` table and displays selected flight information using an ALV Grid.

This project helped me practice ALV concepts and understand how structured business data can be retrieved, processed and presented in an ALV report.

## 🛠️ Technologies & Concepts

- SAP ABAP
- ALV Report
- SFLIGHT Table
- Selection Screen
- Internal Tables
- Work Areas
- Field Catalog
- ALV Layout
- ALV Events
- USER_COMMAND
- REUSE_ALV_EVENTS_GET
- REUSE_ALV_GRID_DISPLAY
- Form Routines

## 🔄 Report Flow

Selection Screen
        ↓
Enter Carrier ID / Connection ID
        ↓
Read Data from SFLIGHT
        ↓
Store Data in Internal Table
        ↓
Build ALV Field Catalog
        ↓
Prepare ALV Events & Layout
        ↓
Display ALV Grid
        ↓
Handle ALV User Command

## 📊 Selection Criteria

The report provides selection options for:

- Carrier ID (`CARRID`)
- Connection ID (`CONNID`)

The selected values are used to retrieve matching records from the `SFLIGHT` table.

## 📋 ALV Output

The report displays flight information including:

- Carrier
- Connection
- Flight Date
- Price
- Currency
- Seats Maximum
- Seats Occupied

## ⚙️ ALV Features Practiced

### Field Catalog

The field catalog is built dynamically to define the columns displayed in the ALV output.

### Layout

The ALV layout includes:

- Zebra pattern
- Optimized column width

### Events

The report retrieves ALV events using:

`REUSE_ALV_EVENTS_GET`

The `USER_COMMAND` event is handled to respond to ALV user actions.

### ALV Display

The report uses:

`REUSE_ALV_GRID_DISPLAY`

to display the flight information in an ALV Grid.

## 🎯 Learning Outcomes

Through this project, I practiced:

- Working with the SFLIGHT table
- Selection-screen processing
- Internal table processing
- Building an ALV field catalog
- Configuring ALV layout
- Working with ALV events
- Handling USER_COMMAND
- Displaying structured business data using ALV

## 📄 Documentation

The project documentation contains screenshots of the ABAP program and its development process.

## 🚀 Learning Journey

This is one of the projects from my SAP ABAP learning journey.

It is not my final or only project. I have continued practicing different areas of ABAP, including Classical Reports, ALV and OO ABAP.

I am sharing these projects to document my progress and learning journey.

> Learning ABAP one project at a time. 🚀
