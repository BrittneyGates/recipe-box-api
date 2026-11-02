2026-11-01: Anonymous GET /recipes → 200 OK, returns all recipes, including "Secret family hot sauce" where is_public: false.
2026-11-01: Anonymous POST /recipes → created id 4, no auth required, is_public: true by default.
2026-11-02: Anonymous PUT /recipes/1 → 405 METHOD NOT ALLOWED, update route not implemented.
2026-11-02: Anonymous DELETE /recipes/1 → 204 NO CONTENT, recipe removed from list.
