# PDF Approval Tracker  

This project automates the tracking of PDFs sent to the board of directors. Using Microsoft Power Automate, it monitors document approvals, streamlining the approval process and ensuring efficient workflow management.  

---

## Features  
- **Automated PDF Tracking** – Logs PDFs sent for approval.  
- **Approval Status Updates** – Tracks whether board members have reviewed and approved documents.  
- **Microsoft Power Automate Integration** – Fully automated workflow.  
- **Efficient Document Management** – Reduces manual follow-ups and ensures transparency.  

---

## Installation & Setup  

### Prerequisites  
- Microsoft Power Automate account  
- Access to the document storage system (e.g., SharePoint, OneDrive)  
- Proper permissions to create and modify workflows  

### Deploy the Power Automate Workflow  
1. **Import the Workflow Package**  
   - Go to Power Automate → My Flows → Import a Flow.  
   - Upload the provided `.zip` package.  

2. **Configure Document Storage**  
   - Ensure that the PDF repository (e.g., SharePoint/OneDrive) is correctly linked.  
   - Adjust paths if necessary to match the document management structure.  

3. **Set Up Approval Logic**  
   - Define board members as approvers.  
   - Customize approval notifications and reminders.  

---

## Workflow Overview  
1. **PDF Submission** – A document is uploaded to the system.  
2. **Approval Request Sent** – Board members receive a notification.  
3. **Approval Tracking** – Responses are logged (approved/rejected).  
4. **Final Status Update** – Approval results are stored and accessible.  

---

## Deployment & Maintenance  
- **Testing**: Run test submissions to ensure proper tracking.  
- **Monitoring**: Check logs in Power Automate for errors.  
- **Updates**: Modify approval flow as needed to match board requirements.  

---

## Future Enhancements  
- Automated reminders for pending approvals  
- Dashboard for approval insights and metrics  
- Integration with external document management systems  

---

## License  
This project is intended for internal use.  

---

Built with Microsoft Power Automate for seamless document approval tracking. For modifications or troubleshooting, contact the project administrator.  
