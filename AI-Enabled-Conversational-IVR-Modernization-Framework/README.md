# IVR to Conversational AI Middleware/API Layer

## Objective
Build a middleware/API layer to connect legacy IVRs to the Conversational AI stack, enabling smooth communication and real-time data exchange.

## Features / Tasks Completed
1. **API/Connector Implementation**  
   - Developed connectors to link VXML-based IVR systems to ACS/BAP (Conversational AI Services / Bot Application Platform).  
   - Supports basic request-response handling between IVR and AI stack.

2. **Real-Time Data Handling**  
   - Ensures messages and transactions are processed in real-time.  
   - Handles asynchronous communication and concurrent requests from multiple IVRs.

3. **Integration Validation**  
   - Sample transaction flows tested for end-to-end communication.  
   - Verified data integrity and compatibility between legacy IVR responses and AI stack.

## Technologies Used
- **Backend:** Node.js / Express  
- **API Protocols:** REST / JSON  
- **Testing:** Postman / Axios scripts for sample transaction flow

## Project Structure
```
ivr-middleware/
├── src/
│   ├── api/             # API endpoints for IVR to AI communication
│   ├── connectors/      # VXML and ACS/BAP integration code
│   ├── tests/           # Sample transaction & flow tests
│   └── app.js           # Entry point
├── README.md
├── package.json
└── .gitignore
```

## Sample Usage / Flow Test
```bash
# Start the middleware
npm start

# Sample API request from IVR
node src/tests/sampleTest.js
```

**Expected Response:**  
```json
{
  "status": "success",
  "response": "Your balance is $250"
}
```

## Notes
- Can be extended to multiple IVR systems and different Conversational AI stacks.  
- Real-time testing logs included in `/tests/`.