- An embedded app tells its framing page what the user picked: selecting an
  aircraft, vessel or satellite posts `{ type: 'gev:entity', kind, id, label,
  lat, lon }` (ICAO address, MMSI or NORAD number) to the exact origins
  `GEV_EMBED_FRAME_ANCESTORS` names, and to no page when it is unset or `*`.
  Cameras, plate readers, Street Level and other layers are never reported
  (zedpr0).
