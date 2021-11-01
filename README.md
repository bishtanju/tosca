
# Implemation of 150 Automated testcase for 5 different application as part of BAB

This Project include the implementation of the core funcationality of all the 5 different application.
Execute the e2e funcationality as part of new releases

## API Reference

For enabling the MFA and also for the activation of the added beneficiary to the account

#### Get all items

```http
  GET /api/items
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get item

```http
  GET /api/items/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |

## Demo

## Deployment

## Environment Variables

To run this project, we have added the global environment variable at the execution level of the testcase as Business parameter.This will maintain the list of variable as part of the testing





