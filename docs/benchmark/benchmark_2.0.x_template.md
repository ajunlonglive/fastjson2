## EishayParseBinary
| aliyun ecs spec | jdk version 	|	fastjson2JSONB	|	fastjson2UTF8Bytes	|	hessian	|	javaSerialize |
|-----|-----|----------|----------|----------|-----|
| ecs.c7.xlarge | oracle-jdk1.8.0_341_x64	|	1745.91	|	1146.229 (65.65%)	|	276.815 (15.86%)	|	45.864 (2.63%) |
| ecs.c7.xlarge | oracle-jdk-11.0.16_x64	|	2634.157	|	1135.099 (43.09%)	|	247.56 (9.4%)	|	48.875 (1.86%) |
| ecs.c7.xlarge | oracle-jdk-17.0.4_x64	|	2928.732	|	1232.146 (42.07%)	|	258.316 (8.82%)	|	53.003 (1.81%) |
| ecs.g8m.xlarge | oracle-jdk1.8.0_341_aarch64	|	1405.29	|	860.406 (61.23%)	|	208.791 (14.86%)	|	42.988 (3.06%) |
| ecs.g8m.xlarge | oracle-jdk-11.0.16_aarch64	|	2111.423	|	1031.57 (48.86%)	|	193.33 (9.16%)	|	39.983 (1.89%) |
| ecs.g8m.xlarge | oracle-jdk-17.0.4_aarch64	|	2288.4	|	1089.834 (47.62%)	|	226.228 (9.89%)	|	36.769 (1.61%) |

## EishayParseBinaryArrayMapping
| aliyun ecs spec | jdk version 	|	fastjson2JSONB	|	kryo	|	fastjson2UTF8Bytes	|	fastjson1UTF8Bytes |
|-----|-----|----------|----------|----------|-----|
| ecs.c7.xlarge | oracle-jdk1.8.0_341_x64	|	2761.666	|	1696.124 (61.42%)	|	1647.547 (59.66%)	|	1459.11 (52.83%) |
| ecs.c7.xlarge | oracle-jdk-11.0.16_x64	|	3932.143	|	1619.629 (41.19%)	|	1815.996 (46.18%)	|	1497.139 (38.07%) |
| ecs.c7.xlarge | oracle-jdk-17.0.4_x64	|	5020.29	|	1432.184 (28.53%)	|	1939.496 (38.63%)	|	1699.256 (33.85%) |
| ecs.g8m.xlarge | oracle-jdk1.8.0_341_aarch64	|	2411.173	|	1286.333 (53.35%)	|	1228.088 (50.93%)	|	1142.991 (47.4%) |
| ecs.g8m.xlarge | oracle-jdk-11.0.16_aarch64	|	3239.657	|	1405.794 (43.39%)	|	1560.39 (48.17%)	|	1270.627 (39.22%) |
| ecs.g8m.xlarge | oracle-jdk-17.0.4_aarch64	|	3396.391	|	1162.501 (34.23%)	|	1610.301 (47.41%)	|	1387.655 (40.86%) |

## EishayParseBinaryAutoType
| aliyun ecs spec | jdk version 	|	fastjson2JSONB	|	fastjson2JSONB_autoTypeFilter	|	hessian	|	javaSerialize |
|-----|-----|----------|----------|----------|-----|
| ecs.c7.xlarge | oracle-jdk1.8.0_341_x64	|	1423.78	|	1395.533 (98.02%)	|	287.764 (20.21%)	|	47.654 (3.35%) |
| ecs.c7.xlarge | oracle-jdk-11.0.16_x64	|	1972.141	|	1711.592 (86.79%)	|	249.47 (12.65%)	|	47.662 (2.42%) |
| ecs.c7.xlarge | oracle-jdk-17.0.4_x64	|	2213.489	|	1876.255 (84.76%)	|	254.031 (11.48%)	|	51.75 (2.34%) |
| ecs.g8m.xlarge | oracle-jdk1.8.0_341_aarch64	|	1230.93	|	1165.261 (94.67%)	|	210.171 (17.07%)	|	43.005 (3.49%) |
| ecs.g8m.xlarge | oracle-jdk-11.0.16_aarch64	|	1633.31	|	1556.502 (95.3%)	|	180.759 (11.07%)	|	40.755 (2.5%) |
| ecs.g8m.xlarge | oracle-jdk-17.0.4_aarch64	|	1608.237	|	1582.764 (98.42%)	|	193.034 (12%)	|	37.802 (2.35%) |

## EishayParseString
| aliyun ecs spec | jdk version 	|	fastjson2	|	fastjson1	|	jackson	|	gson |
|-----|-----|----------|----------|----------|-----|
| ecs.c7.xlarge | oracle-jdk1.8.0_341_x64	|	1323.858	|	982.148 (74.19%)	|	517.309 (39.08%)	|	427.025 (32.26%) |
| ecs.c7.xlarge | oracle-jdk-11.0.16_x64	|	1218.926	|	925.63 (75.94%)	|	475.128 (38.98%)	|	425.79 (34.93%) |
| ecs.c7.xlarge | oracle-jdk-17.0.4_x64	|	1341.893	|	1239.901 (92.4%)	|	503.87 (37.55%)	|	423.181 (31.54%) |
| ecs.g8m.xlarge | oracle-jdk1.8.0_341_aarch64	|	951.633	|	777.889 (81.74%)	|	377.255 (39.64%)	|	358.643 (37.69%) |
| ecs.g8m.xlarge | oracle-jdk-11.0.16_aarch64	|	1103.552	|	794.81 (72.02%)	|	400.342 (36.28%)	|	375.965 (34.07%) |
| ecs.g8m.xlarge | oracle-jdk-17.0.4_aarch64	|	1093.67	|	1004.368 (91.83%)	|	389.798 (35.64%)	|	361.481 (33.05%) |

## EishayParseStringPretty
| aliyun ecs spec | jdk version 	|	fastjson2	|	fastjson1	|	jackson	|	gson |
|-----|-----|----------|----------|----------|-----|
| ecs.c7.xlarge | oracle-jdk1.8.0_341_x64	|	923.861	|	271.362 (29.37%)	|	481.053 (52.07%)	|	401.565 (43.47%) |
| ecs.c7.xlarge | oracle-jdk-11.0.16_x64	|	881.41	|	237.561 (26.95%)	|	428.643 (48.63%)	|	401.457 (45.55%) |
| ecs.c7.xlarge | oracle-jdk-17.0.4_x64	|	920.565	|	299.886 (32.58%)	|	470.083 (51.06%)	|	422.964 (45.95%) |
| ecs.g8m.xlarge | oracle-jdk1.8.0_341_aarch64	|	772.223	|	224.357 (29.05%)	|	345.056 (44.68%)	|	331.756 (42.96%) |
| ecs.g8m.xlarge | oracle-jdk-11.0.16_aarch64	|	790.372	|	226.612 (28.67%)	|	365.176 (46.2%)	|	350.066 (44.29%) |
| ecs.g8m.xlarge | oracle-jdk-17.0.4_aarch64	|	790.844	|	262.743 (33.22%)	|	288.152 (36.44%)	|	270.417 (34.19%) |

## EishayParseTreeString
| aliyun ecs spec | jdk version 	|	fastjson2	|	fastjson1	|	jackson	|	gson |
|-----|-----|----------|----------|----------|-----|
| ecs.c7.xlarge | oracle-jdk1.8.0_341_x64	|	999.647	|	507.661 (50.78%)	|	532.279 (53.25%)	|	348.278 (34.84%) |
| ecs.c7.xlarge | oracle-jdk-11.0.16_x64	|	784.695	|	397.209 (50.62%)	|	459.978 (58.62%)	|	320.917 (40.9%) |
| ecs.c7.xlarge | oracle-jdk-17.0.4_x64	|	1053.872	|	550.747 (52.26%)	|	505.613 (47.98%)	|	321.34 (30.49%) |
| ecs.g8m.xlarge | oracle-jdk1.8.0_341_aarch64	|	599.3	|	303.988 (50.72%)	|	297.275 (49.6%)	|	280.526 (46.81%) |
| ecs.g8m.xlarge | oracle-jdk-11.0.16_aarch64	|	663.603	|	355.428 (53.56%)	|	360.372 (54.31%)	|	303.726 (45.77%) |
| ecs.g8m.xlarge | oracle-jdk-17.0.4_aarch64	|	786.345	|	409.156 (52.03%)	|	406.311 (51.67%)	|	267.144 (33.97%) |

## EishayParseTreeStringPretty
| aliyun ecs spec | jdk version 	|	fastjson2	|	fastjson1	|	jackson	|	gson |
|-----|-----|----------|----------|----------|-----|
| ecs.c7.xlarge | oracle-jdk1.8.0_341_x64	|	778.061	|	422.573 (54.31%)	|	508.11 (65.3%)	|	325.924 (41.89%) |
| ecs.c7.xlarge | oracle-jdk-11.0.16_x64	|	654.361	|	341.388 (52.17%)	|	411.78 (62.93%)	|	304.786 (46.58%) |
| ecs.c7.xlarge | oracle-jdk-17.0.4_x64	|	806.591	|	491.125 (60.89%)	|	477.171 (59.16%)	|	298.579 (37.02%) |
| ecs.g8m.xlarge | oracle-jdk1.8.0_341_aarch64	|	487.05	|	282.304 (57.96%)	|	314.568 (64.59%)	|	268.657 (55.16%) |
| ecs.g8m.xlarge | oracle-jdk-11.0.16_aarch64	|	635.494	|	287.082 (45.17%)	|	327.999 (51.61%)	|	285.944 (45%) |
| ecs.g8m.xlarge | oracle-jdk-17.0.4_aarch64	|	629.637	|	367.895 (58.43%)	|	362.61 (57.59%)	|	265.456 (42.16%) |

## EishayParseTreeUTF8Bytes
| aliyun ecs spec | jdk version 	|	fastjson2	|	fastjson1	|	jackson	|	gson |
|-----|-----|----------|----------|----------|-----|
| ecs.c7.xlarge | oracle-jdk1.8.0_341_x64	|	852.502	|	432.011 (50.68%)	|	597.233 (70.06%)	|	320.264 (37.57%) |
| ecs.c7.xlarge | oracle-jdk-11.0.16_x64	|	775.674	|	365.793 (47.16%)	|	509.321 (65.66%)	|	319.213 (41.15%) |
| ecs.c7.xlarge | oracle-jdk-17.0.4_x64	|	991.227	|	486.717 (49.1%)	|	576.491 (58.16%)	|	322.559 (32.54%) |
| ecs.g8m.xlarge | oracle-jdk1.8.0_341_aarch64	|	563.056	|	266.028 (47.25%)	|	366.695 (65.13%)	|	254.317 (45.17%) |
| ecs.g8m.xlarge | oracle-jdk-11.0.16_aarch64	|	735.733	|	265.604 (36.1%)	|	417.095 (56.69%)	|	296.295 (40.27%) |
| ecs.g8m.xlarge | oracle-jdk-17.0.4_aarch64	|	780.39	|	355.615 (45.57%)	|	468.263 (60%)	|	265.037 (33.96%) |

## EishayParseTreeUTF8BytesPretty
| aliyun ecs spec | jdk version 	|	fastjson2	|	fastjson1	|	jackson	|	gson |
|-----|-----|----------|----------|----------|-----|
| ecs.c7.xlarge | oracle-jdk1.8.0_341_x64	|	684.219	|	370.055 (54.08%)	|	537.251 (78.52%)	|	288.624 (42.18%) |
| ecs.c7.xlarge | oracle-jdk-11.0.16_x64	|	659.008	|	310.89 (47.18%)	|	489.176 (74.23%)	|	297.134 (45.09%) |
| ecs.c7.xlarge | oracle-jdk-17.0.4_x64	|	722.042	|	396.861 (54.96%)	|	502.276 (69.56%)	|	291.768 (40.41%) |
| ecs.g8m.xlarge | oracle-jdk1.8.0_341_aarch64	|	486.655	|	230.377 (47.34%)	|	343.643 (70.61%)	|	239.741 (49.26%) |
| ecs.g8m.xlarge | oracle-jdk-11.0.16_aarch64	|	617.956	|	209.79 (33.95%)	|	388.13 (62.81%)	|	277.333 (44.88%) |
| ecs.g8m.xlarge | oracle-jdk-17.0.4_aarch64	|	626.471	|	245.386 (39.17%)	|	418.541 (66.81%)	|	225.564 (36.01%) |

## EishayParseUTF8Bytes
| aliyun ecs spec | jdk version 	|	fastjson2	|	dsljson	|	fastjson1	|	jackson	|	gson |
|-----|-----|----------|----------|----------|----------|-----|
| ecs.c7.xlarge | oracle-jdk1.8.0_341_x64	|	1097.462	|	868.012 (79.09%)	|	779.785 (71.05%)	|	594.846 (54.2%)	|	317.638 (28.94%) |
| ecs.c7.xlarge | oracle-jdk-11.0.16_x64	|	1049.985	|	862.175 (82.11%)	|	754.394 (71.85%)	|	553.14 (52.68%)	|	315.802 (30.08%) |
| ecs.c7.xlarge | oracle-jdk-17.0.4_x64	|	1139.991	|	822.273 (72.13%)	|	951.899 (83.5%)	|	555.618 (48.74%)	|	317.956 (27.89%) |
| ecs.g8m.xlarge | oracle-jdk1.8.0_341_aarch64	|	843.91	|	669.183 (79.3%)	|	662.392 (78.49%)	|	442.84 (52.47%)	|	259.758 (30.78%) |
| ecs.g8m.xlarge | oracle-jdk-11.0.16_aarch64	|	996.623	|	681.642 (68.4%)	|	678.046 (68.03%)	|	462.799 (46.44%)	|	295.187 (29.62%) |
| ecs.g8m.xlarge | oracle-jdk-17.0.4_aarch64	|	1009.637	|	590.536 (58.49%)	|	760.413 (75.32%)	|	460.009 (45.56%)	|	256.439 (25.4%) |

## EishayParseUTF8BytesPretty
| aliyun ecs spec | jdk version 	|	fastjson2	|	fastjson1	|	jackson	|	gson |
|-----|-----|----------|----------|----------|-----|
| ecs.c7.xlarge | oracle-jdk1.8.0_341_x64	|	829.024	|	246.824 (29.77%)	|	511.346 (61.68%)	|	290.724 (35.07%) |
| ecs.c7.xlarge | oracle-jdk-11.0.16_x64	|	840.712	|	224.995 (26.76%)	|	489.954 (58.28%)	|	303.847 (36.14%) |
| ecs.c7.xlarge | oracle-jdk-17.0.4_x64	|	865.528	|	271.334 (31.35%)	|	496.775 (57.4%)	|	304.859 (35.22%) |
| ecs.g8m.xlarge | oracle-jdk1.8.0_341_aarch64	|	698.082	|	208.892 (29.92%)	|	382.304 (54.76%)	|	237.519 (34.02%) |
| ecs.g8m.xlarge | oracle-jdk-11.0.16_aarch64	|	727.576	|	162.69 (22.36%)	|	403.849 (55.51%)	|	279.494 (38.41%) |
| ecs.g8m.xlarge | oracle-jdk-17.0.4_aarch64	|	756.069	|	243.031 (32.14%)	|	418.411 (55.34%)	|	261.294 (34.56%) |

## EishayWriteBinary
| aliyun ecs spec | jdk version 	|	fastjson2JSONB	|	fastjson2UTF8Bytes	|	hessian	|	javaSerialize |
|-----|-----|----------|----------|----------|-----|
| ecs.c7.xlarge | oracle-jdk1.8.0_341_x64	|	2057.518	|	1527.653 (74.25%)	|	342.37 (16.64%)	|	229.569 (11.16%) |
| ecs.c7.xlarge | oracle-jdk-11.0.16_x64	|	2463.229	|	1609.664 (65.35%)	|	332.56 (13.5%)	|	211.839 (8.6%) |
| ecs.c7.xlarge | oracle-jdk-17.0.4_x64	|	3366.385	|	1923.188 (57.13%)	|	317.751 (9.44%)	|	220.755 (6.56%) |
| ecs.g8m.xlarge | oracle-jdk1.8.0_341_aarch64	|	1678.391	|	1344.197 (80.09%)	|	354.066 (21.1%)	|	209.384 (12.48%) |
| ecs.g8m.xlarge | oracle-jdk-11.0.16_aarch64	|	2186.228	|	1449.958 (66.32%)	|	346.928 (15.87%)	|	221.442 (10.13%) |
| ecs.g8m.xlarge | oracle-jdk-17.0.4_aarch64	|	2095.549	|	1429.841 (68.23%)	|	336.325 (16.05%)	|	199.163 (9.5%) |

## EishayWriteBinaryArrayMapping
| aliyun ecs spec | jdk version 	|	fastjson2JSONB	|	kryo	|	fastjson2UTF8Bytes	|	fastjson1UTF8Bytes |
|-----|-----|----------|----------|----------|-----|
| ecs.c7.xlarge | oracle-jdk1.8.0_341_x64	|	3080.203	|	1905.839 (61.87%)	|	1852.425 (60.14%)	|	754.25 (24.49%) |
| ecs.c7.xlarge | oracle-jdk-11.0.16_x64	|	4506.065	|	1985.027 (44.05%)	|	2101.397 (46.63%)	|	677.97 (15.05%) |
| ecs.c7.xlarge | oracle-jdk-17.0.4_x64	|	5719.26	|	1887.01 (32.99%)	|	2169.409 (37.93%)	|	695.466 (12.16%) |
| ecs.g8m.xlarge | oracle-jdk1.8.0_341_aarch64	|	2643.814	|	1437.302 (54.36%)	|	1585.289 (59.96%)	|	474.295 (17.94%) |
| ecs.g8m.xlarge | oracle-jdk-11.0.16_aarch64	|	4172.809	|	1556.759 (37.31%)	|	1312.569 (31.46%)	|	427.747 (10.25%) |
| ecs.g8m.xlarge | oracle-jdk-17.0.4_aarch64	|	4226.555	|	1424.594 (33.71%)	|	1730.064 (40.93%)	|	538.222 (12.73%) |

## EishayWriteBinaryAutoType
| aliyun ecs spec | jdk version 	|	fastjson2JSONB	|	fastjson2UTF8Bytes	|	hessian	|	javaSerialize |
|-----|-----|----------|----------|----------|-----|
| ecs.c7.xlarge | oracle-jdk1.8.0_341_x64	|	1356.46	|	1472.171 (108.53%)	|	345.464 (25.47%)	|	230.477 (16.99%) |
| ecs.c7.xlarge | oracle-jdk-11.0.16_x64	|	1417.547	|	1543.54 (108.89%)	|	333.694 (23.54%)	|	211.004 (14.89%) |
| ecs.c7.xlarge | oracle-jdk-17.0.4_x64	|	1685.941	|	1835.123 (108.85%)	|	314.312 (18.64%)	|	219.537 (13.02%) |
| ecs.g8m.xlarge | oracle-jdk1.8.0_341_aarch64	|	1140.792	|	1302.846 (114.21%)	|	341.365 (29.92%)	|	209.422 (18.36%) |
| ecs.g8m.xlarge | oracle-jdk-11.0.16_aarch64	|	1339.791	|	1370.818 (102.32%)	|	341.088 (25.46%)	|	205.958 (15.37%) |
| ecs.g8m.xlarge | oracle-jdk-17.0.4_aarch64	|	1261.381	|	1397.386 (110.78%)	|	333.762 (26.46%)	|	208.898 (16.56%) |

## EishayWriteString
| aliyun ecs spec | jdk version 	|	fastjson2	|	fastjson1	|	jackson	|	gson |
|-----|-----|----------|----------|----------|-----|
| ecs.c7.xlarge | oracle-jdk1.8.0_341_x64	|	1621.491	|	616.435 (38.02%)	|	974.255 (60.08%)	|	446.25 (27.52%) |
| ecs.c7.xlarge | oracle-jdk-11.0.16_x64	|	1464.777	|	585.129 (39.95%)	|	928.165 (63.37%)	|	352.143 (24.04%) |
| ecs.c7.xlarge | oracle-jdk-17.0.4_x64	|	1639.719	|	603.79 (36.82%)	|	1032.774 (62.98%)	|	235.628 (14.37%) |
| ecs.g8m.xlarge | oracle-jdk1.8.0_341_aarch64	|	1266.311	|	479.864 (37.89%)	|	653.777 (51.63%)	|	343.324 (27.11%) |
| ecs.g8m.xlarge | oracle-jdk-11.0.16_aarch64	|	1256.394	|	461.363 (36.72%)	|	624.14 (49.68%)	|	314.902 (25.06%) |
| ecs.g8m.xlarge | oracle-jdk-17.0.4_aarch64	|	1281.334	|	526.377 (41.08%)	|	550.006 (42.92%)	|	210.608 (16.44%) |

## EishayWriteStringTree
| aliyun ecs spec | jdk version 	|	fastjson2	|	fastjson1	|	jackson	|	gson |
|-----|-----|----------|----------|----------|-----|
| ecs.c7.xlarge | oracle-jdk1.8.0_341_x64	|	1240.164	|	780.375 (62.93%)	|	888.625 (71.65%)	|	490.39 (39.54%) |
| ecs.c7.xlarge | oracle-jdk-11.0.16_x64	|	1258.199	|	787.432 (62.58%)	|	944.223 (75.05%)	|	394.369 (31.34%) |
| ecs.c7.xlarge | oracle-jdk-17.0.4_x64	|	1167.44	|	811.931 (69.55%)	|	873.917 (74.86%)	|	248.604 (21.29%) |
| ecs.g8m.xlarge | oracle-jdk1.8.0_341_aarch64	|	968.298	|	590.892 (61.02%)	|	688.129 (71.07%)	|	419.16 (43.29%) |
| ecs.g8m.xlarge | oracle-jdk-11.0.16_aarch64	|	1028.048	|	598.446 (58.21%)	|	740.239 (72%)	|	324.587 (31.57%) |
| ecs.g8m.xlarge | oracle-jdk-17.0.4_aarch64	|	1094.089	|	636.337 (58.16%)	|	686.431 (62.74%)	|	219.365 (20.05%) |

## EishayWriteStringTree1x
| aliyun ecs spec | jdk version 	|	fastjson2	|	fastjson1	|	jackson	|	gson |
|-----|-----|----------|----------|----------|-----|
| ecs.c7.xlarge | oracle-jdk1.8.0_341_x64	|	1136.139	|	796.314 (70.09%)	|	920.276 (81%)	|	477.85 (42.06%) |
| ecs.c7.xlarge | oracle-jdk-11.0.16_x64	|	1147.489	|	726.937 (63.35%)	|	893.055 (77.83%)	|	377.213 (32.87%) |
| ecs.c7.xlarge | oracle-jdk-17.0.4_x64	|	901.294	|	717.182 (79.57%)	|	761.599 (84.5%)	|	242.727 (26.93%) |
| ecs.g8m.xlarge | oracle-jdk1.8.0_341_aarch64	|	832.749	|	578.747 (69.5%)	|	631.931 (75.88%)	|	390.154 (46.85%) |
| ecs.g8m.xlarge | oracle-jdk-11.0.16_aarch64	|	932.86	|	580.227 (62.2%)	|	715.541 (76.7%)	|	347.5 (37.25%) |
| ecs.g8m.xlarge | oracle-jdk-17.0.4_aarch64	|	739.189	|	571.86 (77.36%)	|	641.065 (86.73%)	|	215.321 (29.13%) |

## EishayWriteUTF8Bytes
| aliyun ecs spec | jdk version 	|	fastjson2	|	fastjson1	|	jackson	|	gson |
|-----|-----|----------|----------|----------|-----|
| ecs.c7.xlarge | oracle-jdk1.8.0_341_x64	|	1502.875	|	569.395 (37.89%)	|	901.732 (60%)	|	350.641 (23.33%) |
| ecs.c7.xlarge | oracle-jdk-11.0.16_x64	|	1592.584	|	537.93 (33.78%)	|	855.947 (53.75%)	|	351.36 (22.06%) |
| ecs.c7.xlarge | oracle-jdk-17.0.4_x64	|	1922.001	|	558.529 (29.06%)	|	969.965 (50.47%)	|	234.736 (12.21%) |
| ecs.g8m.xlarge | oracle-jdk1.8.0_341_aarch64	|	1348.165	|	472.104 (35.02%)	|	673.881 (49.99%)	|	311.596 (23.11%) |
| ecs.g8m.xlarge | oracle-jdk-11.0.16_aarch64	|	1445.026	|	384.077 (26.58%)	|	538.124 (37.24%)	|	316.287 (21.89%) |
| ecs.g8m.xlarge | oracle-jdk-17.0.4_aarch64	|	1144.691	|	446.46 (39%)	|	676.314 (59.08%)	|	213.773 (18.68%) |
