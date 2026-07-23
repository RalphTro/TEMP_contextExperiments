 "sensorElementList": {
                "@id": "epcis:sensorElementList",
                "@container": "@set",
                "@context": {
                    "@protected": true,
                    "deviceID": {
                        "@id": "epcis:deviceID",
                        "@type": "@id"
                    },
                    "deviceMetadata": {
                        "@id": "epcis:deviceMetadata",
                        "@type": "@id"
                    },
                    "rawData": {
                        "@id": "epcis:rawData",
                        "@type": "@id"
                    },
                    "dataProcessingMethod": {
                        "@id": "epcis:dataProcessingMethod",
                        "@type": "@id"
                    },
                    "time": {
                        "@id": "epcis:time",
                        "@type": "xsd:dateTimeStamp"
                    },
                    "type": "@type",
                    "sensorMetadata": {
                        "@id": "epcis:sensorMetadata",
                        "@context": {
                            "@protected": true,
                            "startTime": {
                                "@id": "epcis:startTime",
                                "@type": "xsd:dateTimeStamp"
                            },
                            "endTime": {
                                "@id": "epcis:endTime",
                                "@type": "xsd:dateTimeStamp"
                            },
                            "bizRules": {
                                "@id": "epcis:bizRules",
                                "@type": "@id"
                            }
                        }
                    },
                    "sensorReport": {
                        "@id": "epcis:sensorReport",
                        "@context": {
                            "@protected": true,
                            "type": {
                                "@context": {
                                    "AbsoluteHumidity": "gs1:AbsoluteHumidity",
                                    "AbsorbedDose": "gs1:AbsorbedDose",
                                    "AbsorbedDoseRate": "gs1:AbsorbedDoseRate",
                                    "Acceleration": "gs1:Acceleration",
                                    "Radioactivity": "gs1:Radioactivity",
                                    "Altitude": "gs1:Altitude",
                                    "AmountOfSubstance": "gs1:AmountOfSubstance",
                                    "AmountOfSubstancePerUnitVolume": "gs1:AmountOfSubstancePerUnitVolume",
                                    "Angle": "gs1:Angle",
                                    "AngularAcceleration": "gs1:AngularAcceleration",
                                    "AngularMomentum": "gs1:AngularMomentum",
                                    "AngularVelocity": "gs1:AngularVelocity",
                                    "Area": "gs1:Area",
                                    "Capacitance": "gs1:Capacitance",
                                    "Conductance": "gs1:Conductance",
                                    "Conductivity": "gs1:Conductivity",
                                    "Count": "gs1:Count",
                                    "Density": "gs1:Density",
                                    "Dimensionless": "gs1:Dimensionless",
                                    "DoseEquivalent": "gs1:DoseEquivalent",
                                    "DoseEquivalentRate": "gs1:DoseEquivalentRate",
                                    "DynamicViscosity": "gs1:DynamicViscosity",
                                    "ElectricCharge": "gs1:ElectricCharge",
                                    "ElectricCurrent": "gs1:ElectricCurrent",
                                    "ElectricCurrentDensity": "gs1:ElectricCurrentDensity",
                                    "ElectricFieldStrength": "gs1:ElectricFieldStrength",
                                    "Energy": "gs1:Energy",
                                    "Exposure": "gs1:Exposure",
                                    "Force": "gs1:Force",
                                    "Frequency": "gs1:Frequency",
                                    "Illuminance": "gs1:Illuminance",
                                    "Inductance": "gs1:Inductance",
                                    "Irradiance": "gs1:Irradiance",
                                    "KinematicViscosity": "gs1:KinematicViscosity",
                                    "Length": "gs1:Length",
                                    "LinearMomentum": "gs1:LinearMomentum",
                                    "Luminance": "gs1:Luminance",
                                    "LuminousFlux": "gs1:LuminousFlux",
                                    "LuminousIntensity": "gs1:LuminousIntensity",
                                    "MagneticFlux": "gs1:MagneticFlux",
                                    "MagneticFluxDensity": "gs1:MagneticFluxDensity",
                                    "MagneticVectorPotential": "gs1:MagneticVectorPotential",
                                    "Mass": "gs1:Mass",
                                    "MassConcentration": "gs1:MassConcentration",
                                    "MassFlowRate": "gs1:MassFlowRate",
                                    "MassPerAreaTime": "gs1:MassPerAreaTime",
                                    "MemoryCapacity": "gs1:MemoryCapacity",
                                    "MolalityOfSolute": "gs1:MolalityOfSolute",
                                    "MolarEnergy": "gs1:MolarEnergy",
                                    "MolarMass": "gs1:MolarMass",
                                    "MolarVolume": "gs1:MolarVolume",
                                    "Power": "gs1:Power",
                                    "Pressure": "gs1:Pressure",
                                    "RadiantFlux": "gs1:RadiantFlux",
                                    "RadiantIntensity": "gs1:RadiantIntensity",
                                    "RelativeHumidity": "gs1:RelativeHumidity",
                                    "Resistance": "gs1:Resistance",
                                    "Resistivity": "gs1:Resistivity",
                                    "SolidAngle": "gs1:SolidAngle",
                                    "SpecificVolume": "gs1:SpecificVolume",
                                    "Speed": "gs1:Speed",
                                    "SurfaceDensity": "gs1:SurfaceDensity",
                                    "SurfaceTension": "gs1:SurfaceTension",
                                    "Temperature": "gs1:Temperature",
                                    "Time": "gs1:Time",
                                    "Torque": "gs1:Torque",
                                    "Voltage": "gs1:Voltage",
                                    "Volume": "gs1:Volume",
                                    "VolumeFlowRate": "gs1:VolumeFlowRate",
                                    "VolumeFraction": "gs1:VolumeFraction",
                                    "VolumetricFlux": "gs1:VolumetricFlux",
                                    "Wavenumber": "gs1:Wavenumber"
                                },
                                "@id": "epcis:measurementType",
                                "@type": "@vocab"
                            },
                            "exception": {
                                "@context": {
                                    "ALARM_CONDITION": "gs1:ALARM_CONDITION",
                                    "ERROR_CONDITION": "gs1:ERROR_CONDITION"
                                },
                                "@type": "@vocab"
                            },
                            "coordinateReferenceSystem": {
                                "@id": "epcis:coordinateReferenceSystem",
                                "@type": "@id"
                            },
                            "microorganism": {
                                "@id": "epcis:microorganism",
                                "@type": "@id"
                            },
                            "chemicalSubstance": {
                                "@id": "epcis:chemicalSubstance",
                                "@type": "@id"
                            },
                            "time": {
                                "@id": "epcis:time",
                                "@type": "xsd:dateTimeStamp"
                            },
                            "component": {
                                "@context": {
                                    "x": "cbv:Comp-x",
                                    "y": "cbv:Comp-y",
                                    "z": "cbv:Comp-z",
                                    "axial_distance": "cbv:Comp-axial_distance",
                                    "azimuth": "cbv:Comp-azimuth",
                                    "height": "cbv:Comp-height",
                                    "spherical_radius": "cbv:Comp-spherical_radius",
                                    "polar_angle": "cbv:Comp-polar_angle",
                                    "elevation_angle": "cbv:Comp-elevation_angle",
                                    "easting": "cbv:Comp-easting",
                                    "northing": "cbv:Comp-northing",
                                    "latitude": "cbv:Comp-latitude",
                                    "longitude": "cbv:Comp-longitude",
                                    "altitude": "cbv:Comp-altitude"
                                },
                                "@id": "epcis:component",
                                "@type": "@vocab"
                            },
                            "stringValue": "epcis:stringValue",
                            "booleanValue": {
                                "@id": "epcis:booleanValue",
                                "@type": "xsd:boolean"
                            },
                            "hexBinaryValue": {
                                "@id": "epcis:hexBinaryValue",
                                "@type": "xsd:hexBinary"
                            },
                            "uriValue": {
                                "@id": "epcis:uriValue",
                                "@type": "@id"
                            },
                            "minValue": {
                                "@id": "epcis:minValue",
                                "@type": "xsd:double"
                            },
                            "maxValue": {
                                "@id": "epcis:maxValue",
                                "@type": "xsd:double"
                            },
                            "value": {
                                "@id": "epcis:value",
                                "@type": "xsd:double"
                            },
                            "meanValue": {
                                "@id": "epcis:meanValue",
                                "@type": "xsd:double"
                            },
                            "sDev": {
                                "@id": "epcis:sDev",
                                "@type": "xsd:double"
                            },
                            "percRank": {
                                "@id": "epcis:percRank",
                                "@type": "xsd:double"
                            },
                            "percValue": {
                                "@id": "epcis:percValue",
                                "@type": "xsd:double"
                            }
                        }
                    }
                }
            },


              "sourceList": {
                "@id": "epcis:sourceList",
                "@container": "@set",
                "@context": {
                    "@protected": true,
                    "source": {
                        "@id": "epcis:sourceOrDestination",
                        "@type": "@id"
                    },
                    "type": {
                        "@id": "epcis:sourceOrDestinationType",
                        "@type": "@vocab",
                        "@context": {
                            "owning_party": "cbv:SDT-owning_party",
                            "possessing_party": "cbv:SDT-possessing_party",
                            "location": "cbv:SDT-location"
                        }
                    }
                }
            },
            "destinationList": {
                "@id": "epcis:destinationList",
                "@container": "@set",
                "@context": {
                    "@protected": true,
                    "destination": {
                        "@id": "epcis:sourceOrDestination",
                        "@type": "@id"
                    },
                    "type": {
                        "@id": "epcis:sourceOrDestinationType",
                        "@type": "@vocab",
                        "@context": {
                            "owning_party": "cbv:SDT-owning_party",
                            "possessing_party": "cbv:SDT-possessing_party",
                            "location": "cbv:SDT-location"
                        }
                    }
                }
            },

            