  nikto_mapper translates an Nikto results JSON file into HDF format JSON to be viewable in Heimdall
  
  Note: Current this mapper only support single target Nikto Scans.

Examples:

  heimdall_tools nikto_mapper [OPTIONS] -x <nikto-results-json> -o <hdf-scan-results.json>
