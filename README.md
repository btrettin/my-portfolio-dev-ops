# my-portfolio-dev-ops

dev ops for my portfolio
CertificateArn=$(aws acm list-certificates --query "(CertificateSummaryList[?DomainName=='*.bentrettin.com'])[0].CertificateArn" --output text)
