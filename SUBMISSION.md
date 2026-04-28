# Submission

## Deployed Links
- Frontend: _Add your deployed frontend URL here_
- Backend: _Add your deployed backend URL here_

## Completed Features
- Backend model extended with `description` and `category` fields
- `POST /api/items` supports `name`, `price`, `description`, and `category`
- `DELETE /api/items/:id` implemented
- Frontend form includes `description` and `category`
- Items list displays `description` and `category`
- Delete button removes an item from the backend and refreshes the UI

## Deployment Verification
1. Deployed backend properly configured with `MONGO_URI`
2. Deployed frontend configured to use the backend API URL
3. CORS allowed between frontend and backend deployments

## Screenshots
- Screenshot 1: Working UI showing items with `description` and `category`
- Screenshot 2: MongoDB Atlas collection view showing saved items
- Screenshot 3: Deployment dashboard showing live/success status

## Notes
- Fill in the deployment URLs and attach screenshots before submitting.
- The frontend uses `VITE_API_URL` from `frontend/.env` to target the deployed backend.
