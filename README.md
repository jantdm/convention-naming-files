# File Naming Convention

The following rules are optimized for maximum interoperability with local filesystems, web URLs, legacy file systems and human readability.

The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED",  "MAY", and "OPTIONAL" in this document are to be interpreted as described in [RFC 2119](http://tools.ietf.org/html/rfc2119).

+ File names MUST NOT contain spaces, periods, umlauts or any other special characters (other than "-"). Accepted characters are a-z, A-Z, -, and 0-9.
+ The RECOMMENDED way to divide words and elements in a file name is either
  + Dashes for logical divions (naming-file-detail.file)
  + [CamelCase](http://en.wikipedia.org/wiki/CamelCase) for multi-part elements (finalRecommendations.file)
  + or a combination of the above (naming-furtherDetails.file)
+ File names MAY contain a date at the beginning or at the end. Following the [ISO 8601](http://en.wikipedia.org/wiki/ISO_8601) date format is REQUIRED.
+ Files MAY further contain a trailing version number (namingConvention-v01.file)
+ Stating the author (either full name or initials) is OPTIONAL (namingConvention-JLT.file)
