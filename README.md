```json
{
  "Result": {
    "transaction_hash": "0x16d355b37133cc5a356d41976d15a167807ee7f3c7c4c1b49af114565f803942",
    "gas_used": 8216,
    "gas_unit_price": 100,
    "sender": "b921408807cd2c075b63d6ea867485d4dc3e71e04ae3f4b86e8e328c73e10972",
    "sequence_number": 0,
    "success": true,
    "timestamp_us": 1666448024207169,
    "version": 20220068,
    "vm_status": "Executed successfully"
  }
}
```

```JSON
{
  "tx": {
    "version": "20457447",
    "hash": "0xc629b04fadc4711038fea157232ba5371844cc51c21a2e2466d6135a00878a8a",
    "state_change_hash": "0x90d873ba59171435c69edb9168a5b036ab09d1fdf7475df63e5f8db2fd874353",
    "event_root_hash": "0xf1807f64df6a187035658e096fef6353498198e6d9b54263b296665b41e287eb",
    "state_checkpoint_hash": null,
    "gas_used": "1000",
    "success": true,
    "vm_status": "Executed successfully",
    "accumulator_root_hash": "0x01eb9716adf747a1bd453e2760066b447e8d8830bdfe180d8bc7bf9159ad719d",
    "changes": [
      {
        "address": "0xb921408807cd2c075b63d6ea867485d4dc3e71e04ae3f4b86e8e328c73e10972",
        "state_key_hash": "0xe686d544f3a3c91aace2fbb72e478a2859ec8c2cc73aaffb76c8ad40c08f515e",
        "data": {
          "type": "0x1::coin::CoinStore<0x1::aptos_coin::AptosCoin>",
          "data": {
            "coin": {
              "value": "96111400"
            },
            "deposit_events": {
              "counter": "4",
              "guid": {
                "id": {
                  "addr": "0xb921408807cd2c075b63d6ea867485d4dc3e71e04ae3f4b86e8e328c73e10972",
                  "creation_num": "2"
                }
              }
            },
            "frozen": false,
            "withdraw_events": {
              "counter": "0",
              "guid": {
                "id": {
                  "addr": "0xb921408807cd2c075b63d6ea867485d4dc3e71e04ae3f4b86e8e328c73e10972",
                  "creation_num": "3"
                }
              }
            }
          }
        },
        "type": "write_resource"
      },
      {
        "address": "0xb921408807cd2c075b63d6ea867485d4dc3e71e04ae3f4b86e8e328c73e10972",
        "state_key_hash": "0xbb3adaed98e56a3eb8f50ca853164e6a7a0f59abe3cf9a5c37ac5ad697802a39",
        "data": {
          "type": "0x1::coin::CoinStore<0xb921408807cd2c075b63d6ea867485d4dc3e71e04ae3f4b86e8e328c73e10972::dogecoinV2::DogeCoin>",
          "data": {
            "coin": {
              "value": "0"
            },
            "deposit_events": {
              "counter": "0",
              "guid": {
                "id": {
                  "addr": "0xb921408807cd2c075b63d6ea867485d4dc3e71e04ae3f4b86e8e328c73e10972",
                  "creation_num": "4"
                }
              }
            },
            "frozen": false,
            "withdraw_events": {
              "counter": "0",
              "guid": {
                "id": {
                  "addr": "0xb921408807cd2c075b63d6ea867485d4dc3e71e04ae3f4b86e8e328c73e10972",
                  "creation_num": "5"
                }
              }
            }
          }
        },
        "type": "write_resource"
      },
      {
        "address": "0xb921408807cd2c075b63d6ea867485d4dc3e71e04ae3f4b86e8e328c73e10972",
        "state_key_hash": "0xdab6b868b6edcce613926477d0430af4adea879d097c5192e15add02fface506",
        "data": {
          "type": "0x1::account::Account",
          "data": {
            "authentication_key": "0xb921408807cd2c075b63d6ea867485d4dc3e71e04ae3f4b86e8e328c73e10972",
            "coin_register_events": {
              "counter": "2",
              "guid": {
                "id": {
                  "addr": "0xb921408807cd2c075b63d6ea867485d4dc3e71e04ae3f4b86e8e328c73e10972",
                  "creation_num": "0"
                }
              }
            },
            "guid_creation_num": "6",
            "key_rotation_events": {
              "counter": "0",
              "guid": {
                "id": {
                  "addr": "0xb921408807cd2c075b63d6ea867485d4dc3e71e04ae3f4b86e8e328c73e10972",
                  "creation_num": "1"
                }
              }
            },
            "rotation_capability_offer": {
              "for": {
                "vec": []
              }
            },
            "sequence_number": "8",
            "signer_capability_offer": {
              "for": {
                "vec": []
              }
            }
          }
        },
        "type": "write_resource"
      },
      {
        "state_key_hash": "0x6e4b28d40f98a106a65163530924c0dcb40c1349d3aa915d108b4d6cfc1ddb19",
        "handle": "0x1b854694ae746cdbd8d44186ca4929b2b337df21d1c74633be19b2710552fdca",
        "key": "0x0619dc29a0aac8fa146714058e8dd6d2d0f3bdf5f6331907bf91f3acd81e6935",
        "value": "0x53188f8acd1d0b000100000000000000",
        "data": null,
        "type": "write_table_item"
      }
    ],
    "sender": "0xb921408807cd2c075b63d6ea867485d4dc3e71e04ae3f4b86e8e328c73e10972",
    "sequence_number": "7",
    "max_gas_amount": "1932",
    "gas_unit_price": "100",
    "expiration_timestamp_secs": "1666452320",
    "payload": {
      "function": "0xb921408807cd2c075b63d6ea867485d4dc3e71e04ae3f4b86e8e328c73e10972::dogecoinV2::register",
      "type_arguments": [],
      "arguments": [],
      "type": "entry_function_payload"
    },
    "signature": {
      "public_key": "0xd72ecdbfe6bca1cb202e9fb8b970a0d166dfbf836bb7cc20b489d53c173ff863",
      "signature": "0x36283d53de56e9a9f77e5ddcb65209fbc2ced29b2633c2dbc6c07fbf9479fdc81189041595f2a1244b7083e1e1918e7e6f9320d1c8465570871939181accdb0e",
      "type": "ed25519_signature"
    },
    "events": [
      {
        "guid": {
          "creation_number": "0",
          "account_address": "0xb921408807cd2c075b63d6ea867485d4dc3e71e04ae3f4b86e8e328c73e10972"
        },
        "sequence_number": "1",
        "type": "0x1::account::CoinRegisterEvent",
        "data": {
          "type_info": {
            "account_address": "0xb921408807cd2c075b63d6ea867485d4dc3e71e04ae3f4b86e8e328c73e10972",
            "module_name": "0x646f6765636f696e5632",
            "struct_name": "0x446f6765436f696e"
          }
        }
      }
    ],
    "timestamp": "1666452301391364",
    "type": "user_transaction"
  }
}
```

0xb921408807cd2c075b63d6ea867485d4dc3e71e04ae3f4b86e8e328c73e10972::dogecoinV2::DogeCoin
