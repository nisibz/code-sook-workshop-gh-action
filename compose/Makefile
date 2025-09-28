start:
	docker compose -f compose.nginx.yaml up -d
	docker compose -f compose.caddy.yaml up -d
	docker compose -f compose.wt.yaml up -d
	docker compose -f compose.react.yaml up -d

stop:
	docker compose -f compose.nginx.yaml down
	docker compose -f compose.caddy.yaml down
	docker compose -f compose.wt.yaml down
	docker compose -f compose.react.yaml down
