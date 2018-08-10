import json
import requests

api_url = 'https://rfw-svc.trafficmanager.net/api/Application/HealthAppBuildBranchMetrics'
create_row_data = {'filters': {'EntityId': '7c1d3b2de1bda60df9d26e5a1539ba0c'}, 'aggregationLevel': 'NamePublisherVersion'}
r = requests.post(url=api_url, json=create_row_data)
print(r.status_code, r.reason, r.text)
