Travel Booking & Quotation Widget (Zoho CRM Embedded App)
📌 Overview

This project is a multi-step Travel Booking & Quotation Widget built as an embedded Zoho CRM application.
It allows sales or operations teams to create end-to-end travel quotations by selecting client details, hotels, rooms, activities, sub-activities, and transfers, with dynamic pricing and real-time summary generation.

The widget is designed to streamline the travel quotation workflow inside Zoho CRM, ensuring accuracy, flexibility, and an intuitive user experience.

🚀 Key Features
🧍 Client & Travel Information

Client name, country, city selection

Travel date range (From / To)

Dynamic city loading based on country

🏨 Hotel Selection

Fetch hotels directly from Zoho CRM

Filters:

Star rating (3★, 4★, 5★)

Area

Sharing capacity

Google rating and hotel amenities display

Single hotel selection with visual highlight

🛏️ Room Management

Fetch rooms linked to selected hotel

Multi-room selection supported

Dynamic pricing:

Base room price

Extra adult price

Child with bed

Child without bed

Real-time price recalculation

Quantity-based pricing logic

🎯 Activities & Sub-Activities

Activity selection by city

Multi-select activities

Expandable Sub-Activities

Adult & child counters per sub-activity

Price auto-calculation

Parent–child activity linking

🚐 Transfers & Sub-Transfers

Supports Private & Shared transfers

People-based pricing for shared transfers

Transfer capacity handling

Sub-transfers linked to sub-activities

Visual selection and state management

📊 Quote Summary

Auto-generated quotation summary table

Displays:

Hotels

Rooms

Activities

Sub-Activities

Transfers

Grand total calculation

Clean, readable breakdown

🔄 Step-by-Step Flow

Client Info

Hotel Selection

Room Selection

Activities & Transfers

Quote Summary & Save

Includes:

Progress bar

Back & Next navigation

Validation at each step

🛠️ Tech Stack

HTML5

Tailwind CSS (UI & styling)

JavaScript (Vanilla JS)

jQuery

Zoho CRM Embedded App SDK

Zoho CRM APIs

🔗 Zoho CRM Integration

This widget interacts with the following Zoho CRM modules:

Hotels

Rooms

Room_Prices

Activities

Activities_Details

Activity_Price

Transfers

Sub_Transfer

Transfer_Price

All data is fetched dynamically using:

ZOHO.CRM.API.searchRecord

ZOHO.CRM.API.getAllRecords
