const express = require('express');
const app = express();
const port = process.env.PORT || 5000;

// Middleware
app.use(express.json());

// Test Route
app.get('/', (req, res) => {
  res.send('🎉 IELTS Mock Platform Backend is running!');
});

// Start server
app.listen(port, () => {
  console.log(`🚀 Server is listening on port ${port}`);
});


