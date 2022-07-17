# Pipeline process

## It uses CircleCi Version 2 and has 3 steps

- ### Build Step

  1. Install node.js version 14.19.0
  1. Install the frontend and backend dependencies
  1. Run the frontend lint script
  1. Run the build script for the frontend and backend

- ### Approval Step

  1. Wait for admin approval

- ### Build Step

  1. Install node.js version 14.19.0
  1. Set up EB cli
  1. Install and configure AWS cli
  1. Configure AWS access keys
  1. Run deploy script for frontend and backend
