## **img2csv – Prepare eBay Listings from Photos**  
**Tech:** Django REST Framework (DRF), PostgreSQL  

### **Problem**  
Creating eBay listings is a time-consuming process. Taking and editing photos, removing backgrounds, and manually entering listing details require significant effort, especially for sellers who want clean, professional-looking product images.

### **Scope**  
Users can upload photos or take photos directly within the application.
Create new items with photos, category information, and shop/location details.
Generate listing content using an LLM API, or enter content manually.
Remove image backgrounds with a single click from the thumbnail view.
Background removal can be toggled on and off, allowing users to revert changes if the result is unsatisfactory.
Select multiple items and export them as CSV files for eBay bulk listing uploads.
Import and export item data for backup and migration purposes.
 
### **Outcome**
- Successfully deployed and used in an on-premises production environment for three months.
- Adopted by an organisation with two active users.
- Streamlined the eBay listing workflow by reducing the time required for photo processing, content generation, and listing publication.
