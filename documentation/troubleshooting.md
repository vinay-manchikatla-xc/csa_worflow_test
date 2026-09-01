# Troubleshooting

## Common Issues

### Webhook Not Receiving Events

1. Check if the webhook URL is correct
2. Verify the secret matches
3. Check GitHub webhook delivery logs

### Signature Verification Failed

- Ensure the payload is not modified in transit
- Check that the secret is correct
- Verify the header `x-hub-signature-256` is present

### File Processing Errors

- Verify the file is a valid markdown file
- Check if the repository is accessible
- Ensure the branch name is correct
