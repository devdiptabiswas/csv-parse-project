## Overview

This project implements a feature in a Next.js application that allows users to upload CSV files containing user data. The uploaded files are parsed, and the user data is sent as API requests in a background job. This approach ensures efficient processing without blocking the main application thread.

## Features

File upload functionality using Multer.

CSV parsing and validation using csv-parser.

Background job processing with Bull and Redis.

API interactions using Axios or node-fetch.

Frontend UI for file upload and status feedback.

Robust error handling and logging mechanisms.
