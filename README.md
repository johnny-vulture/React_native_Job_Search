# React Native Job Search

A React Native job search app built with Expo and Expo Router. Browse popular and nearby roles, search by keyword or job type, and open detailed listings powered by the [JSearch](https://rapidapi.com/letscrape-6bRBa3QguO5/api/jsearch) API on RapidAPI.

## Features

- Home screen with personalized welcome, search bar, and job-type filters (Full-time, Part-time, Contractor)
- Popular jobs carousel and nearby jobs list
- Search results with pagination
- Job details with About, Qualifications, and Responsibilities tabs
- Apply button that opens the listing URL
- Pull-to-refresh on the job details screen
- Custom DM Sans typography and themed UI

## Tech Stack

- React Native / Expo
- Expo Router (file-based navigation)
- Axios
- JSearch API (RapidAPI)

## Project Structure

```text
app/                 # Screens (Expo Router)
  index.js           # Home
  search/[id].js     # Search results
  job-details/[id].js
components/          # UI components (home, cards, job details)
constants/           # Theme, icons, images
hook/useFetch.js     # Shared API fetch hook
styles/              # Shared styles
assets/              # Fonts, icons, images
