# TODO: Fix Cancel Order 404 Error

## Steps to Complete
- [x] Add cancelOrder controller function in Backend/src/controllers/orderController.js to allow users to cancel their own orders if the status is 'processing' or 'new'.
- [x] Add PUT /profile/orders/:orderId route in Backend/src/routes/auth.js using the cancelOrder controller.
- [ ] Test the cancel order functionality in the frontend.
