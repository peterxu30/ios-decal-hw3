# Bounce Me

## Authors
* Peter Xu

## Purpose
	When ya need to keep posers out da club.
	A phone based check-in system where only pre-approved
	users can sign in.

## Features
* Add users to a check-in list
* Users can check-in through a local network i.e. Multipeer Connectivity
* Notifies the "bouncer" phone of failed attempted check-ins

## Control Flow
* There are two views, one for bouncer and one for guest.
* The bouncer creates a list of accepted users before hand.
* On event day, bouncer will turn on check-ins
* Registered users turn on the app and connect to bouncer phone to sign in.
* Bouncer can see who has signed in as checkmarks on the guestlist.

## Implementation
### Model
* GuestList.swift

### View
* GuestListTableView
* AddGuestToGuestListPage
* GuestCheckInPage

### Controller
* GuestListViewController.swift
* AddGuestToGuestListViewController.swift
* GuestCheckInPageViewController.swift

