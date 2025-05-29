FROM n8nio/n8n

# Required environment variables
ENV N8N_HOST=0.0.0.0
ENV N8N_PORT=5678
ENV N8N_BASIC_AUTH_ACTIVE=true
ENV N8N_BASIC_AUTH_USER=admin
ENV N8N_BASIC_AUTH_PASSWORD=admin
ENV WEBHOOK_URL=https://yourproject.up.railway.app
ENV N8N_ENFORCE_SETTINGS_FILE_PERMISSIONS=false

EXPOSE 5678

# Use absolute path to avoid "command not found" error
CMD ["/usr/local/lib/node_modules/n8n/bin/n8n"]
