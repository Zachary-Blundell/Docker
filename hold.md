.
|-- README.md
|-- guacamole
|   `-- compose.yml
|-- hold.md
|-- homepage
|   |-- compose.yml
|   `-- config
|       |-- bookmarks.yaml
|       |-- custom.css
|       |-- custom.js
|       |-- docker.yaml
|       |-- kubernetes.yaml
|       |-- logs
|       |   `-- homepage.log
|       |-- proxmox.yaml
|       |-- services.yaml
|       |-- settings.yaml
|       |-- settings.yml
|       `-- widgets.yaml
|-- monitoring
|   |-- cadvisor
|   |   `-- compose.yml
|   |-- compose.yml
|   |-- grafana
|   |   `-- compose.yml
|   `-- prometheus
|       `-- compose.yml
|-- nextcloud
|   |-- nextcloud
|   |   `-- compose.yml
|   |-- onlyoffice
|   |   `-- compose.yml
|   `-- whiteboard
|       `-- compose.yml
|-- open-webui
|   `-- compose.yaml
|-- pi-hole
|   |-- compose.yaml
|   |-- etc-dnsmasq.d
|   `-- etc-pihole
|       |-- adlists.list
|       |-- cli_pw
|       |-- config_backups
|       |   |-- pihole.toml.1
|       |   |-- pihole.toml.2
|       |   |-- pihole.toml.3
|       |   |-- pihole.toml.4
|       |   |-- pihole.toml.5
|       |   |-- pihole.toml.6
|       |   |-- pihole.toml.7
|       |   `-- pihole.toml.8
|       |-- dhcp.leases
|       |-- dnsmasq.conf
|       |-- gravity.db
|       |-- gravity_backups
|       |   |-- gravity.db.1
|       |   `-- gravity.db.2
|       |-- gravity_old.db
|       |-- hosts
|       |   `-- custom.list
|       |-- listsCache
|       |   |-- list.1.raw.githubusercontent.com.domains
|       |   |-- list.1.raw.githubusercontent.com.domains.etag
|       |   `-- list.1.raw.githubusercontent.com.domains.sha1
|       |-- logrotate
|       |-- migration_backup
|       |   `-- adlists.list
|       |-- pihole-FTL.db
|       |-- pihole-FTL.db-shm
|       |-- pihole-FTL.db-wal
|       |-- pihole.toml
|       |-- tls.crt
|       |-- tls.pem
|       |-- tls_ca.crt
|       `-- versions
|-- portainer
|   `-- compose.yaml
|-- proxy
|   |-- compose.yml
|   |-- data
|   |   |-- access
|   |   |   `-- 1
|   |   |-- custom_ssl
|   |   |-- database.sqlite
|   |   |-- keys.json
|   |   |-- letsencrypt-acme-challenge
|   |   |-- logs
|   |   |   |-- fallback_access.log
|   |   |   |-- fallback_access.log.1.gz
|   |   |   |-- fallback_access.log.2.gz
|   |   |   |-- fallback_access.log.3.gz
|   |   |   |-- fallback_access.log.4.gz
|   |   |   |-- fallback_error.log
|   |   |   |-- fallback_error.log.1.gz
|   |   |   |-- fallback_error.log.10.gz
|   |   |   |-- fallback_error.log.2.gz
|   |   |   |-- fallback_error.log.3.gz
|   |   |   |-- fallback_error.log.4.gz
|   |   |   |-- fallback_error.log.5.gz
|   |   |   |-- fallback_error.log.6.gz
|   |   |   |-- fallback_error.log.7.gz
|   |   |   |-- fallback_error.log.8.gz
|   |   |   |-- fallback_error.log.9.gz
|   |   |   |-- fallback_http_access.log
|   |   |   |-- fallback_http_access.log.1.gz
|   |   |   |-- fallback_http_access.log.2.gz
|   |   |   |-- fallback_http_access.log.3.gz
|   |   |   |-- fallback_http_access.log.4.gz
|   |   |   |-- fallback_http_error.log
|   |   |   |-- fallback_http_error.log.1.gz
|   |   |   |-- fallback_http_error.log.2.gz
|   |   |   |-- fallback_http_error.log.3.gz
|   |   |   |-- fallback_http_error.log.4.gz
|   |   |   |-- fallback_http_error.log.5.gz
|   |   |   |-- fallback_http_error.log.6.gz
|   |   |   |-- fallback_http_error.log.7.gz
|   |   |   |-- fallback_stream_access.log
|   |   |   |-- letsencrypt-requests_access.log
|   |   |   |-- letsencrypt-requests_access.log.1.gz
|   |   |   |-- letsencrypt-requests_access.log.2.gz
|   |   |   |-- letsencrypt-requests_access.log.3.gz
|   |   |   |-- letsencrypt-requests_access.log.4.gz
|   |   |   |-- letsencrypt-requests_error.log
|   |   |   |-- letsencrypt.log
|   |   |   |-- letsencrypt.log.1
|   |   |   |-- letsencrypt.log.10
|   |   |   |-- letsencrypt.log.100
|   |   |   |-- letsencrypt.log.1000
|   |   |   |-- letsencrypt.log.101
|   |   |   |-- letsencrypt.log.102
|   |   |   |-- letsencrypt.log.103
|   |   |   |-- letsencrypt.log.104
|   |   |   |-- letsencrypt.log.105
|   |   |   |-- letsencrypt.log.106
|   |   |   |-- letsencrypt.log.107
|   |   |   |-- letsencrypt.log.108
|   |   |   |-- letsencrypt.log.109
|   |   |   |-- letsencrypt.log.11
|   |   |   |-- letsencrypt.log.110
|   |   |   |-- letsencrypt.log.111
|   |   |   |-- letsencrypt.log.112
|   |   |   |-- letsencrypt.log.113
|   |   |   |-- letsencrypt.log.114
|   |   |   |-- letsencrypt.log.115
|   |   |   |-- letsencrypt.log.116
|   |   |   |-- letsencrypt.log.117
|   |   |   |-- letsencrypt.log.118
|   |   |   |-- letsencrypt.log.119
|   |   |   |-- letsencrypt.log.12
|   |   |   |-- letsencrypt.log.120
|   |   |   |-- letsencrypt.log.121
|   |   |   |-- letsencrypt.log.122
|   |   |   |-- letsencrypt.log.123
|   |   |   |-- letsencrypt.log.124
|   |   |   |-- letsencrypt.log.125
|   |   |   |-- letsencrypt.log.126
|   |   |   |-- letsencrypt.log.127
|   |   |   |-- letsencrypt.log.128
|   |   |   |-- letsencrypt.log.129
|   |   |   |-- letsencrypt.log.13
|   |   |   |-- letsencrypt.log.130
|   |   |   |-- letsencrypt.log.131
|   |   |   |-- letsencrypt.log.132
|   |   |   |-- letsencrypt.log.133
|   |   |   |-- letsencrypt.log.134
|   |   |   |-- letsencrypt.log.135
|   |   |   |-- letsencrypt.log.136
|   |   |   |-- letsencrypt.log.137
|   |   |   |-- letsencrypt.log.138
|   |   |   |-- letsencrypt.log.139
|   |   |   |-- letsencrypt.log.14
|   |   |   |-- letsencrypt.log.140
|   |   |   |-- letsencrypt.log.141
|   |   |   |-- letsencrypt.log.142
|   |   |   |-- letsencrypt.log.143
|   |   |   |-- letsencrypt.log.144
|   |   |   |-- letsencrypt.log.145
|   |   |   |-- letsencrypt.log.146
|   |   |   |-- letsencrypt.log.147
|   |   |   |-- letsencrypt.log.148
|   |   |   |-- letsencrypt.log.149
|   |   |   |-- letsencrypt.log.15
|   |   |   |-- letsencrypt.log.150
|   |   |   |-- letsencrypt.log.151
|   |   |   |-- letsencrypt.log.152
|   |   |   |-- letsencrypt.log.153
|   |   |   |-- letsencrypt.log.154
|   |   |   |-- letsencrypt.log.155
|   |   |   |-- letsencrypt.log.156
|   |   |   |-- letsencrypt.log.157
|   |   |   |-- letsencrypt.log.158
|   |   |   |-- letsencrypt.log.159
|   |   |   |-- letsencrypt.log.16
|   |   |   |-- letsencrypt.log.160
|   |   |   |-- letsencrypt.log.161
|   |   |   |-- letsencrypt.log.162
|   |   |   |-- letsencrypt.log.163
|   |   |   |-- letsencrypt.log.164
|   |   |   |-- letsencrypt.log.165
|   |   |   |-- letsencrypt.log.166
|   |   |   |-- letsencrypt.log.167
|   |   |   |-- letsencrypt.log.168
|   |   |   |-- letsencrypt.log.169
|   |   |   |-- letsencrypt.log.17
|   |   |   |-- letsencrypt.log.170
|   |   |   |-- letsencrypt.log.171
|   |   |   |-- letsencrypt.log.172
|   |   |   |-- letsencrypt.log.173
|   |   |   |-- letsencrypt.log.174
|   |   |   |-- letsencrypt.log.175
|   |   |   |-- letsencrypt.log.176
|   |   |   |-- letsencrypt.log.177
|   |   |   |-- letsencrypt.log.178
|   |   |   |-- letsencrypt.log.179
|   |   |   |-- letsencrypt.log.18
|   |   |   |-- letsencrypt.log.180
|   |   |   |-- letsencrypt.log.181
|   |   |   |-- letsencrypt.log.182
|   |   |   |-- letsencrypt.log.183
|   |   |   |-- letsencrypt.log.184
|   |   |   |-- letsencrypt.log.185
|   |   |   |-- letsencrypt.log.186
|   |   |   |-- letsencrypt.log.187
|   |   |   |-- letsencrypt.log.188
|   |   |   |-- letsencrypt.log.189
|   |   |   |-- letsencrypt.log.19
|   |   |   |-- letsencrypt.log.190
|   |   |   |-- letsencrypt.log.191
|   |   |   |-- letsencrypt.log.192
|   |   |   |-- letsencrypt.log.193
|   |   |   |-- letsencrypt.log.194
|   |   |   |-- letsencrypt.log.195
|   |   |   |-- letsencrypt.log.196
|   |   |   |-- letsencrypt.log.197
|   |   |   |-- letsencrypt.log.198
|   |   |   |-- letsencrypt.log.199
|   |   |   |-- letsencrypt.log.2
|   |   |   |-- letsencrypt.log.20
|   |   |   |-- letsencrypt.log.200
|   |   |   |-- letsencrypt.log.201
|   |   |   |-- letsencrypt.log.202
|   |   |   |-- letsencrypt.log.203
|   |   |   |-- letsencrypt.log.204
|   |   |   |-- letsencrypt.log.205
|   |   |   |-- letsencrypt.log.206
|   |   |   |-- letsencrypt.log.207
|   |   |   |-- letsencrypt.log.208
|   |   |   |-- letsencrypt.log.209
|   |   |   |-- letsencrypt.log.21
|   |   |   |-- letsencrypt.log.210
|   |   |   |-- letsencrypt.log.211
|   |   |   |-- letsencrypt.log.212
|   |   |   |-- letsencrypt.log.213
|   |   |   |-- letsencrypt.log.214
|   |   |   |-- letsencrypt.log.215
|   |   |   |-- letsencrypt.log.216
|   |   |   |-- letsencrypt.log.217
|   |   |   |-- letsencrypt.log.218
|   |   |   |-- letsencrypt.log.219
|   |   |   |-- letsencrypt.log.22
|   |   |   |-- letsencrypt.log.220
|   |   |   |-- letsencrypt.log.221
|   |   |   |-- letsencrypt.log.222
|   |   |   |-- letsencrypt.log.223
|   |   |   |-- letsencrypt.log.224
|   |   |   |-- letsencrypt.log.225
|   |   |   |-- letsencrypt.log.226
|   |   |   |-- letsencrypt.log.227
|   |   |   |-- letsencrypt.log.228
|   |   |   |-- letsencrypt.log.229
|   |   |   |-- letsencrypt.log.23
|   |   |   |-- letsencrypt.log.230
|   |   |   |-- letsencrypt.log.231
|   |   |   |-- letsencrypt.log.232
|   |   |   |-- letsencrypt.log.233
|   |   |   |-- letsencrypt.log.234
|   |   |   |-- letsencrypt.log.235
|   |   |   |-- letsencrypt.log.236
|   |   |   |-- letsencrypt.log.237
|   |   |   |-- letsencrypt.log.238
|   |   |   |-- letsencrypt.log.239
|   |   |   |-- letsencrypt.log.24
|   |   |   |-- letsencrypt.log.240
|   |   |   |-- letsencrypt.log.241
|   |   |   |-- letsencrypt.log.242
|   |   |   |-- letsencrypt.log.243
|   |   |   |-- letsencrypt.log.244
|   |   |   |-- letsencrypt.log.245
|   |   |   |-- letsencrypt.log.246
|   |   |   |-- letsencrypt.log.247
|   |   |   |-- letsencrypt.log.248
|   |   |   |-- letsencrypt.log.249
|   |   |   |-- letsencrypt.log.25
|   |   |   |-- letsencrypt.log.250
|   |   |   |-- letsencrypt.log.251
|   |   |   |-- letsencrypt.log.252
|   |   |   |-- letsencrypt.log.253
|   |   |   |-- letsencrypt.log.254
|   |   |   |-- letsencrypt.log.255
|   |   |   |-- letsencrypt.log.256
|   |   |   |-- letsencrypt.log.257
|   |   |   |-- letsencrypt.log.258
|   |   |   |-- letsencrypt.log.259
|   |   |   |-- letsencrypt.log.26
|   |   |   |-- letsencrypt.log.260
|   |   |   |-- letsencrypt.log.261
|   |   |   |-- letsencrypt.log.262
|   |   |   |-- letsencrypt.log.263
|   |   |   |-- letsencrypt.log.264
|   |   |   |-- letsencrypt.log.265
|   |   |   |-- letsencrypt.log.266
|   |   |   |-- letsencrypt.log.267
|   |   |   |-- letsencrypt.log.268
|   |   |   |-- letsencrypt.log.269
|   |   |   |-- letsencrypt.log.27
|   |   |   |-- letsencrypt.log.270
|   |   |   |-- letsencrypt.log.271
|   |   |   |-- letsencrypt.log.272
|   |   |   |-- letsencrypt.log.273
|   |   |   |-- letsencrypt.log.274
|   |   |   |-- letsencrypt.log.275
|   |   |   |-- letsencrypt.log.276
|   |   |   |-- letsencrypt.log.277
|   |   |   |-- letsencrypt.log.278
|   |   |   |-- letsencrypt.log.279
|   |   |   |-- letsencrypt.log.28
|   |   |   |-- letsencrypt.log.280
|   |   |   |-- letsencrypt.log.281
|   |   |   |-- letsencrypt.log.282
|   |   |   |-- letsencrypt.log.283
|   |   |   |-- letsencrypt.log.284
|   |   |   |-- letsencrypt.log.285
|   |   |   |-- letsencrypt.log.286
|   |   |   |-- letsencrypt.log.287
|   |   |   |-- letsencrypt.log.288
|   |   |   |-- letsencrypt.log.289
|   |   |   |-- letsencrypt.log.29
|   |   |   |-- letsencrypt.log.290
|   |   |   |-- letsencrypt.log.291
|   |   |   |-- letsencrypt.log.292
|   |   |   |-- letsencrypt.log.293
|   |   |   |-- letsencrypt.log.294
|   |   |   |-- letsencrypt.log.295
|   |   |   |-- letsencrypt.log.296
|   |   |   |-- letsencrypt.log.297
|   |   |   |-- letsencrypt.log.298
|   |   |   |-- letsencrypt.log.299
|   |   |   |-- letsencrypt.log.3
|   |   |   |-- letsencrypt.log.30
|   |   |   |-- letsencrypt.log.300
|   |   |   |-- letsencrypt.log.301
|   |   |   |-- letsencrypt.log.302
|   |   |   |-- letsencrypt.log.303
|   |   |   |-- letsencrypt.log.304
|   |   |   |-- letsencrypt.log.305
|   |   |   |-- letsencrypt.log.306
|   |   |   |-- letsencrypt.log.307
|   |   |   |-- letsencrypt.log.308
|   |   |   |-- letsencrypt.log.309
|   |   |   |-- letsencrypt.log.31
|   |   |   |-- letsencrypt.log.310
|   |   |   |-- letsencrypt.log.311
|   |   |   |-- letsencrypt.log.312
|   |   |   |-- letsencrypt.log.313
|   |   |   |-- letsencrypt.log.314
|   |   |   |-- letsencrypt.log.315
|   |   |   |-- letsencrypt.log.316
|   |   |   |-- letsencrypt.log.317
|   |   |   |-- letsencrypt.log.318
|   |   |   |-- letsencrypt.log.319
|   |   |   |-- letsencrypt.log.32
|   |   |   |-- letsencrypt.log.320
|   |   |   |-- letsencrypt.log.321
|   |   |   |-- letsencrypt.log.322
|   |   |   |-- letsencrypt.log.323
|   |   |   |-- letsencrypt.log.324
|   |   |   |-- letsencrypt.log.325
|   |   |   |-- letsencrypt.log.326
|   |   |   |-- letsencrypt.log.327
|   |   |   |-- letsencrypt.log.328
|   |   |   |-- letsencrypt.log.329
|   |   |   |-- letsencrypt.log.33
|   |   |   |-- letsencrypt.log.330
|   |   |   |-- letsencrypt.log.331
|   |   |   |-- letsencrypt.log.332
|   |   |   |-- letsencrypt.log.333
|   |   |   |-- letsencrypt.log.334
|   |   |   |-- letsencrypt.log.335
|   |   |   |-- letsencrypt.log.336
|   |   |   |-- letsencrypt.log.337
|   |   |   |-- letsencrypt.log.338
|   |   |   |-- letsencrypt.log.339
|   |   |   |-- letsencrypt.log.34
|   |   |   |-- letsencrypt.log.340
|   |   |   |-- letsencrypt.log.341
|   |   |   |-- letsencrypt.log.342
|   |   |   |-- letsencrypt.log.343
|   |   |   |-- letsencrypt.log.344
|   |   |   |-- letsencrypt.log.345
|   |   |   |-- letsencrypt.log.346
|   |   |   |-- letsencrypt.log.347
|   |   |   |-- letsencrypt.log.348
|   |   |   |-- letsencrypt.log.349
|   |   |   |-- letsencrypt.log.35
|   |   |   |-- letsencrypt.log.350
|   |   |   |-- letsencrypt.log.351
|   |   |   |-- letsencrypt.log.352
|   |   |   |-- letsencrypt.log.353
|   |   |   |-- letsencrypt.log.354
|   |   |   |-- letsencrypt.log.355
|   |   |   |-- letsencrypt.log.356
|   |   |   |-- letsencrypt.log.357
|   |   |   |-- letsencrypt.log.358
|   |   |   |-- letsencrypt.log.359
|   |   |   |-- letsencrypt.log.36
|   |   |   |-- letsencrypt.log.360
|   |   |   |-- letsencrypt.log.361
|   |   |   |-- letsencrypt.log.362
|   |   |   |-- letsencrypt.log.363
|   |   |   |-- letsencrypt.log.364
|   |   |   |-- letsencrypt.log.365
|   |   |   |-- letsencrypt.log.366
|   |   |   |-- letsencrypt.log.367
|   |   |   |-- letsencrypt.log.368
|   |   |   |-- letsencrypt.log.369
|   |   |   |-- letsencrypt.log.37
|   |   |   |-- letsencrypt.log.370
|   |   |   |-- letsencrypt.log.371
|   |   |   |-- letsencrypt.log.372
|   |   |   |-- letsencrypt.log.373
|   |   |   |-- letsencrypt.log.374
|   |   |   |-- letsencrypt.log.375
|   |   |   |-- letsencrypt.log.376
|   |   |   |-- letsencrypt.log.377
|   |   |   |-- letsencrypt.log.378
|   |   |   |-- letsencrypt.log.379
|   |   |   |-- letsencrypt.log.38
|   |   |   |-- letsencrypt.log.380
|   |   |   |-- letsencrypt.log.381
|   |   |   |-- letsencrypt.log.382
|   |   |   |-- letsencrypt.log.383
|   |   |   |-- letsencrypt.log.384
|   |   |   |-- letsencrypt.log.385
|   |   |   |-- letsencrypt.log.386
|   |   |   |-- letsencrypt.log.387
|   |   |   |-- letsencrypt.log.388
|   |   |   |-- letsencrypt.log.389
|   |   |   |-- letsencrypt.log.39
|   |   |   |-- letsencrypt.log.390
|   |   |   |-- letsencrypt.log.391
|   |   |   |-- letsencrypt.log.392
|   |   |   |-- letsencrypt.log.393
|   |   |   |-- letsencrypt.log.394
|   |   |   |-- letsencrypt.log.395
|   |   |   |-- letsencrypt.log.396
|   |   |   |-- letsencrypt.log.397
|   |   |   |-- letsencrypt.log.398
|   |   |   |-- letsencrypt.log.399
|   |   |   |-- letsencrypt.log.4
|   |   |   |-- letsencrypt.log.40
|   |   |   |-- letsencrypt.log.400
|   |   |   |-- letsencrypt.log.401
|   |   |   |-- letsencrypt.log.402
|   |   |   |-- letsencrypt.log.403
|   |   |   |-- letsencrypt.log.404
|   |   |   |-- letsencrypt.log.405
|   |   |   |-- letsencrypt.log.406
|   |   |   |-- letsencrypt.log.407
|   |   |   |-- letsencrypt.log.408
|   |   |   |-- letsencrypt.log.409
|   |   |   |-- letsencrypt.log.41
|   |   |   |-- letsencrypt.log.410
|   |   |   |-- letsencrypt.log.411
|   |   |   |-- letsencrypt.log.412
|   |   |   |-- letsencrypt.log.413
|   |   |   |-- letsencrypt.log.414
|   |   |   |-- letsencrypt.log.415
|   |   |   |-- letsencrypt.log.416
|   |   |   |-- letsencrypt.log.417
|   |   |   |-- letsencrypt.log.418
|   |   |   |-- letsencrypt.log.419
|   |   |   |-- letsencrypt.log.42
|   |   |   |-- letsencrypt.log.420
|   |   |   |-- letsencrypt.log.421
|   |   |   |-- letsencrypt.log.422
|   |   |   |-- letsencrypt.log.423
|   |   |   |-- letsencrypt.log.424
|   |   |   |-- letsencrypt.log.425
|   |   |   |-- letsencrypt.log.426
|   |   |   |-- letsencrypt.log.427
|   |   |   |-- letsencrypt.log.428
|   |   |   |-- letsencrypt.log.429
|   |   |   |-- letsencrypt.log.43
|   |   |   |-- letsencrypt.log.430
|   |   |   |-- letsencrypt.log.431
|   |   |   |-- letsencrypt.log.432
|   |   |   |-- letsencrypt.log.433
|   |   |   |-- letsencrypt.log.434
|   |   |   |-- letsencrypt.log.435
|   |   |   |-- letsencrypt.log.436
|   |   |   |-- letsencrypt.log.437
|   |   |   |-- letsencrypt.log.438
|   |   |   |-- letsencrypt.log.439
|   |   |   |-- letsencrypt.log.44
|   |   |   |-- letsencrypt.log.440
|   |   |   |-- letsencrypt.log.441
|   |   |   |-- letsencrypt.log.442
|   |   |   |-- letsencrypt.log.443
|   |   |   |-- letsencrypt.log.444
|   |   |   |-- letsencrypt.log.445
|   |   |   |-- letsencrypt.log.446
|   |   |   |-- letsencrypt.log.447
|   |   |   |-- letsencrypt.log.448
|   |   |   |-- letsencrypt.log.449
|   |   |   |-- letsencrypt.log.45
|   |   |   |-- letsencrypt.log.450
|   |   |   |-- letsencrypt.log.451
|   |   |   |-- letsencrypt.log.452
|   |   |   |-- letsencrypt.log.453
|   |   |   |-- letsencrypt.log.454
|   |   |   |-- letsencrypt.log.455
|   |   |   |-- letsencrypt.log.456
|   |   |   |-- letsencrypt.log.457
|   |   |   |-- letsencrypt.log.458
|   |   |   |-- letsencrypt.log.459
|   |   |   |-- letsencrypt.log.46
|   |   |   |-- letsencrypt.log.460
|   |   |   |-- letsencrypt.log.461
|   |   |   |-- letsencrypt.log.462
|   |   |   |-- letsencrypt.log.463
|   |   |   |-- letsencrypt.log.464
|   |   |   |-- letsencrypt.log.465
|   |   |   |-- letsencrypt.log.466
|   |   |   |-- letsencrypt.log.467
|   |   |   |-- letsencrypt.log.468
|   |   |   |-- letsencrypt.log.469
|   |   |   |-- letsencrypt.log.47
|   |   |   |-- letsencrypt.log.470
|   |   |   |-- letsencrypt.log.471
|   |   |   |-- letsencrypt.log.472
|   |   |   |-- letsencrypt.log.473
|   |   |   |-- letsencrypt.log.474
|   |   |   |-- letsencrypt.log.475
|   |   |   |-- letsencrypt.log.476
|   |   |   |-- letsencrypt.log.477
|   |   |   |-- letsencrypt.log.478
|   |   |   |-- letsencrypt.log.479
|   |   |   |-- letsencrypt.log.48
|   |   |   |-- letsencrypt.log.480
|   |   |   |-- letsencrypt.log.481
|   |   |   |-- letsencrypt.log.482
|   |   |   |-- letsencrypt.log.483
|   |   |   |-- letsencrypt.log.484
|   |   |   |-- letsencrypt.log.485
|   |   |   |-- letsencrypt.log.486
|   |   |   |-- letsencrypt.log.487
|   |   |   |-- letsencrypt.log.488
|   |   |   |-- letsencrypt.log.489
|   |   |   |-- letsencrypt.log.49
|   |   |   |-- letsencrypt.log.490
|   |   |   |-- letsencrypt.log.491
|   |   |   |-- letsencrypt.log.492
|   |   |   |-- letsencrypt.log.493
|   |   |   |-- letsencrypt.log.494
|   |   |   |-- letsencrypt.log.495
|   |   |   |-- letsencrypt.log.496
|   |   |   |-- letsencrypt.log.497
|   |   |   |-- letsencrypt.log.498
|   |   |   |-- letsencrypt.log.499
|   |   |   |-- letsencrypt.log.5
|   |   |   |-- letsencrypt.log.50
|   |   |   |-- letsencrypt.log.500
|   |   |   |-- letsencrypt.log.501
|   |   |   |-- letsencrypt.log.502
|   |   |   |-- letsencrypt.log.503
|   |   |   |-- letsencrypt.log.504
|   |   |   |-- letsencrypt.log.505
|   |   |   |-- letsencrypt.log.506
|   |   |   |-- letsencrypt.log.507
|   |   |   |-- letsencrypt.log.508
|   |   |   |-- letsencrypt.log.509
|   |   |   |-- letsencrypt.log.51
|   |   |   |-- letsencrypt.log.510
|   |   |   |-- letsencrypt.log.511
|   |   |   |-- letsencrypt.log.512
|   |   |   |-- letsencrypt.log.513
|   |   |   |-- letsencrypt.log.514
|   |   |   |-- letsencrypt.log.515
|   |   |   |-- letsencrypt.log.516
|   |   |   |-- letsencrypt.log.517
|   |   |   |-- letsencrypt.log.518
|   |   |   |-- letsencrypt.log.519
|   |   |   |-- letsencrypt.log.52
|   |   |   |-- letsencrypt.log.520
|   |   |   |-- letsencrypt.log.521
|   |   |   |-- letsencrypt.log.522
|   |   |   |-- letsencrypt.log.523
|   |   |   |-- letsencrypt.log.524
|   |   |   |-- letsencrypt.log.525
|   |   |   |-- letsencrypt.log.526
|   |   |   |-- letsencrypt.log.527
|   |   |   |-- letsencrypt.log.528
|   |   |   |-- letsencrypt.log.529
|   |   |   |-- letsencrypt.log.53
|   |   |   |-- letsencrypt.log.530
|   |   |   |-- letsencrypt.log.531
|   |   |   |-- letsencrypt.log.532
|   |   |   |-- letsencrypt.log.533
|   |   |   |-- letsencrypt.log.534
|   |   |   |-- letsencrypt.log.535
|   |   |   |-- letsencrypt.log.536
|   |   |   |-- letsencrypt.log.537
|   |   |   |-- letsencrypt.log.538
|   |   |   |-- letsencrypt.log.539
|   |   |   |-- letsencrypt.log.54
|   |   |   |-- letsencrypt.log.540
|   |   |   |-- letsencrypt.log.541
|   |   |   |-- letsencrypt.log.542
|   |   |   |-- letsencrypt.log.543
|   |   |   |-- letsencrypt.log.544
|   |   |   |-- letsencrypt.log.545
|   |   |   |-- letsencrypt.log.546
|   |   |   |-- letsencrypt.log.547
|   |   |   |-- letsencrypt.log.548
|   |   |   |-- letsencrypt.log.549
|   |   |   |-- letsencrypt.log.55
|   |   |   |-- letsencrypt.log.550
|   |   |   |-- letsencrypt.log.551
|   |   |   |-- letsencrypt.log.552
|   |   |   |-- letsencrypt.log.553
|   |   |   |-- letsencrypt.log.554
|   |   |   |-- letsencrypt.log.555
|   |   |   |-- letsencrypt.log.556
|   |   |   |-- letsencrypt.log.557
|   |   |   |-- letsencrypt.log.558
|   |   |   |-- letsencrypt.log.559
|   |   |   |-- letsencrypt.log.56
|   |   |   |-- letsencrypt.log.560
|   |   |   |-- letsencrypt.log.561
|   |   |   |-- letsencrypt.log.562
|   |   |   |-- letsencrypt.log.563
|   |   |   |-- letsencrypt.log.564
|   |   |   |-- letsencrypt.log.565
|   |   |   |-- letsencrypt.log.566
|   |   |   |-- letsencrypt.log.567
|   |   |   |-- letsencrypt.log.568
|   |   |   |-- letsencrypt.log.569
|   |   |   |-- letsencrypt.log.57
|   |   |   |-- letsencrypt.log.570
|   |   |   |-- letsencrypt.log.571
|   |   |   |-- letsencrypt.log.572
|   |   |   |-- letsencrypt.log.573
|   |   |   |-- letsencrypt.log.574
|   |   |   |-- letsencrypt.log.575
|   |   |   |-- letsencrypt.log.576
|   |   |   |-- letsencrypt.log.577
|   |   |   |-- letsencrypt.log.578
|   |   |   |-- letsencrypt.log.579
|   |   |   |-- letsencrypt.log.58
|   |   |   |-- letsencrypt.log.580
|   |   |   |-- letsencrypt.log.581
|   |   |   |-- letsencrypt.log.582
|   |   |   |-- letsencrypt.log.583
|   |   |   |-- letsencrypt.log.584
|   |   |   |-- letsencrypt.log.585
|   |   |   |-- letsencrypt.log.586
|   |   |   |-- letsencrypt.log.587
|   |   |   |-- letsencrypt.log.588
|   |   |   |-- letsencrypt.log.589
|   |   |   |-- letsencrypt.log.59
|   |   |   |-- letsencrypt.log.590
|   |   |   |-- letsencrypt.log.591
|   |   |   |-- letsencrypt.log.592
|   |   |   |-- letsencrypt.log.593
|   |   |   |-- letsencrypt.log.594
|   |   |   |-- letsencrypt.log.595
|   |   |   |-- letsencrypt.log.596
|   |   |   |-- letsencrypt.log.597
|   |   |   |-- letsencrypt.log.598
|   |   |   |-- letsencrypt.log.599
|   |   |   |-- letsencrypt.log.6
|   |   |   |-- letsencrypt.log.60
|   |   |   |-- letsencrypt.log.600
|   |   |   |-- letsencrypt.log.601
|   |   |   |-- letsencrypt.log.602
|   |   |   |-- letsencrypt.log.603
|   |   |   |-- letsencrypt.log.604
|   |   |   |-- letsencrypt.log.605
|   |   |   |-- letsencrypt.log.606
|   |   |   |-- letsencrypt.log.607
|   |   |   |-- letsencrypt.log.608
|   |   |   |-- letsencrypt.log.609
|   |   |   |-- letsencrypt.log.61
|   |   |   |-- letsencrypt.log.610
|   |   |   |-- letsencrypt.log.611
|   |   |   |-- letsencrypt.log.612
|   |   |   |-- letsencrypt.log.613
|   |   |   |-- letsencrypt.log.614
|   |   |   |-- letsencrypt.log.615
|   |   |   |-- letsencrypt.log.616
|   |   |   |-- letsencrypt.log.617
|   |   |   |-- letsencrypt.log.618
|   |   |   |-- letsencrypt.log.619
|   |   |   |-- letsencrypt.log.62
|   |   |   |-- letsencrypt.log.620
|   |   |   |-- letsencrypt.log.621
|   |   |   |-- letsencrypt.log.622
|   |   |   |-- letsencrypt.log.623
|   |   |   |-- letsencrypt.log.624
|   |   |   |-- letsencrypt.log.625
|   |   |   |-- letsencrypt.log.626
|   |   |   |-- letsencrypt.log.627
|   |   |   |-- letsencrypt.log.628
|   |   |   |-- letsencrypt.log.629
|   |   |   |-- letsencrypt.log.63
|   |   |   |-- letsencrypt.log.630
|   |   |   |-- letsencrypt.log.631
|   |   |   |-- letsencrypt.log.632
|   |   |   |-- letsencrypt.log.633
|   |   |   |-- letsencrypt.log.634
|   |   |   |-- letsencrypt.log.635
|   |   |   |-- letsencrypt.log.636
|   |   |   |-- letsencrypt.log.637
|   |   |   |-- letsencrypt.log.638
|   |   |   |-- letsencrypt.log.639
|   |   |   |-- letsencrypt.log.64
|   |   |   |-- letsencrypt.log.640
|   |   |   |-- letsencrypt.log.641
|   |   |   |-- letsencrypt.log.642
|   |   |   |-- letsencrypt.log.643
|   |   |   |-- letsencrypt.log.644
|   |   |   |-- letsencrypt.log.645
|   |   |   |-- letsencrypt.log.646
|   |   |   |-- letsencrypt.log.647
|   |   |   |-- letsencrypt.log.648
|   |   |   |-- letsencrypt.log.649
|   |   |   |-- letsencrypt.log.65
|   |   |   |-- letsencrypt.log.650
|   |   |   |-- letsencrypt.log.651
|   |   |   |-- letsencrypt.log.652
|   |   |   |-- letsencrypt.log.653
|   |   |   |-- letsencrypt.log.654
|   |   |   |-- letsencrypt.log.655
|   |   |   |-- letsencrypt.log.656
|   |   |   |-- letsencrypt.log.657
|   |   |   |-- letsencrypt.log.658
|   |   |   |-- letsencrypt.log.659
|   |   |   |-- letsencrypt.log.66
|   |   |   |-- letsencrypt.log.660
|   |   |   |-- letsencrypt.log.661
|   |   |   |-- letsencrypt.log.662
|   |   |   |-- letsencrypt.log.663
|   |   |   |-- letsencrypt.log.664
|   |   |   |-- letsencrypt.log.665
|   |   |   |-- letsencrypt.log.666
|   |   |   |-- letsencrypt.log.667
|   |   |   |-- letsencrypt.log.668
|   |   |   |-- letsencrypt.log.669
|   |   |   |-- letsencrypt.log.67
|   |   |   |-- letsencrypt.log.670
|   |   |   |-- letsencrypt.log.671
|   |   |   |-- letsencrypt.log.672
|   |   |   |-- letsencrypt.log.673
|   |   |   |-- letsencrypt.log.674
|   |   |   |-- letsencrypt.log.675
|   |   |   |-- letsencrypt.log.676
|   |   |   |-- letsencrypt.log.677
|   |   |   |-- letsencrypt.log.678
|   |   |   |-- letsencrypt.log.679
|   |   |   |-- letsencrypt.log.68
|   |   |   |-- letsencrypt.log.680
|   |   |   |-- letsencrypt.log.681
|   |   |   |-- letsencrypt.log.682
|   |   |   |-- letsencrypt.log.683
|   |   |   |-- letsencrypt.log.684
|   |   |   |-- letsencrypt.log.685
|   |   |   |-- letsencrypt.log.686
|   |   |   |-- letsencrypt.log.687
|   |   |   |-- letsencrypt.log.688
|   |   |   |-- letsencrypt.log.689
|   |   |   |-- letsencrypt.log.69
|   |   |   |-- letsencrypt.log.690
|   |   |   |-- letsencrypt.log.691
|   |   |   |-- letsencrypt.log.692
|   |   |   |-- letsencrypt.log.693
|   |   |   |-- letsencrypt.log.694
|   |   |   |-- letsencrypt.log.695
|   |   |   |-- letsencrypt.log.696
|   |   |   |-- letsencrypt.log.697
|   |   |   |-- letsencrypt.log.698
|   |   |   |-- letsencrypt.log.699
|   |   |   |-- letsencrypt.log.7
|   |   |   |-- letsencrypt.log.70
|   |   |   |-- letsencrypt.log.700
|   |   |   |-- letsencrypt.log.701
|   |   |   |-- letsencrypt.log.702
|   |   |   |-- letsencrypt.log.703
|   |   |   |-- letsencrypt.log.704
|   |   |   |-- letsencrypt.log.705
|   |   |   |-- letsencrypt.log.706
|   |   |   |-- letsencrypt.log.707
|   |   |   |-- letsencrypt.log.708
|   |   |   |-- letsencrypt.log.709
|   |   |   |-- letsencrypt.log.71
|   |   |   |-- letsencrypt.log.710
|   |   |   |-- letsencrypt.log.711
|   |   |   |-- letsencrypt.log.712
|   |   |   |-- letsencrypt.log.713
|   |   |   |-- letsencrypt.log.714
|   |   |   |-- letsencrypt.log.715
|   |   |   |-- letsencrypt.log.716
|   |   |   |-- letsencrypt.log.717
|   |   |   |-- letsencrypt.log.718
|   |   |   |-- letsencrypt.log.719
|   |   |   |-- letsencrypt.log.72
|   |   |   |-- letsencrypt.log.720
|   |   |   |-- letsencrypt.log.721
|   |   |   |-- letsencrypt.log.722
|   |   |   |-- letsencrypt.log.723
|   |   |   |-- letsencrypt.log.724
|   |   |   |-- letsencrypt.log.725
|   |   |   |-- letsencrypt.log.726
|   |   |   |-- letsencrypt.log.727
|   |   |   |-- letsencrypt.log.728
|   |   |   |-- letsencrypt.log.729
|   |   |   |-- letsencrypt.log.73
|   |   |   |-- letsencrypt.log.730
|   |   |   |-- letsencrypt.log.731
|   |   |   |-- letsencrypt.log.732
|   |   |   |-- letsencrypt.log.733
|   |   |   |-- letsencrypt.log.734
|   |   |   |-- letsencrypt.log.735
|   |   |   |-- letsencrypt.log.736
|   |   |   |-- letsencrypt.log.737
|   |   |   |-- letsencrypt.log.738
|   |   |   |-- letsencrypt.log.739
|   |   |   |-- letsencrypt.log.74
|   |   |   |-- letsencrypt.log.740
|   |   |   |-- letsencrypt.log.741
|   |   |   |-- letsencrypt.log.742
|   |   |   |-- letsencrypt.log.743
|   |   |   |-- letsencrypt.log.744
|   |   |   |-- letsencrypt.log.745
|   |   |   |-- letsencrypt.log.746
|   |   |   |-- letsencrypt.log.747
|   |   |   |-- letsencrypt.log.748
|   |   |   |-- letsencrypt.log.749
|   |   |   |-- letsencrypt.log.75
|   |   |   |-- letsencrypt.log.750
|   |   |   |-- letsencrypt.log.751
|   |   |   |-- letsencrypt.log.752
|   |   |   |-- letsencrypt.log.753
|   |   |   |-- letsencrypt.log.754
|   |   |   |-- letsencrypt.log.755
|   |   |   |-- letsencrypt.log.756
|   |   |   |-- letsencrypt.log.757
|   |   |   |-- letsencrypt.log.758
|   |   |   |-- letsencrypt.log.759
|   |   |   |-- letsencrypt.log.76
|   |   |   |-- letsencrypt.log.760
|   |   |   |-- letsencrypt.log.761
|   |   |   |-- letsencrypt.log.762
|   |   |   |-- letsencrypt.log.763
|   |   |   |-- letsencrypt.log.764
|   |   |   |-- letsencrypt.log.765
|   |   |   |-- letsencrypt.log.766
|   |   |   |-- letsencrypt.log.767
|   |   |   |-- letsencrypt.log.768
|   |   |   |-- letsencrypt.log.769
|   |   |   |-- letsencrypt.log.77
|   |   |   |-- letsencrypt.log.770
|   |   |   |-- letsencrypt.log.771
|   |   |   |-- letsencrypt.log.772
|   |   |   |-- letsencrypt.log.773
|   |   |   |-- letsencrypt.log.774
|   |   |   |-- letsencrypt.log.775
|   |   |   |-- letsencrypt.log.776
|   |   |   |-- letsencrypt.log.777
|   |   |   |-- letsencrypt.log.778
|   |   |   |-- letsencrypt.log.779
|   |   |   |-- letsencrypt.log.78
|   |   |   |-- letsencrypt.log.780
|   |   |   |-- letsencrypt.log.781
|   |   |   |-- letsencrypt.log.782
|   |   |   |-- letsencrypt.log.783
|   |   |   |-- letsencrypt.log.784
|   |   |   |-- letsencrypt.log.785
|   |   |   |-- letsencrypt.log.786
|   |   |   |-- letsencrypt.log.787
|   |   |   |-- letsencrypt.log.788
|   |   |   |-- letsencrypt.log.789
|   |   |   |-- letsencrypt.log.79
|   |   |   |-- letsencrypt.log.790
|   |   |   |-- letsencrypt.log.791
|   |   |   |-- letsencrypt.log.792
|   |   |   |-- letsencrypt.log.793
|   |   |   |-- letsencrypt.log.794
|   |   |   |-- letsencrypt.log.795
|   |   |   |-- letsencrypt.log.796
|   |   |   |-- letsencrypt.log.797
|   |   |   |-- letsencrypt.log.798
|   |   |   |-- letsencrypt.log.799
|   |   |   |-- letsencrypt.log.8
|   |   |   |-- letsencrypt.log.80
|   |   |   |-- letsencrypt.log.800
|   |   |   |-- letsencrypt.log.801
|   |   |   |-- letsencrypt.log.802
|   |   |   |-- letsencrypt.log.803
|   |   |   |-- letsencrypt.log.804
|   |   |   |-- letsencrypt.log.805
|   |   |   |-- letsencrypt.log.806
|   |   |   |-- letsencrypt.log.807
|   |   |   |-- letsencrypt.log.808
|   |   |   |-- letsencrypt.log.809
|   |   |   |-- letsencrypt.log.81
|   |   |   |-- letsencrypt.log.810
|   |   |   |-- letsencrypt.log.811
|   |   |   |-- letsencrypt.log.812
|   |   |   |-- letsencrypt.log.813
|   |   |   |-- letsencrypt.log.814
|   |   |   |-- letsencrypt.log.815
|   |   |   |-- letsencrypt.log.816
|   |   |   |-- letsencrypt.log.817
|   |   |   |-- letsencrypt.log.818
|   |   |   |-- letsencrypt.log.819
|   |   |   |-- letsencrypt.log.82
|   |   |   |-- letsencrypt.log.820
|   |   |   |-- letsencrypt.log.821
|   |   |   |-- letsencrypt.log.822
|   |   |   |-- letsencrypt.log.823
|   |   |   |-- letsencrypt.log.824
|   |   |   |-- letsencrypt.log.825
|   |   |   |-- letsencrypt.log.826
|   |   |   |-- letsencrypt.log.827
|   |   |   |-- letsencrypt.log.828
|   |   |   |-- letsencrypt.log.829
|   |   |   |-- letsencrypt.log.83
|   |   |   |-- letsencrypt.log.830
|   |   |   |-- letsencrypt.log.831
|   |   |   |-- letsencrypt.log.832
|   |   |   |-- letsencrypt.log.833
|   |   |   |-- letsencrypt.log.834
|   |   |   |-- letsencrypt.log.835
|   |   |   |-- letsencrypt.log.836
|   |   |   |-- letsencrypt.log.837
|   |   |   |-- letsencrypt.log.838
|   |   |   |-- letsencrypt.log.839
|   |   |   |-- letsencrypt.log.84
|   |   |   |-- letsencrypt.log.840
|   |   |   |-- letsencrypt.log.841
|   |   |   |-- letsencrypt.log.842
|   |   |   |-- letsencrypt.log.843
|   |   |   |-- letsencrypt.log.844
|   |   |   |-- letsencrypt.log.845
|   |   |   |-- letsencrypt.log.846
|   |   |   |-- letsencrypt.log.847
|   |   |   |-- letsencrypt.log.848
|   |   |   |-- letsencrypt.log.849
|   |   |   |-- letsencrypt.log.85
|   |   |   |-- letsencrypt.log.850
|   |   |   |-- letsencrypt.log.851
|   |   |   |-- letsencrypt.log.852
|   |   |   |-- letsencrypt.log.853
|   |   |   |-- letsencrypt.log.854
|   |   |   |-- letsencrypt.log.855
|   |   |   |-- letsencrypt.log.856
|   |   |   |-- letsencrypt.log.857
|   |   |   |-- letsencrypt.log.858
|   |   |   |-- letsencrypt.log.859
|   |   |   |-- letsencrypt.log.86
|   |   |   |-- letsencrypt.log.860
|   |   |   |-- letsencrypt.log.861
|   |   |   |-- letsencrypt.log.862
|   |   |   |-- letsencrypt.log.863
|   |   |   |-- letsencrypt.log.864
|   |   |   |-- letsencrypt.log.865
|   |   |   |-- letsencrypt.log.866
|   |   |   |-- letsencrypt.log.867
|   |   |   |-- letsencrypt.log.868
|   |   |   |-- letsencrypt.log.869
|   |   |   |-- letsencrypt.log.87
|   |   |   |-- letsencrypt.log.870
|   |   |   |-- letsencrypt.log.871
|   |   |   |-- letsencrypt.log.872
|   |   |   |-- letsencrypt.log.873
|   |   |   |-- letsencrypt.log.874
|   |   |   |-- letsencrypt.log.875
|   |   |   |-- letsencrypt.log.876
|   |   |   |-- letsencrypt.log.877
|   |   |   |-- letsencrypt.log.878
|   |   |   |-- letsencrypt.log.879
|   |   |   |-- letsencrypt.log.88
|   |   |   |-- letsencrypt.log.880
|   |   |   |-- letsencrypt.log.881
|   |   |   |-- letsencrypt.log.882
|   |   |   |-- letsencrypt.log.883
|   |   |   |-- letsencrypt.log.884
|   |   |   |-- letsencrypt.log.885
|   |   |   |-- letsencrypt.log.886
|   |   |   |-- letsencrypt.log.887
|   |   |   |-- letsencrypt.log.888
|   |   |   |-- letsencrypt.log.889
|   |   |   |-- letsencrypt.log.89
|   |   |   |-- letsencrypt.log.890
|   |   |   |-- letsencrypt.log.891
|   |   |   |-- letsencrypt.log.892
|   |   |   |-- letsencrypt.log.893
|   |   |   |-- letsencrypt.log.894
|   |   |   |-- letsencrypt.log.895
|   |   |   |-- letsencrypt.log.896
|   |   |   |-- letsencrypt.log.897
|   |   |   |-- letsencrypt.log.898
|   |   |   |-- letsencrypt.log.899
|   |   |   |-- letsencrypt.log.9
|   |   |   |-- letsencrypt.log.90
|   |   |   |-- letsencrypt.log.900
|   |   |   |-- letsencrypt.log.901
|   |   |   |-- letsencrypt.log.902
|   |   |   |-- letsencrypt.log.903
|   |   |   |-- letsencrypt.log.904
|   |   |   |-- letsencrypt.log.905
|   |   |   |-- letsencrypt.log.906
|   |   |   |-- letsencrypt.log.907
|   |   |   |-- letsencrypt.log.908
|   |   |   |-- letsencrypt.log.909
|   |   |   |-- letsencrypt.log.91
|   |   |   |-- letsencrypt.log.910
|   |   |   |-- letsencrypt.log.911
|   |   |   |-- letsencrypt.log.912
|   |   |   |-- letsencrypt.log.913
|   |   |   |-- letsencrypt.log.914
|   |   |   |-- letsencrypt.log.915
|   |   |   |-- letsencrypt.log.916
|   |   |   |-- letsencrypt.log.917
|   |   |   |-- letsencrypt.log.918
|   |   |   |-- letsencrypt.log.919
|   |   |   |-- letsencrypt.log.92
|   |   |   |-- letsencrypt.log.920
|   |   |   |-- letsencrypt.log.921
|   |   |   |-- letsencrypt.log.922
|   |   |   |-- letsencrypt.log.923
|   |   |   |-- letsencrypt.log.924
|   |   |   |-- letsencrypt.log.925
|   |   |   |-- letsencrypt.log.926
|   |   |   |-- letsencrypt.log.927
|   |   |   |-- letsencrypt.log.928
|   |   |   |-- letsencrypt.log.929
|   |   |   |-- letsencrypt.log.93
|   |   |   |-- letsencrypt.log.930
|   |   |   |-- letsencrypt.log.931
|   |   |   |-- letsencrypt.log.932
|   |   |   |-- letsencrypt.log.933
|   |   |   |-- letsencrypt.log.934
|   |   |   |-- letsencrypt.log.935
|   |   |   |-- letsencrypt.log.936
|   |   |   |-- letsencrypt.log.937
|   |   |   |-- letsencrypt.log.938
|   |   |   |-- letsencrypt.log.939
|   |   |   |-- letsencrypt.log.94
|   |   |   |-- letsencrypt.log.940
|   |   |   |-- letsencrypt.log.941
|   |   |   |-- letsencrypt.log.942
|   |   |   |-- letsencrypt.log.943
|   |   |   |-- letsencrypt.log.944
|   |   |   |-- letsencrypt.log.945
|   |   |   |-- letsencrypt.log.946
|   |   |   |-- letsencrypt.log.947
|   |   |   |-- letsencrypt.log.948
|   |   |   |-- letsencrypt.log.949
|   |   |   |-- letsencrypt.log.95
|   |   |   |-- letsencrypt.log.950
|   |   |   |-- letsencrypt.log.951
|   |   |   |-- letsencrypt.log.952
|   |   |   |-- letsencrypt.log.953
|   |   |   |-- letsencrypt.log.954
|   |   |   |-- letsencrypt.log.955
|   |   |   |-- letsencrypt.log.956
|   |   |   |-- letsencrypt.log.957
|   |   |   |-- letsencrypt.log.958
|   |   |   |-- letsencrypt.log.959
|   |   |   |-- letsencrypt.log.96
|   |   |   |-- letsencrypt.log.960
|   |   |   |-- letsencrypt.log.961
|   |   |   |-- letsencrypt.log.962
|   |   |   |-- letsencrypt.log.963
|   |   |   |-- letsencrypt.log.964
|   |   |   |-- letsencrypt.log.965
|   |   |   |-- letsencrypt.log.966
|   |   |   |-- letsencrypt.log.967
|   |   |   |-- letsencrypt.log.968
|   |   |   |-- letsencrypt.log.969
|   |   |   |-- letsencrypt.log.97
|   |   |   |-- letsencrypt.log.970
|   |   |   |-- letsencrypt.log.971
|   |   |   |-- letsencrypt.log.972
|   |   |   |-- letsencrypt.log.973
|   |   |   |-- letsencrypt.log.974
|   |   |   |-- letsencrypt.log.975
|   |   |   |-- letsencrypt.log.976
|   |   |   |-- letsencrypt.log.977
|   |   |   |-- letsencrypt.log.978
|   |   |   |-- letsencrypt.log.979
|   |   |   |-- letsencrypt.log.98
|   |   |   |-- letsencrypt.log.980
|   |   |   |-- letsencrypt.log.981
|   |   |   |-- letsencrypt.log.982
|   |   |   |-- letsencrypt.log.983
|   |   |   |-- letsencrypt.log.984
|   |   |   |-- letsencrypt.log.985
|   |   |   |-- letsencrypt.log.986
|   |   |   |-- letsencrypt.log.987
|   |   |   |-- letsencrypt.log.988
|   |   |   |-- letsencrypt.log.989
|   |   |   |-- letsencrypt.log.99
|   |   |   |-- letsencrypt.log.990
|   |   |   |-- letsencrypt.log.991
|   |   |   |-- letsencrypt.log.992
|   |   |   |-- letsencrypt.log.993
|   |   |   |-- letsencrypt.log.994
|   |   |   |-- letsencrypt.log.995
|   |   |   |-- letsencrypt.log.996
|   |   |   |-- letsencrypt.log.997
|   |   |   |-- letsencrypt.log.998
|   |   |   |-- letsencrypt.log.999
|   |   |   |-- proxy-host-10_access.log
|   |   |   |-- proxy-host-10_access.log.1.gz
|   |   |   |-- proxy-host-10_access.log.2.gz
|   |   |   |-- proxy-host-10_access.log.3.gz
|   |   |   |-- proxy-host-10_access.log.4.gz
|   |   |   |-- proxy-host-10_error.log
|   |   |   |-- proxy-host-10_error.log.1.gz
|   |   |   |-- proxy-host-10_error.log.10.gz
|   |   |   |-- proxy-host-10_error.log.2.gz
|   |   |   |-- proxy-host-10_error.log.3.gz
|   |   |   |-- proxy-host-10_error.log.4.gz
|   |   |   |-- proxy-host-10_error.log.5.gz
|   |   |   |-- proxy-host-10_error.log.6.gz
|   |   |   |-- proxy-host-10_error.log.7.gz
|   |   |   |-- proxy-host-10_error.log.8.gz
|   |   |   |-- proxy-host-10_error.log.9.gz
|   |   |   |-- proxy-host-11_access.log
|   |   |   |-- proxy-host-11_access.log.1.gz
|   |   |   |-- proxy-host-11_error.log
|   |   |   |-- proxy-host-11_error.log.1.gz
|   |   |   |-- proxy-host-12_access.log
|   |   |   |-- proxy-host-12_access.log.1.gz
|   |   |   |-- proxy-host-12_access.log.2.gz
|   |   |   |-- proxy-host-12_access.log.3.gz
|   |   |   |-- proxy-host-12_access.log.4.gz
|   |   |   |-- proxy-host-12_error.log
|   |   |   |-- proxy-host-12_error.log.1.gz
|   |   |   |-- proxy-host-12_error.log.10.gz
|   |   |   |-- proxy-host-12_error.log.2.gz
|   |   |   |-- proxy-host-12_error.log.3.gz
|   |   |   |-- proxy-host-12_error.log.4.gz
|   |   |   |-- proxy-host-12_error.log.5.gz
|   |   |   |-- proxy-host-12_error.log.6.gz
|   |   |   |-- proxy-host-12_error.log.7.gz
|   |   |   |-- proxy-host-12_error.log.8.gz
|   |   |   |-- proxy-host-12_error.log.9.gz
|   |   |   |-- proxy-host-13_access.log
|   |   |   |-- proxy-host-13_error.log
|   |   |   |-- proxy-host-14_access.log
|   |   |   |-- proxy-host-14_access.log.1.gz
|   |   |   |-- proxy-host-14_error.log
|   |   |   |-- proxy-host-15_access.log
|   |   |   |-- proxy-host-15_error.log
|   |   |   |-- proxy-host-1_access.log
|   |   |   |-- proxy-host-1_access.log.1.gz
|   |   |   |-- proxy-host-1_access.log.2.gz
|   |   |   |-- proxy-host-1_access.log.3.gz
|   |   |   |-- proxy-host-1_access.log.4.gz
|   |   |   |-- proxy-host-1_error.log
|   |   |   |-- proxy-host-1_error.log.1.gz
|   |   |   |-- proxy-host-1_error.log.10.gz
|   |   |   |-- proxy-host-1_error.log.2.gz
|   |   |   |-- proxy-host-1_error.log.3.gz
|   |   |   |-- proxy-host-1_error.log.4.gz
|   |   |   |-- proxy-host-1_error.log.5.gz
|   |   |   |-- proxy-host-1_error.log.6.gz
|   |   |   |-- proxy-host-1_error.log.7.gz
|   |   |   |-- proxy-host-1_error.log.8.gz
|   |   |   |-- proxy-host-1_error.log.9.gz
|   |   |   |-- proxy-host-2_access.log
|   |   |   |-- proxy-host-2_access.log.1.gz
|   |   |   |-- proxy-host-2_access.log.2.gz
|   |   |   |-- proxy-host-2_access.log.3.gz
|   |   |   |-- proxy-host-2_access.log.4.gz
|   |   |   |-- proxy-host-2_error.log
|   |   |   |-- proxy-host-2_error.log.1.gz
|   |   |   |-- proxy-host-2_error.log.10.gz
|   |   |   |-- proxy-host-2_error.log.2.gz
|   |   |   |-- proxy-host-2_error.log.3.gz
|   |   |   |-- proxy-host-2_error.log.4.gz
|   |   |   |-- proxy-host-2_error.log.5.gz
|   |   |   |-- proxy-host-2_error.log.6.gz
|   |   |   |-- proxy-host-2_error.log.7.gz
|   |   |   |-- proxy-host-2_error.log.8.gz
|   |   |   |-- proxy-host-2_error.log.9.gz
|   |   |   |-- proxy-host-3_access.log
|   |   |   |-- proxy-host-3_access.log.1.gz
|   |   |   |-- proxy-host-3_access.log.2.gz
|   |   |   |-- proxy-host-3_access.log.3.gz
|   |   |   |-- proxy-host-3_access.log.4.gz
|   |   |   |-- proxy-host-3_error.log
|   |   |   |-- proxy-host-3_error.log.1.gz
|   |   |   |-- proxy-host-3_error.log.10.gz
|   |   |   |-- proxy-host-3_error.log.2.gz
|   |   |   |-- proxy-host-3_error.log.3.gz
|   |   |   |-- proxy-host-3_error.log.4.gz
|   |   |   |-- proxy-host-3_error.log.5.gz
|   |   |   |-- proxy-host-3_error.log.6.gz
|   |   |   |-- proxy-host-3_error.log.7.gz
|   |   |   |-- proxy-host-3_error.log.8.gz
|   |   |   |-- proxy-host-3_error.log.9.gz
|   |   |   |-- proxy-host-4_access.log
|   |   |   |-- proxy-host-4_error.log
|   |   |   |-- proxy-host-5_access.log
|   |   |   |-- proxy-host-5_access.log.1.gz
|   |   |   |-- proxy-host-5_access.log.2.gz
|   |   |   |-- proxy-host-5_access.log.3.gz
|   |   |   |-- proxy-host-5_access.log.4.gz
|   |   |   |-- proxy-host-5_error.log
|   |   |   |-- proxy-host-5_error.log.1.gz
|   |   |   |-- proxy-host-5_error.log.10.gz
|   |   |   |-- proxy-host-5_error.log.2.gz
|   |   |   |-- proxy-host-5_error.log.3.gz
|   |   |   |-- proxy-host-5_error.log.4.gz
|   |   |   |-- proxy-host-5_error.log.5.gz
|   |   |   |-- proxy-host-5_error.log.6.gz
|   |   |   |-- proxy-host-5_error.log.7.gz
|   |   |   |-- proxy-host-5_error.log.8.gz
|   |   |   |-- proxy-host-5_error.log.9.gz
|   |   |   |-- proxy-host-6_access.log
|   |   |   |-- proxy-host-6_error.log
|   |   |   |-- proxy-host-7_access.log
|   |   |   |-- proxy-host-7_access.log.1.gz
|   |   |   |-- proxy-host-7_access.log.2.gz
|   |   |   |-- proxy-host-7_access.log.3.gz
|   |   |   |-- proxy-host-7_access.log.4.gz
|   |   |   |-- proxy-host-7_error.log
|   |   |   |-- proxy-host-7_error.log.1.gz
|   |   |   |-- proxy-host-7_error.log.10.gz
|   |   |   |-- proxy-host-7_error.log.2.gz
|   |   |   |-- proxy-host-7_error.log.3.gz
|   |   |   |-- proxy-host-7_error.log.4.gz
|   |   |   |-- proxy-host-7_error.log.5.gz
|   |   |   |-- proxy-host-7_error.log.6.gz
|   |   |   |-- proxy-host-7_error.log.7.gz
|   |   |   |-- proxy-host-7_error.log.8.gz
|   |   |   |-- proxy-host-7_error.log.9.gz
|   |   |   |-- proxy-host-8_access.log
|   |   |   |-- proxy-host-8_access.log.1.gz
|   |   |   |-- proxy-host-8_access.log.2.gz
|   |   |   |-- proxy-host-8_access.log.3.gz
|   |   |   |-- proxy-host-8_access.log.4.gz
|   |   |   |-- proxy-host-8_error.log
|   |   |   |-- proxy-host-8_error.log.1.gz
|   |   |   |-- proxy-host-8_error.log.10.gz
|   |   |   |-- proxy-host-8_error.log.2.gz
|   |   |   |-- proxy-host-8_error.log.3.gz
|   |   |   |-- proxy-host-8_error.log.4.gz
|   |   |   |-- proxy-host-8_error.log.5.gz
|   |   |   |-- proxy-host-8_error.log.6.gz
|   |   |   |-- proxy-host-8_error.log.7.gz
|   |   |   |-- proxy-host-8_error.log.8.gz
|   |   |   |-- proxy-host-8_error.log.9.gz
|   |   |   |-- proxy-host-9_access.log
|   |   |   |-- proxy-host-9_access.log.1.gz
|   |   |   |-- proxy-host-9_access.log.2.gz
|   |   |   |-- proxy-host-9_access.log.3.gz
|   |   |   |-- proxy-host-9_access.log.4.gz
|   |   |   |-- proxy-host-9_error.log
|   |   |   |-- proxy-host-9_error.log.1.gz
|   |   |   |-- proxy-host-9_error.log.2.gz
|   |   |   |-- proxy-host-9_error.log.3.gz
|   |   |   `-- proxy-host-9_error.log.4.gz
|   |   `-- nginx
|   |       |-- dead_host
|   |       |-- default_host
|   |       |-- default_www
|   |       |-- proxy_host
|   |       |   |-- 1.conf
|   |       |   |-- 10.conf
|   |       |   |-- 12.conf
|   |       |   |-- 14.conf
|   |       |   |-- 15.conf
|   |       |   |-- 2.conf
|   |       |   |-- 3.conf
|   |       |   |-- 5.conf
|   |       |   `-- 8.conf
|   |       |-- redirection_host
|   |       |-- stream
|   |       `-- temp
|   `-- letsencrypt
|       |-- accounts
|       |   `-- acme-v02.api.letsencrypt.org
|       |       `-- directory
|       |           `-- e99f2dbdd8a59f33e688d22718a679d9
|       |               |-- meta.json
|       |               |-- private_key.json
|       |               `-- regr.json
|       |-- archive
|       |   |-- npm-11
|       |   |   |-- cert1.pem
|       |   |   |-- chain1.pem
|       |   |   |-- fullchain1.pem
|       |   |   `-- privkey1.pem
|       |   |-- npm-12
|       |   |   |-- cert1.pem
|       |   |   |-- chain1.pem
|       |   |   |-- fullchain1.pem
|       |   |   `-- privkey1.pem
|       |   |-- npm-13
|       |   |   |-- cert1.pem
|       |   |   |-- chain1.pem
|       |   |   |-- fullchain1.pem
|       |   |   `-- privkey1.pem
|       |   |-- npm-15
|       |   |   |-- cert1.pem
|       |   |   |-- chain1.pem
|       |   |   |-- fullchain1.pem
|       |   |   `-- privkey1.pem
|       |   |-- npm-16
|       |   |   |-- cert1.pem
|       |   |   |-- chain1.pem
|       |   |   |-- fullchain1.pem
|       |   |   `-- privkey1.pem
|       |   |-- npm-17
|       |   |   |-- cert1.pem
|       |   |   |-- chain1.pem
|       |   |   |-- fullchain1.pem
|       |   |   `-- privkey1.pem
|       |   |-- npm-19
|       |   |   |-- cert1.pem
|       |   |   |-- cert2.pem
|       |   |   |-- cert3.pem
|       |   |   |-- chain1.pem
|       |   |   |-- chain2.pem
|       |   |   |-- chain3.pem
|       |   |   |-- fullchain1.pem
|       |   |   |-- fullchain2.pem
|       |   |   |-- fullchain3.pem
|       |   |   |-- privkey1.pem
|       |   |   |-- privkey2.pem
|       |   |   `-- privkey3.pem
|       |   |-- npm-2
|       |   |   |-- cert1.pem
|       |   |   |-- chain1.pem
|       |   |   |-- fullchain1.pem
|       |   |   `-- privkey1.pem
|       |   |-- npm-26
|       |   |   |-- cert1.pem
|       |   |   |-- chain1.pem
|       |   |   |-- fullchain1.pem
|       |   |   `-- privkey1.pem
|       |   |-- npm-3
|       |   |   |-- cert1.pem
|       |   |   |-- chain1.pem
|       |   |   |-- fullchain1.pem
|       |   |   `-- privkey1.pem
|       |   |-- npm-4
|       |   |   |-- cert1.pem
|       |   |   |-- chain1.pem
|       |   |   |-- fullchain1.pem
|       |   |   `-- privkey1.pem
|       |   |-- npm-5
|       |   |   |-- cert1.pem
|       |   |   |-- chain1.pem
|       |   |   |-- fullchain1.pem
|       |   |   `-- privkey1.pem
|       |   |-- npm-6
|       |   |   |-- cert1.pem
|       |   |   |-- chain1.pem
|       |   |   |-- fullchain1.pem
|       |   |   `-- privkey1.pem
|       |   |-- npm-7
|       |   |   |-- cert1.pem
|       |   |   |-- cert2.pem
|       |   |   |-- cert3.pem
|       |   |   |-- cert4.pem
|       |   |   |-- cert5.pem
|       |   |   |-- cert6.pem
|       |   |   |-- chain1.pem
|       |   |   |-- chain2.pem
|       |   |   |-- chain3.pem
|       |   |   |-- chain4.pem
|       |   |   |-- chain5.pem
|       |   |   |-- chain6.pem
|       |   |   |-- fullchain1.pem
|       |   |   |-- fullchain2.pem
|       |   |   |-- fullchain3.pem
|       |   |   |-- fullchain4.pem
|       |   |   |-- fullchain5.pem
|       |   |   |-- fullchain6.pem
|       |   |   |-- privkey1.pem
|       |   |   |-- privkey2.pem
|       |   |   |-- privkey3.pem
|       |   |   |-- privkey4.pem
|       |   |   |-- privkey5.pem
|       |   |   `-- privkey6.pem
|       |   `-- npm-9
|       |       |-- cert1.pem
|       |       |-- cert2.pem
|       |       |-- cert3.pem
|       |       |-- cert4.pem
|       |       |-- cert5.pem
|       |       |-- chain1.pem
|       |       |-- chain2.pem
|       |       |-- chain3.pem
|       |       |-- chain4.pem
|       |       |-- chain5.pem
|       |       |-- fullchain1.pem
|       |       |-- fullchain2.pem
|       |       |-- fullchain3.pem
|       |       |-- fullchain4.pem
|       |       |-- fullchain5.pem
|       |       |-- privkey1.pem
|       |       |-- privkey2.pem
|       |       |-- privkey3.pem
|       |       |-- privkey4.pem
|       |       `-- privkey5.pem
|       |-- credentials
|       |   `-- credentials-26
|       |-- live
|       |   |-- README
|       |   |-- npm-11
|       |   |   |-- README
|       |   |   |-- cert.pem -> ../../archive/npm-11/cert1.pem
|       |   |   |-- chain.pem -> ../../archive/npm-11/chain1.pem
|       |   |   |-- fullchain.pem -> ../../archive/npm-11/fullchain1.pem
|       |   |   `-- privkey.pem -> ../../archive/npm-11/privkey1.pem
|       |   |-- npm-12
|       |   |   |-- README
|       |   |   |-- cert.pem -> ../../archive/npm-12/cert1.pem
|       |   |   |-- chain.pem -> ../../archive/npm-12/chain1.pem
|       |   |   |-- fullchain.pem -> ../../archive/npm-12/fullchain1.pem
|       |   |   `-- privkey.pem -> ../../archive/npm-12/privkey1.pem
|       |   |-- npm-13
|       |   |   |-- README
|       |   |   |-- cert.pem -> ../../archive/npm-13/cert1.pem
|       |   |   |-- chain.pem -> ../../archive/npm-13/chain1.pem
|       |   |   |-- fullchain.pem -> ../../archive/npm-13/fullchain1.pem
|       |   |   `-- privkey.pem -> ../../archive/npm-13/privkey1.pem
|       |   |-- npm-15
|       |   |   |-- README
|       |   |   |-- cert.pem -> ../../archive/npm-15/cert1.pem
|       |   |   |-- chain.pem -> ../../archive/npm-15/chain1.pem
|       |   |   |-- fullchain.pem -> ../../archive/npm-15/fullchain1.pem
|       |   |   `-- privkey.pem -> ../../archive/npm-15/privkey1.pem
|       |   |-- npm-16
|       |   |   |-- README
|       |   |   |-- cert.pem -> ../../archive/npm-16/cert1.pem
|       |   |   |-- chain.pem -> ../../archive/npm-16/chain1.pem
|       |   |   |-- fullchain.pem -> ../../archive/npm-16/fullchain1.pem
|       |   |   `-- privkey.pem -> ../../archive/npm-16/privkey1.pem
|       |   |-- npm-17
|       |   |   |-- README
|       |   |   |-- cert.pem -> ../../archive/npm-17/cert1.pem
|       |   |   |-- chain.pem -> ../../archive/npm-17/chain1.pem
|       |   |   |-- fullchain.pem -> ../../archive/npm-17/fullchain1.pem
|       |   |   `-- privkey.pem -> ../../archive/npm-17/privkey1.pem
|       |   |-- npm-19
|       |   |   |-- README
|       |   |   |-- cert.pem -> ../../archive/npm-19/cert3.pem
|       |   |   |-- chain.pem -> ../../archive/npm-19/chain3.pem
|       |   |   |-- fullchain.pem -> ../../archive/npm-19/fullchain3.pem
|       |   |   `-- privkey.pem -> ../../archive/npm-19/privkey3.pem
|       |   |-- npm-2
|       |   |   |-- README
|       |   |   |-- cert.pem -> ../../archive/npm-2/cert1.pem
|       |   |   |-- chain.pem -> ../../archive/npm-2/chain1.pem
|       |   |   |-- fullchain.pem -> ../../archive/npm-2/fullchain1.pem
|       |   |   `-- privkey.pem -> ../../archive/npm-2/privkey1.pem
|       |   |-- npm-26
|       |   |   |-- README
|       |   |   |-- cert.pem -> ../../archive/npm-26/cert1.pem
|       |   |   |-- chain.pem -> ../../archive/npm-26/chain1.pem
|       |   |   |-- fullchain.pem -> ../../archive/npm-26/fullchain1.pem
|       |   |   `-- privkey.pem -> ../../archive/npm-26/privkey1.pem
|       |   |-- npm-3
|       |   |   |-- README
|       |   |   |-- cert.pem -> ../../archive/npm-3/cert1.pem
|       |   |   |-- chain.pem -> ../../archive/npm-3/chain1.pem
|       |   |   |-- fullchain.pem -> ../../archive/npm-3/fullchain1.pem
|       |   |   `-- privkey.pem -> ../../archive/npm-3/privkey1.pem
|       |   |-- npm-4
|       |   |   |-- README
|       |   |   |-- cert.pem -> ../../archive/npm-4/cert1.pem
|       |   |   |-- chain.pem -> ../../archive/npm-4/chain1.pem
|       |   |   |-- fullchain.pem -> ../../archive/npm-4/fullchain1.pem
|       |   |   `-- privkey.pem -> ../../archive/npm-4/privkey1.pem
|       |   |-- npm-5
|       |   |   |-- README
|       |   |   |-- cert.pem -> ../../archive/npm-5/cert1.pem
|       |   |   |-- chain.pem -> ../../archive/npm-5/chain1.pem
|       |   |   |-- fullchain.pem -> ../../archive/npm-5/fullchain1.pem
|       |   |   `-- privkey.pem -> ../../archive/npm-5/privkey1.pem
|       |   |-- npm-6
|       |   |   |-- README
|       |   |   |-- cert.pem -> ../../archive/npm-6/cert1.pem
|       |   |   |-- chain.pem -> ../../archive/npm-6/chain1.pem
|       |   |   |-- fullchain.pem -> ../../archive/npm-6/fullchain1.pem
|       |   |   `-- privkey.pem -> ../../archive/npm-6/privkey1.pem
|       |   |-- npm-7
|       |   |   |-- README
|       |   |   |-- cert.pem -> ../../archive/npm-7/cert6.pem
|       |   |   |-- chain.pem -> ../../archive/npm-7/chain6.pem
|       |   |   |-- fullchain.pem -> ../../archive/npm-7/fullchain6.pem
|       |   |   `-- privkey.pem -> ../../archive/npm-7/privkey6.pem
|       |   `-- npm-9
|       |       |-- README
|       |       |-- cert.pem -> ../../archive/npm-9/cert5.pem
|       |       |-- chain.pem -> ../../archive/npm-9/chain5.pem
|       |       |-- fullchain.pem -> ../../archive/npm-9/fullchain5.pem
|       |       `-- privkey.pem -> ../../archive/npm-9/privkey5.pem
|       |-- renewal
|       |   |-- npm-11.conf
|       |   |-- npm-12.conf
|       |   |-- npm-13.conf
|       |   |-- npm-15.conf
|       |   |-- npm-16.conf
|       |   |-- npm-17.conf
|       |   |-- npm-19.conf
|       |   |-- npm-2.conf
|       |   |-- npm-26.conf
|       |   |-- npm-3.conf
|       |   |-- npm-4.conf
|       |   |-- npm-5.conf
|       |   |-- npm-6.conf
|       |   |-- npm-7.conf
|       |   `-- npm-9.conf
|       `-- renewal-hooks
|           |-- deploy
|           |-- post
|           `-- pre
`-- stirling-pdf
    |-- compose.yaml
    `-- stirling-data
        |-- configs
        |   |-- backup
        |   |   |-- db
        |   |   |   |-- backup_202603231527.sql
        |   |   |   |-- backup_202603231529.sql
        |   |   |   |-- backup_202603231703.sql
        |   |   |   `-- backup_202603231704.sql
        |   |   `-- keys
        |   |       |-- jwt-key-2026-03-23-152748.key
        |   |       `-- jwt-key-2026-03-23-152748.pub
        |   |-- cache
        |   |-- custom_settings.yml
        |   |-- heap_dumps
        |   |-- settings.yml
        |   `-- stirling-pdf-DB-2.3.232.mv.db
        |-- customFiles
        |   |-- static
        |   `-- templates
        |-- logs
        |   |-- info.log
        |   `-- invalid-auths.log
        |-- pipeline
        |   |-- defaultWebUIConfigs
        |   |   |-- OCR\ images.json
        |   |   |-- Pre-publish-sanitization.json
        |   |   |-- Prepare-pdfs-for-email.json
        |   |   `-- split-rotate-auto-rename.json
        |   `-- watchedFolders
        `-- tessdata

96 directories, 1473 files
