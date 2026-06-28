# partner-targets.md

## Partner Integration Roadmap for ipv-guard

### Target Integrations

| Partner/API               | Free-Tier Limits                     | Integration Effort | Value-Add (User Job Solved)                                       | Affiliate/Revenue-Share |
|---------------------------|-------------------------------------|--------------------|-------------------------------------------------------------------|--------------------------|
| AWS VPC                   | Free tier for 1 VPC, 1 GB data out | M                  | Simplifies IPv6 prefix management in cloud environments.          | Yes                      |
| Google Cloud VPC          | Free tier for 1 VPC, 1 GB data out | M                  | Enhances network configuration for developers using GCP.         | Yes                      |
| Azure Virtual Network      | Free tier for 1 VNet, 5 GB data out| M                  | Facilitates IPv6 prefix management for Azure users.               | Yes                      |
| Cloudflare DNS            | Free tier for 1 domain             | S                  | Automates DNS management for IPv6 addresses.                      | Yes                      |
| DigitalOcean Networking    | Free tier for 1 droplet, 1 TB data | M                  | Streamlines IPv6 prefix management for DigitalOcean users.        | Yes                      |
| Netlify                   | Free tier for 300 build minutes    | S                  | Integrates IPv6 management with static site deployments.          | No                       |
| Heroku                    | Free tier for 550 dyno hours/month | M                  | Simplifies IPv6 prefix management for app developers.             | No                       |
| Terraform                 | Open-source (no free tier limits)  | L                  | Automates infrastructure management and integrates with ipv-guard. | No                       |

### Rationale for Selection

1. **AWS VPC, Google Cloud VPC, Azure Virtual Network**: These are leading cloud service providers where many organizations deploy their applications. Integrating with these platforms will allow ipv-guard to provide seamless IPv6 prefix management directly within the cloud environments, addressing a significant pain point for developers and network administrators.

2. **Cloudflare DNS**: As a widely used DNS provider, integrating with Cloudflare will allow users to automate the management of their IPv6 addresses, enhancing the usability of ipv-guard for web applications.

3. **DigitalOcean Networking**: DigitalOcean is popular among startups and developers. Integrating with their networking services will help ipv-guard capture a segment of the market focused on simplicity and ease of use.

4. **Netlify and Heroku**: While these platforms are not primarily focused on networking, they are popular among developers for deploying applications. Integrating with them can provide additional value to users looking to manage their IPv6 addresses in conjunction with their application deployments.

5. **Terraform**: Although not a SaaS product with a free tier, Terraform is widely used for infrastructure as code. Integrating ipv-guard with Terraform will allow users to automate their IPv6 prefix management as part of their deployment pipelines, significantly enhancing the product's value proposition.

### Prioritization

The integrations are prioritized based on their relevance to the target user base, potential for affiliate/revenue-share opportunities, and the integration effort required. The focus is on cloud service providers and DNS management platforms that can directly enhance the user experience with ipv-guard.