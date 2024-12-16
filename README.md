se game.PlaceId == 2753915549 então
    Mundo1 = verdadeiro
elseif game.PlaceId == 4442272183 então
    Mundo2 = verdadeiro
elseif game.PlaceId == 7449423635 então
    Mundo3 = verdadeiro
outro
    game:GetService("Jogadores").LocalPlayer:Kick("Não dê suporte, aguarde...")
fim

função CheckQuest()
    MeuNível = jogo:GetService("Jogadores").LocalPlayer.Data.Level.Value
    se World1 então
        se MyLevel == 1 ou MyLevel <= 9 então
            Seg = "Bandido"
            LevelQuest = 1
            NomeQuest = "BanditQuest1"
            NomeMon = "Bandido"
            CFrameQuest = CFrame.new(1059.37195, 15.4495068, 1550.4231, 0.939700544, -0, -0.341998369, 0, 1, -0, 0.341998369, 0, 0.939700544)
            CFrameMon = CFrame.new(1045.962646484375, 27.00250816345215, 1560.8203125)
        elseif MeuNível == 10 ou MeuNível <= 14 então
            Seg = "Macaco"
            LevelQuest = 1
            NomeQuest = "JungleQuest"
            NomeMon = "Macaco"
            CFrameQuest = CFrame.new(-1598.08911, 35.5501175, 153.377838, 0, 0, 1, 0, 1, -0, -1, 0, 0)
            CFrameMon = CFrame.new(-1448.51806640625, 67.85301208496094, 11.46579647064209)
        elseif MeuNível == 15 ou MeuNível <= 29 então
            Seg = "Gorila"
            LevelQuest = 2
            NomeQuest = "JungleQuest"
            NomeMon = "Gorila"
            CFrameQuest = CFrame.new(-1598.08911, 35.5501175, 153.377838, 0, 0, 1, 0, 1, -0, -1, 0, 0)
            CFrameMon = CFrame.new(-1129.8836669921875, 40.46354675292969, -525.4237060546875)
        elseif MeuNível == 30 ou MeuNível <= 39 então
            Seg = "Pirata"
            LevelQuest = 1
            NomeQuest = "BuggyQuest1"
            NomeMon = "Pirata"
            CFrameQuest = CFrame.new(-1141.07483, 4.10001802, 3831.5498, 0.965929627, -0, -0.258804798, 0, 1, -0, 0.258804798, 0, 0.965929627)
            CFrameMon = CFrame.new(-1103.513427734375, 13.752052307128906, 3896.091064453125)
        elseif MeuNível == 40 ou MeuNível <= 59 então
            Seg = "Bruto"
            LevelQuest = 2
            NomeQuest = "BuggyQuest1"
            NomeMon = "Bruto"
            CFrameQuest = CFrame.new(-1141.07483, 4.10001802, 3831.5498, 0.965929627, -0, -0.258804798, 0, 1, -0, 0.258804798, 0, 0.965929627)
            CFrameMon = CFrame.new(-1140.083740234375, 14.809885025024414, 4322.92138671875)
        elseif MeuNível == 60 ou MeuNível <= 74 então
            Mon = "Bandido do Deserto"
            LevelQuest = 1
            NomeQuest = "DesertQuest"
            NomeMon = "Bandido do Deserto"
            CFrameQuest = CFrame.new(894.488647, 5.14000702, 4392.43359, 0.819155693, -0, -0.573571265, 0, 1, -0, 0.573571265, 0, 0.819155693)
            CFrameMon = CFrame.new(924.7998046875, 6.44867467880249, 4481.5859375)
        elseif MeuNível == 75 ou MeuNível <= 89 então
            Mon = "Oficial do Deserto"
            LevelQuest = 2
            NomeQuest = "DesertQuest"
            NomeMon = "Oficial do Deserto"
            CFrameQuest = CFrame.new(894.488647, 5.14000702, 4392.43359, 0.819155693, -0, -0.573571265, 0, 1, -0, 0.573571265, 0, 0.819155693)
            CFrameMon = CFrame.new(1608.2822265625, 8.614224433898926, 4371.00732421875)
        elseif MeuNível == 90 ou MeuNível <= 99 então
            Seg = "Bandido da Neve"
            LevelQuest = 1
            NomeQuest = "Quest de Neve"
            NomeMon = "Bandido da Neve"
            CFrameQuest = CFrame.new(1389.74451, 88.1519318, -1298.90796, -0.342042685, 0, 0.939684391, 0, 1, 0, -0.939684391, 0, -0.342042685)
            CFrameMon = CFrame.new(1354.347900390625, 87.27277374267578, -1393.946533203125)
        elseif MeuNível == 100 ou MeuNível <= 119 então
            Seg = "Boneco de Neve"
            LevelQuest = 2
            NomeQuest = "Quest de Neve"
            NomeMon = "Boneco de Neve"
            CFrameQuest = CFrame.new(1389.74451, 88.1519318, -1298.90796, -0.342042685, 0, 0.939684391, 0, 1, 0, -0.939684391, 0, -0.342042685)
            CFrameMon = CFrame.new(1201.6412353515625, 144.57958984375, -1550.0670166015625)
        elseif MeuNível == 120 ou MeuNível <= 149 então
            Mon = "Suboficial Chefe"
            LevelQuest = 1
            NomeQuest = "MarineQuest2"
            NomeMon = "Suboficial Chefe"
            CFrameQuest = CFrame.new(-5039.58643, 27.3500385, 4324.68018, 0, 0, -1, 0, 1, 0, 1, 0, 0)
            CFrameMon = CFrame.novo(-4881.23095703125, 22.65204429626465, 4273.75244140625)
        elseif MeuNível == 150 ou MeuNível <= 174 então
            Seg = "Bandido do Céu"
            LevelQuest = 1
            NomeQuest = "SkyQuest"
            NomeMon = "Bandido do Céu"
            CFrameQuest = CFrame.new(-4839.53027, 716.368591, -2619.44165, 0.866007268, 0, 0.500031412, 0, 1, 0, -0.500031412, 0, 0.866007268)
            CFrameMon = CFrame.novo(-4953.20703125, 295.74420166015625, -2899.22900390625)
        elseif MeuNível == 175 ou MeuNível <= 189 então
            Mon = "Mestre das Trevas"
            LevelQuest = 2
            NomeQuest = "SkyQuest"
            NomeMon = "Mestre das Trevas"
            CFrameQuest = CFrame.new(-4839.53027, 716.368591, -2619.44165, 0.866007268, 0, 0.500031412, 0, 1, 0, -0.500031412, 0, 0.866007268)
            CFrameMon = CFrame.novo(-5259.8447265625, 391.3976745605469, -2229.035400390625)
        elseif MeuNível == 190 ou MeuNível <= 209 então
            Seg = "Prisioneiro"
            LevelQuest = 1
            NameQuest = "Quest do Prisioneiro"
            NomeMon = "Prisioneiro"
            CFrameQuest = CFrame.new(5308.93115, 1.65517521, 475.120514, -0.0894274712, -5.00292918e-09, -0.995993316, 1.60817859e-09, 1, -5.16744869e-09, 0.995993316, -2.06384709e-09, -0.0894274712)
            CFrameMon = CFrame.new(5098.9736328125, -0.3204058110713959, 474.2373352050781)
        elseif MeuNível == 210 ou MeuNível <= 249 então
            Mon = "Prisioneiro Perigoso"
            LevelQuest = 2
            NameQuest = "Quest do Prisioneiro"
            NameMon = "Prisioneiro Perigoso"
            CFrameQuest = CFrame.new(5308.93115, 1.65517521, 475.120514, -0.0894274712, -5.00292918e-09, -0.995993316, 1.60817859e-09, 1, -5.16744869e-09, 0.995993316, -2.06384709e-09, -0.0894274712)
            CFrameMon = CFrame.new(5654.5634765625, 15.633401870727539, 866.2991943359375)
        elseif MeuNível == 250 ou MeuNível <= 274 então
            Mon = "Guerreiro Toga"
            LevelQuest = 1
            NameQuest = "ColosseumQuest"
            NomeMon = "Guerreiro Toga"
            CFrameQuest = CFrame.new(-1580.04663, 6.35000277, -2986.47534, -0.515037298, 0, -0.857167721, 0, 1, 0, 0.857167721, 0, -0.515037298)
            CFrameMon = CFrame.novo(-1820.21484375, 51.68385696411133, -2740.6650390625)
        elseif MeuNível == 275 ou MeuNível <= 299 então
            Seg = "Gladiador"
            LevelQuest = 2
            NameQuest = "ColosseumQuest"
            NomeMon = "Gladiador"
            CFrameQuest = CFrame.new(-1580.04663, 6.35000277, -2986.47534, -0.515037298, 0, -0.857167721, 0, 1, 0, 0.857167721, 0, -0.515037298)
            CFrameMon = CFrame.new(-1292.838134765625, 56.380882263183594, -3339.031494140625)
        elseif MeuNível == 300 ou MeuNível <= 324 então
            Mon = "Soldado Militar"
            LevelQuest = 1
            NomeQuest = "MagmaQuest"
            NomeMon = "Soldado Militar"
            CFrameQuest = CFrame.new(-5313.37012, 10.9500084, 8515.29395, -0.499959469, 0, 0.866048813, 0, 1, 0, -0.866048813, 0, -0.499959469)
            CFrameMon = CFrame.new(-5411.16455078125, 11.081554412841797, 8454.29296875)
        elseif MeuNível == 325 ou MeuNível <= 374 então
            Mon = "Espião Militar"
            LevelQuest = 2
            NomeQuest = "MagmaQuest"
            NameMon = "Espião Militar"
            CFrameQuest = CFrame.new(-5313.37012, 10.9500084, 8515.29395, -0.499959469, 0, 0.866048813, 0, 1, 0, -0.866048813, 0, -0.499959469)
            CFrameMon = CFrame.novo(-5802.8681640625, 86.26241302490234, 8828.859375)
        elseif MeuNível == 375 ou MeuNível <= 399 então
            Mon = "Guerreiro Homem-Peixe"
            LevelQuest = 1
            NomeQuest = "PeixeQuest"
            NomeMon = "Guerreiro Homem-Peixe"
            CFrameQuest = CFrame.new(61122.65234375, 18.497442245483, 1569.3997802734)
            CFrameMon = CFrame.new(60878.30078125, 18.482830047607422, 1543.7574462890625)
            se _G.AutoFarm e (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 10000 então
                jogo:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(61163.8515625, 11.6796875, 1819.7841796875))
            fim
        elseif MeuNível == 400 ou MeuNível <= 449 então
            Seg = "Comando dos Homens-Peixe"
            LevelQuest = 2
            NomeQuest = "PeixeQuest"
            NomeMon = "Comando Fishman"
            CFrameQuest = CFrame.new(61122.65234375, 18.497442245483, 1569.3997802734)
            CFrameMon = CFrame.new(61922.6328125, 18.482830047607422, 1493.934326171875)
            se _G.AutoFarm e (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 10000 então
                jogo:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(61163.8515625, 11.6796875, 1819.7841796875))
            fim
        senão se MyLevel == 450 ou MyLevel <= 474 então
            Seg = "Guarda de Deus"
            LevelQuest = 1
            NomeQuest = "SkyExp1Quest"
            NomeMon = "Guarda de Deus"
            CFrameQuest = CFrame.new(-4721,88867, 843,874695, -1949,96643, 0,996191859, -0, -0,0871884301, 0, 1, -0, 0,0871884301, 0, 0,996191859)
            CFrameMon = CFrame.novo(-4710.04296875, 845.2769775390625, -1927.3079833984375)
            se _G.AutoFarm e (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 10000 então
                jogo:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(-4607.82275, 872.54248, -1667.55688))
            fim
        elseif MeuNível == 475 ou MeuNível <= 524 então
            Seg = "Shanda"
            LevelQuest = 2
            NomeQuest = "SkyExp1Quest"
            NomeMon = "Shanda"
            CFrameQuest = CFrame.new(-7859.09814, 5544.19043, -381.476196, -0.422592998, 0, 0.906319618, 0, 1, 0, -0.906319618, 0, -0.422592998)
            CFrameMon = CFrame.novo(-7678.48974609375, 5566.40380859375, -497.2156066894531)
            se _G.AutoFarm e (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 10000 então
                jogo:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(-7894.6176757813, 5547.1416015625, -380.29119873047))
            fim
        elseif MeuNível == 525 ou MeuNível <= 549 então
            Seg = "Esquadrão Real"
            LevelQuest = 1
            NomeQuest = "SkyExp2Quest"
            NomeMon = "Esquadrão Real"
            CFrameQuest = CFrame.new(-7906.81592, 5634.6626, -1411.99194, 0, 0, -1, 0, 1, 0, 1, 0, 0)
            CFrameMon = CFrame.novo(-7624.25244140625, 5658.13330078125, -1467.354248046875)
        elseif MeuNível == 550 ou MeuNível <= 624 então
            Mon = "Soldado Real"
            LevelQuest = 2
            NomeQuest = "SkyExp2Quest"
            NomeMon = "Soldado Real"
            CFrameQuest = CFrame.new(-7906.81592, 5634.6626, -1411.99194, 0, 0, -1, 0, 1, 0, 1, 0, 0)
            CFrameMon = CFrame.novo(-7836.75341796875, 5645.6640625, -1790.6236572265625)
        elseif MeuNível == 625 ou MeuNível <= 649 então
            Seg = "Pirata da Galera"
            LevelQuest = 1
            NameQuest = "Quest da Fonte"
            NomeMon = "Pirata da Galera"
            CFrameQuest = CFrame.new(5259.81982, 37.3500175, 4050.0293, 0.087131381, 0, 0.996196866, 0, 1, 0, -0.996196866, 0, 0.087131381)
            CFrameMon = CFrame.new(5551.02197265625, 78.90135192871094, 3930.412841796875)
        elseif MeuNível >= 650 então
            Seg = "Capitão de cozinha"
            LevelQuest = 2
            NameQuest = "Quest da Fonte"
            NomeMon = "Capitão da Galera"
            CFrameQuest = CFrame.new(5259.81982, 37.3500175, 4050.0293, 0.087131381, 0, 0.996196866, 0, 1, 0, -0.996196866, 0, 0.087131381)
            CFrameMon = CFrame.new(5441.95166015625, 42.50205993652344, 4950.09375)
        fim
    senão se World2 então
        se MyLevel == 700 ou MyLevel <= 724 então
            Seg = "Invasor"
            LevelQuest = 1
            NomeQuest = "Area1Quest"
            NomeMon = "Raider"
            CFrameQuest = CFrame.new(-429,543518, 71,7699966, 1836,18188, -0,22495985, 0, -0,974368095, 0, 1, 0, 0,974368095, 0, -0,22495985)
            CFrameMon = CFrame.new(-728.3267211914062, 52.779319763183594, 2345.7705078125)
        elseif MeuNível == 725 ou MeuNível <= 774 então
            Seg = "Mercenário"
            LevelQuest = 2
            NomeQuest = "Area1Quest"
            NomeMon = "Mercenário"
            CFrameQuest = CFrame.new(-429,543518, 71,7699966, 1836,18188, -0,22495985, 0, -0,974368095, 0, 1, 0, 0,974368095, 0, -0,22495985)
            CFrameMon = CFrame.new(-1004.3244018554688, 80.15886688232422, 1424.619384765625)
        elseif MeuNível == 775 ou MeuNível <= 799 então
            Seg = "Pirata Cisne"
            LevelQuest = 1
            NomeQuest = "Area2Quest"
            NomeMon = "Pirata Cisne"
            CFrameQuest = CFrame.new(638,43811, 71,769989, 918,282898, 0,139203906, 0, 0,99026376, 0, 1, 0, -0,99026376, 0, 0,139203906)
            CFrameMon = CFrame.new(1068.664306640625, 137.61428833007812, 1322.1060791015625)
        elseif MeuNível == 800 ou MeuNível <= 874 então
            Seg = "Equipe da Fábrica"
            NomeQuest = "Area2Quest"
            LevelQuest = 2
            NameMon = "Equipe da Fábrica"
            CFrameQuest = CFrame.new(632,698608, 73,1055908, 918,666321, -0,0319722369, 8,96074881e-10, -0,999488771, 1,36326533e-10, 1, 8,92172336e-10, 0,999488771, -1,07732087e-10, -0,0319722369)
            CFrameMon = CFrame.new(73.07867431640625, 81.86344146728516, -27.470672607421875)
        elseif MeuNível == 875 ou MeuNível <= 899 então
            Mon = "Tenente da Marinha"
            LevelQuest = 1
            NomeQuest = "MarineQuest3"
            NomeMon = "Tenente da Marinha"
            CFrameQuest = CFrame.new(-2440,79639, 71,7140732, -3216,06812, 0,866007268, 0, 0,500031412, 0, 1, 0, -0,500031412, 0, 0,866007268)
            CFrameMon = CFrame.new(-2821.372314453125, 75.89727783203125, -3070.089111328125)
        elseif MeuNível == 900 ou MeuNível <= 949 então
            Mon = "Capitão da Marinha"
            LevelQuest = 2
            NomeQuest = "MarineQuest3"
            NomeMon = "Capitão da Marinha"
            CFrameQuest = CFrame.new(-2440,79639, 71,7140732, -3216,06812, 0,866007268, 0, 0,500031412, 0, 1, 0, -0,500031412, 0, 0,866007268)
            CFrameMon = CFrame.novo(-1861.2310791015625, 80.17658233642578, -3254.697509765625)
        elseif MeuNível == 950 ou MeuNível <= 974 então
            Seg = "Zumbi"
            LevelQuest = 1
            NomeQuest = "ZombieQuest"
            NomeMon = "Zumbi"
            CFrameQuest = CFrame.new(-5497,06152, 47,5923004, -795,237061, -0,29242146, 0, -0,95628953, 0, 1, 0, 0,95628953, 0, -0,29242146)
            CFrameMon = CFrame.new(-5657.77685546875, 78.96973419189453, -928.68701171875)
        elseif MeuNível == 975 ou MeuNível <= 999 então
            Seg = "Vampiro"
            LevelQuest = 2
            NomeQuest = "ZombieQuest"
            NomeMon = "Vampiro"
            CFrameQuest = CFrame.new(-5497,06152, 47,5923004, -795,237061, -0,29242146, 0, -0,95628953, 0, 1, 0, 0,95628953, 0, -0,29242146)
            CFrameMon = CFrame.new(-6037.66796875, 32.18463897705078, -1340.6597900390625)
        elseif MeuNível == 1000 ou MeuNível <= 1049 então
            Seg = "Soldado da Neve"
            LevelQuest = 1
            NomeQuest = "SnowMountainQuest"
            NomeMon = "Soldado da Neve"
            CFrameQuest = CFrame.new(609,858826, 400,119904, -5372,25928, -0,374604106, 0, 0,92718488, 0, 1, 0, -0,92718488, 0, -0,374604106)
            CFrameMon = CFrame.new(549.1473388671875, 427.3870544433594, -5563.69873046875)
        caso contrário, se MyLevel == 1050 ou MyLevel <= 1099, então
            Seg = "Guerreiro do Inverno"
            LevelQuest = 2
            NomeQuest = "SnowMountainQuest"
            NomeMon = "Guerreiro do Inverno"
            CFrameQuest = CFrame.new(609,858826, 400,119904, -5372,25928, -0,374604106, 0, 0,92718488, 0, 1, 0, -0,92718488, 0, -0,374604106)
            CFrameMon = CFrame.new(1142.7451171875, 475.6398010253906, -5199.41650390625)
        elseif MeuNível == 1100 ou MeuNível <= 1124 então
            Seg = "Subordinado de Laboratório"
            LevelQuest = 1
            NomeQuest = "IceSideQuest"
            NameMon = "Subordinado de laboratório"
            CFrameQuest = CFrame.new(-6064.06885, 15.2422857, -4902.97852, 0.453972578, -0, -0.891015649, 0, 1, -0, 0.891015649, 0, 0.453972578)
            CFrameMon = CFrame.novo(-5707.4716796875, 15.951709747314453, -4513.39208984375)
        elseif MeuNível == 1125 ou MeuNível <= 1174 então
            Mon = "Guerreiro com Chifres"
            LevelQuest = 2
            NomeQuest = "IceSideQuest"
            NomeMon = "Guerreiro Chifrudo"
            CFrameQuest = CFrame.new(-6064.06885, 15.2422857, -4902.97852, 0.453972578, -0, -0.891015649, 0, 1, -0, 0.891015649, 0, 0.453972578)
            CFrameMon = CFrame.novo(-6341.36669921875, 15.951770782470703, -5723.162109375)
        elseif MeuNível == 1175 ou MeuNível <= 1199 então
            Seg = "Magma Ninja"
            LevelQuest = 1
            NomeQuest = "FireSideQuest"
            NomeMon = "Magma Ninja"
            CFrameQuest = CFrame.new(-5428,03174, 15,0622921, -5299,43457, -0,882952213, 0, 0,469463557, 0, 1, 0, -0,469463557, 0, -0,882952213)
            CFrameMon = CFrame.new(-5449.6728515625, 76.65874481201172, -5808.20068359375)
        elseif MeuNível == 1200 ou MeuNível <= 1249 então
            Seg = "Pirata da Lava"
            LevelQuest = 2
            NomeQuest = "FireSideQuest"
            NomeMon = "Pirata da Lava"
            CFrameQuest = CFrame.new(-5428,03174, 15,0622921, -5299,43457, -0,882952213, 0, 0,469463557, 0, 1, 0, -0,469463557, 0, -0,882952213)
            CFrameMon = CFrame.novo(-5213.33154296875, 49.73788070678711, -4701.451171875)
        elseif MeuNível == 1250 ou MeuNível <= 1274 então
            Mon = "Marinheiro de convés do navio"
            LevelQuest = 1
            NomeQuest = "ShipQuest1"
            NomeMon = "Marinheiro do Navio"
            CFrameQuest = CFrame.new(1037.80127, 125.092171, 32911.6016)         
            CFrameMon = CFrame.new(1212.0111083984375, 150.79205322265625, 33059.24609375)    
            se _G.AutoFarm e (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 10000 então
                jogo:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(923.21252441406, 126.9760055542, 32852.83203125))
            fim
        elseif MeuNível == 1275 ou MeuNível <= 1299 então
            Mon = "Engenheiro de Navio"
            LevelQuest = 2
            NomeQuest = "ShipQuest1"
            NomeMon = "Engenheiro de Navio"
            CFrameQuest = CFrame.new(1037.80127, 125.092171, 32911.6016)   
            CFrameMon = CFrame.new(919.4786376953125, 43.54401397705078, 32779.96875)   
            se _G.AutoFarm e (CFrameQuest.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude > 10000 então
                jogo:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("reque
