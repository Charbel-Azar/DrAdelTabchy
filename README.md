# Dr. Adel Tabchy - Breast Health Guide

Patient-facing website for Dr. Adel Tabchy, Breast and Reconstructive Surgeon. Provides breast cancer prevention and treatment information, screening guidelines, and a WhatsApp link to book a consultation.

Live at https://dradeltabchy.vercel.app

## What it is

A single-page static website. All content lives in `index.html` with supporting styles, scripts, and images under `assets/`. Content is available in English, Arabic, and French.

## Stack

Plain HTML, CSS, and vanilla JavaScript. No build step. Deployed on Vercel.

## Running locally

Open `index.html` directly in a browser, or run `vercel dev` from the project root if the Vercel CLI is installed.

## Deploying

Run `vercel --prod` to push to production. The Vercel project is linked via the `.vercel/` folder.

## Files

- `index.html` is the full site
- `assets/` contains CSS, JavaScript, and images
- `vercel.json` is the hosting config
- `package.json` holds project metadata

## Note

The page title in `index.html` still references "Dr. John Doe" from the template. This should be replaced with Dr. Adel Tabchy's name before the site is linked from external sources.
