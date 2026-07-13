# Project Documentation - Travel Hunt Tech / Comment AutoReply Buddy

This file is internal documentation only. It is not linked from any page on the live site.

## 1. What this repo is

This repository (travelhunttech-website) is the source for the public business website travelhunttech.com. Its main purpose is to satisfy Meta's Business Verification and App Review requirements for a separate project, the Comment AutoReply Buddy Instagram app, by providing a real, verifiable business presence online.

## 2. Hosting and domain setup

Host: GitHub Pages
Repo: lpant29-cmyk/travelhunttech-website (public)
Branch: main, root folder
Custom domain: travelhunttech.com (set via CNAME file in repo root)
DNS: verified successful with GitHub Pages
HTTPS: Enforce HTTPS is enabled and confirmed working

## 3. Pages in this repo

index.html - homepage
about.html - about the business
services.html - services offered
contact.html - contact details, email travelhunttech@gmail.com
privacy.html - privacy policy
terms.html - terms of service
style.css - shared stylesheet
CNAME - custom domain config for GitHub Pages
README.md - repo readme
PROJECT-DOCS.md - this file

All pages share a footer with links to Privacy Policy and Terms of Service.

## 4. Related project - Comment AutoReply Buddy

Separate GitHub repo: lpant29-cmyk/comment-autoreply-buddy
What it does: Instagram comment auto-reply tool using Claude API and Instagram Graph API
Built for Instagram account: ektafitnessflow (wife's account), possible future commercial use

## 5. Meta / Facebook Developer setup

Meta App name: Comment AutoReply Buddy
App ID: 880401361807320
Basic Settings status: Category set to Business and pages, app icon uploaded, previously showed Currently ineligible for submission banner which has now cleared
Terms of Service URL field: intentionally left empty until business verification completes. Planned value: https://travelhunttech.com/terms.html
App domains field: intentionally left empty until business verification completes. Planned value: travelhunttech.com
App Review: not yet submitted, draft has 5 permissions queued - instagram_business_basic, instagram_business_manage_messages, instagram_manage_comments, instagram_business_manage_comments, public_profile

## 6. Meta Business Verification

Business ID: 470638335908380
Business name: Travel Hunt Group
Website on file: https://travelhunttech.com/
Phone on file: +91 7838349999
Status as of last check: In review (Meta indicated up to about two working days)

## 7. Outstanding next steps

1. Wait for Meta business verification decision
2. Once approved, set Terms of Service URL and App domains fields in Meta Basic Settings
3. Submit Meta App Review with the 5 queued permissions
4. After approval, connect and test the auto-reply flow on ektafitnessflow
