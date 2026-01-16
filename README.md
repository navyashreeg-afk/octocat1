Fix README typo
curl -X POST https://staging-backend.composio.dev/api/v3/tools/execute/GITHUB_LIST_PULL_REQUESTS \
  -H "x-api-key: ak_lDBNnsZZVrzjCaTiI_c0" \
  -H "Content-Type: application/json" \
  -d '{
    "connected_account_id": "ca_G7X1zJYijWfb",
    "version": "19260116_00",
    "arguments": {
      "owner": "navyashreeg-afk",
      "repo": "octocat1",
      "state": "open"
    }
  }'
