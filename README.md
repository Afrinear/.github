# Afrinear – Multi-Module Commerce & Services Ecosystem

Afrinear is a unified digital ecosystem designed to connect customers, sellers, service providers, and delivery riders through a single, API-driven backend architecture.
This repository represents the coordinated development of the 27-week Afrinear MVP, which includes five core applications and an administrative dashboard.

## 📌 Purpose

This document outlines the functional scope, technical expectations, acceptance criteria, and deliverables for the Afrinear MVP.
The MVP covers five primary modules:

Customer Application

Seller Application (Restaurants + All Shops)

Delivery Rider Application

Services Application

Administrative Dashboard

Afrinear is designed with a modular, API-driven architecture that supports seamless integration of future modules such as utilities, business scheduling, and five or more additional verticals in later development phases.

## 🛠️ General Technical Requirements
Technology Stack

Mobile Apps: Flutter or React Native

Backend & API: Laravel / Node.js / Firebase (or equivalent scalable service)

Architecture: Single shared backend consumed by all apps (REST APIs)

Hosting: Google Cloud, AWS, or Firebase (under Afrinear’s cloud account)

Source Control & DevOps

GitHub or GitLab repository owned by Afrinear

Continuous push access required for all development teams

Modular repositories encouraged for scalability

Security

All API calls authenticated with token-based security

All endpoints served over SSL/HTTPS

UI/UX Workflow

Every screen, feature, or user flow must be wireframed or sketched

Afrinear must review and approve designs before implementation

## 📱 Module-Specific Requirements & Acceptance Criteria
1. Customer Application
Features

Account registration/login (Email, Phone, Social Logins)

Home screen with search and category browsing

Product/service detail pages (images, pricing, reviews)

Add to cart, checkout, and payment gateway integration

Real-time order tracking (Pending → Confirmed → Out for Delivery → Completed)

Profile dashboard (orders, addresses, settings)

Acceptance Criteria

All flows function smoothly on Android & iOS

Order and payment data persist via API

No critical errors during login, checkout, or navigation


2. Seller Application (Restaurants + Shops)
Features

Vendor onboarding & Admin approval

Product/menu management with images & stock status

Order notifications and fulfilment workflow

Sales analytics dashboard

(Optional MVP) In-app messaging or notifications

Dynamic category management controlled from Admin Dashboard

Acceptance Criteria

Sellers can add/manage products and fulfil orders

Restaurant/shop data displays correctly in Customer App

Real-time order status sync between Seller, Customer, and Rider apps

3. Delivery Rider Application
Features

Rider login & Admin verification

Assigned orders list with pickup/drop-off locations

Map integration for navigation

Status updates (Picked Up → On Route → Delivered)

Daily/weekly earnings summary

Acceptance Criteria

Status updates sync across Customer and Seller apps

GPS tracking and maps function reliably

No API sync-related errors

4. Services Application
Features

Provider registration and profile setup

Service category listings (e.g., cleaning, repairs, tutoring)

Customer booking flow with scheduling options

Booking management (Accept / Decline / Complete)

Ratings & reviews

Acceptance Criteria

Providers can be discovered and booked by customers

Confirmed bookings appear for both Customer & Provider

No critical errors in booking or notification flows

5. Administrative Dashboard
Features

Super Admin login with role-based permissions

Unified management of Customers, Vendors, Riders, and Service Providers

Approve, suspend, or update vendor/user accounts

Manage categories, delivery zones, and locations

Reporting (sales, transactions, user growth)

Basic content management (banners, announcements)

Acceptance Criteria

Admin can manage all records without errors

Data updates reflect across all applications

Reports exportable to CSV or PDF

## 📦 Deliverables Per Milestone

(Your internal team can expand this section based on finalized milestone planning.)

🌍 Afrinear Vision

Afrinear aims to become a unified platform where everyday commerce meets on-demand services — empowering local businesses, supporting riders, and delivering convenience to customers across Africa and beyond.
