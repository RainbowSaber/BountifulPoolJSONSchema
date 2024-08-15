Schema file for the Bountiful Minecraft Mod that can lint and help with creation of new files through auto complete and descriptions.

Can be natively added to VSC as a json Schema using the following entry in the workspace settings

		"json.schemas": [
			{
				"fileMatch": [
					"**/data/bountiful/bounty_pools/**"
				],
				"url": "./bountiful/bountiful_schema.json"
			}
		]
