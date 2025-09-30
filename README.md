# Script-List
The scripts on this list are ones that should be ready to be used on their own, likely without my help, and are made available in the Ansys-Internal organization.

### HFSS Geometry
* **Create Spline From File** - IronPython script with GUI that will run from HFSS and let you import your point list from a .pts file. Repo: https://github.com/ansys-internal/CreateSplineFromFileHFSS
* **Create Native Geometry From Array** - IronPython script with GUI to turn CADDM built using the finite array tool into native geometry to support a variety of “next steps” in array building workflows. Repo: https://github.com/ansys-internal/HFSSCreateNativeGeometryFromArray
### HFSS Data Export
* **Export S-Parameters for All Variations** - IronPython script with GUI to export S-parameter data, in case you forgot to automatically export S-parameters in Design Settings.  Repo: https://github.com/ansys-internal/HFSSExportSParametersForVariations
* **Export Far Field Data for All Variations** - Iron Python script with GUI that looks for all available variations for a solved frequency sweep and exports the ffd files as specified by a selected far field setup. Repo: https://github.com/ansys-internal/HFSSExportFarFieldDataForVariations
* **Export Near Field Data for Individual Sources** - IronPython script with GUI that iterates over all the excitations in a design and exports the NF data corresponding to each source.  Repo: https://github.com/ansys-internal/HFSSExportNearFieldFromIndividualSources
* **Phase Shift Correction for FFD**.  Repo: https://github.com/ansys-internal/HFSSHybridArrayExportPhaseShift
* **HFSS Export of STK RCS** - IronPython script with GUI that exports FullComplexScatterMatrix .rcs format from HFSS for use in STK.  Repo: https://github.com/ansys-internal/HFSSExportSTKRCS

Ansys/Synopsys employees, reach out to admins or me to enable access (you'll likely get a 404 unless policies change since this writting)

If you are not a Synopsys/Ansys employee, reach out to your representative.
