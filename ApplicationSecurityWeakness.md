# Application Security Weaknesses

## Web Application Security Weaknesses

### Data Handling 
#### Injection flaws
- Code Injection 
- HTTP Injection 
- LDAP Injection 
- NoSQL Injection 
- OS Command Injection 
- Path Traversal
  Attackers try to access the files in the system by using the url path such as /.../wp-admin/photos/.....  Or by manipulating this url such as  /.../wp-admin/documents/.....
  To prevent this developrs must test the vunerabiloty and mitigate it.
- Local File Inclusion 
- Remote File Inclusion 
- SQL injection 
- XML Injection 
- XPath Injection 
- XQuery Injection 
- Email Injection 
- Deserialization of Untrusted Data 
- Log Forging 
- Resource Injection 
- CSS Injection 

### Authentication and Access Control

#### Access Control
Access control is a crucial aspect of web application security. Properly managing user permissions and restricting access to sensitive resources is essential to prevent unauthorized actions and data breaches.
- Preventing any data leakage by execuing a user check program for every request


### Insecure Development Practices

#### Logging & Monitoring

Effective logging and monitoring are essential components of access control. Insufficient or improper logging can prevent the detection of unauthorized access and other security incidents.

**Common Logging & Monitoring Weaknesses:**
- Insufficient Logging



### Security Misconfiguration 
#### Information Exposure
- using default account name and passwords
- debugging information was left enabled

#### Click Jacking
- luring a user to click to a vunerable are
  Ro resolve this developers should use content security policy headers

#### Disabled Security Features
- luring a user to click to a vunerable are
  Ro resolve this developers should use content security policy headers
- 
