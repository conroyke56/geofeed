# geofeed
Geolocation Data for Network Management - This repository contains a geofeed CSV file with accurate geolocation information for specific IP addresses, adhering to RFC 8805 standards.

# Geolocation Data for Network Management

This repository hosts a geofeed CSV file providing accurate geolocation information for specific IP addresses, in accordance with RFC 8805 guidelines. The geofeed format offers a standardized way to share geolocation data, enhancing the accuracy of IP-based geolocation services.

## About Geofeeds

A geofeed is a CSV file that maps IP addresses or networks to geographical locations, including country, region, city, and postal code. This standard, detailed in RFC 8805, allows network administrators and owners to correct and distribute geolocation information for their IP ranges efficiently.

## Geofeed Format

The geofeed file in this repository follows the specified CSV format:

- `network`: A valid IP address or network range, supporting both IPv4 and IPv6.
- `iso_country_code`: A valid ISO 3166-1 alpha-2 country code.
- `iso_region_code`: A valid ISO 3166-2 region code for the specified country.
- `city_name`: The name of the city associated with the IP address or network.
- `postal_code`: (Optional) The postal code for the location.

Example entry:

