// Barra superior con título
            TopAppBar(
                title = {
                    //Boton Flecha
                    IconButton(
                        onClick = {}
                    ) { Icon(
                        painter = painterResource(R.drawable.flecha),
                        contentDescription = "owo",
                        modifier = Modifier
                            .size(20.dp)
                    ) }

                    Text(
                        "Camisas",
                        modifier = Modifier
                            .fillMaxSize()
                            .padding(top = 11.dp),
                        textAlign = TextAlign.Center,
                        fontWeight = FontWeight.Bold
                    )
                },
                colors = TopAppBarDefaults.topAppBarColors(
                    containerColor = MaterialTheme.colorScheme.surfaceVariant,
                    titleContentColor = MaterialTheme.colorScheme.onSurface

                )
            )
