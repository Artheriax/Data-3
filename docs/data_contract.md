# Datacontract

Attributen per record:

`source`, `source_id`, `title`, `description`, `tags`, `media_type`, `media_url`, `license`, `retrieved_at`, `dataset_version`, `duration_seconds`, `sample_rate`, `channels`, `image_width`, `image_height`, `text_length`, `processing_status`, `quality_flag`

**Toegestane waarden:** `media_type` = audio | image; `processing_status` = raw | valid | failed | excluded.

**Granulariteit:** Eén record = exact één uniek media-item uit één databron.
**Null-semantiek:** `null` = gegeven niet beschikbaar (niet nul of lege string).
