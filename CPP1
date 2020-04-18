#CHECK_POINT-PYTHON

print ("\033[1;35m------------------------------------------------------------------------------------------------------------ ")
print ('''  __        ________   ______   __    __         ______   ________   ______   _______    ______   __    __ 
/  |      /        | /      \ /  |  /  |       /      \ /        | /      \ /       \  /      \ /  |  /  |
$$ |      $$$$$$$$/ /$$$$$$  |$$ | /$$/       /$$$$$$  |$$$$$$$$/ /$$$$$$  |$$$$$$$  |/$$$$$$  |$$ |  $$ |
$$ |      $$ |__    $$ |__$$ |$$ |/$$/        $$ \__$$/ $$ |__    $$ |__$$ |$$ |__$$ |$$ |  $$/ $$ |__$$ |
$$ |      $$    |   $$    $$ |$$  $$<         $$      \ $$    |   $$    $$ |$$    $$< $$ |      $$    $$ |
$$ |      $$$$$/    $$$$$$$$ |$$$$$  \         $$$$$$  |$$$$$/    $$$$$$$$ |$$$$$$$  |$$ |   __ $$$$$$$$ |
$$ |_____ $$ |_____ $$ |  $$ |$$ |$$  \       /  \__$$ |$$ |_____ $$ |  $$ |$$ |  $$ |$$ \__/  |$$ |  $$ |
$$       |$$       |$$ |  $$ |$$ | $$  |      $$    $$/ $$       |$$ |  $$ |$$ |  $$ |$$    $$/ $$ |  $$ |
$$$$$$$$/ $$$$$$$$/ $$/   $$/ $$/   $$/        $$$$$$/  $$$$$$$$/ $$/   $$/ $$/   $$/  $$$$$$/  $$/   $$/ 
                                                                                                           ''' )

print ("------------------------------------------------------------------------------------------------------------\033[m")
print ("O LEAK SEARCH é de forma simplificada uma base de dados com os vazamentos mais atualizados onde o usuário pode pesquisar se suas informações estão circulando onde não deveriam.")
print ("Para utilizar o LEAK SEARCH basta selecionas uma de suas 5 possíveis pesquisas, e digitar com a pontuação correta seu item!")

import getpass
import time

#Base de dados vazados
num_cpf = ["440.550.768-60", "817.223.028-10", "675.241.758-09", "504.175.618-06", "135.311.098-20", "554.632.358-21", "804.360.018-02", "611.588.148-01", "762.959.898-02", "619.230.528-53", "141.894.668-08", "409.891.198-15", "207.606.368-42", "744.689.418-04", "649.945.378-10", "110.099.928-05", "289.826.148-34", "732.287.698-95", "722.785.478-79", "975.913.498-56", "563.308.908-11", "541.743.968-17", "892.899.278-87", "072.095.658-76", "886.523.838-04"]
num_rg = ["36.346.882-1", "14.601.155-7", "32.784.305-6", "11.769.500-2", "50.065.695-2", "47.861.220-5", "23.498.338-3", "46.303.259-7", "48.905.338-5", "36.862.455-9", "49.496.091-7", "28.377.755-2", "50.392.960-8", "36.731.703-5", "16.228.091-9", "23.731.255-4", "17.332.568-3", "22.788.515-6", "43.930.848-3", "50.202.073-8", "49.021.795-3"]
num_cep = ["07851-071", "03702-000", "05521-201", "12446-250", "13340-152", "18705-023", "18076-050", "02022-0350", "04533-011", "09122-055", "13214-867", "04509-903", "12930-970", "13903-442", "13088-012", "12225-852", "15991-422", "13309-340", "07862-080", "16056-873", "07434-313", "13213-080", "08253-420", "03165-000", "01126-030", "16012-527", "12041-016", "06807-000", "14031-480", "13273-275", "07131-340"]
senhas = ["VicsheRsus", "VanVictorious", "@45Plego", "@chenko", "laranjaq31", "asdad2", "abc1212", "alberico_lindos2s2", "me_da_nota_boa", "Zeucursed", "alvocaos9090", "hackserkk1", "time-for-space2232", "enzo-eidy", "deeperinside212", "feccer", "kkjdASDSff2"]
num_title_eleitor = ["377104770191", "513862270175", "408167480132", "417048650132", "226454500191", "842243620132", "645723720108", "335343760175", "205457750140", "136818150132", "078625000191", "147520150108", "644758520108", "080640430159", "281276770132", "154523800116", "234223660191", "285438270116", "750586100191"]
opcao = int


while opcao != 6:
    print('''             [1] Pesquisar CPF
             [2] Pesquisar RG
             [3] Pesquisar CEP
             [4] Pesquisar Senha
             [5] Pesquisar Título de Eleitor
             [6] Finalizar pesquisa''')
    opcao = int(input("Digite a opção que deve ser pesquisada: "))
    
        ###### Verificador de CPF #############
    
    if opcao == 1:
        num_cpf_vazamento = (input("Digite o item a ser pesquisado na lista de vazamentos: "))
        for x in num_cpf:
            if x == num_cpf_vazamento:
                print("\033[1;31mO número de cpf {} foi vazado!\033[m".format(num_cpf_vazamento))
                break
        else:
            print("\033[1;32mO número de cpf {} está seguro!\033[m".format(num_cpf_vazamento))
        time.sleep(2)
        resposta = (input('''Deseja realizar uma nova pesquisa?
        [1] Sim!
        [2] Não!
        '''))
        if resposta == "1":
            print("Realizando sua nova pesquisa...")
            time.sleep(2)                    
        else:
            print("Obrigado por utilizar o \033[;1m\033[1;35mLEAK SEARCH!\033[m")
            time.sleep(2)
            exit()
        
        ####### Verificador de RG ##############            
    
    elif opcao == 2:
        num_rg_vazamento = (input("Digite o RG que deve ser analisado: "))
        for y in num_rg:
            if y == num_rg_vazamento:
                print("\033[1;31mO número de RG {} foi vazado!\033[m".format(num_rg_vazamento))
                break
        else:
            print("\033[1;32mO número de RG {} está seguro!\033[m".format(num_rg_vazamento))
        time.sleep(2)
        resposta = (input('''Deseja realizar uma nova pesquisa?
        [1] Sim!
        [2] Não!
        '''))
        if resposta == "1":
            print("Realizando uma nova pesquisa...")
            time.sleep(2)                    
        else:
            print("Obrigado por utilizar o \033[;1m\033[1;35mLEAK SEARCH!\033[m")
            time.sleep(2)
            exit()
        
        
        ###### Verificador de CEP ###############

    elif opcao == 3:
        num_cep_vazamento = (input("Digite o CEP que deve ser analisado: "))
        for z in num_cep:
            if z in num_cep_vazamento:
                print("\033[1;31mO número de CEP {} foi vazado!\033[m".format(num_cep_vazamento))
                break
        else:
            print("\033[1;32mO número de CEP {} está seguro!\033[m".format(num_cep_vazamento))
        time.sleep(2)
        resposta = (input('''Deseja realizar uma nova pesquisa?
        [1] Sim!
        [2] Não!
        '''))
        if resposta == "1":
            print("Realizando uma nova pesquisa...")
            time.sleep(2)                    
        else:
            print("Obrigado por utilizar o \033[;1m\033[1;35mLEAK SEARCH!\033[m")
            time.sleep(2)
            exit()

        ###### Verificador de senhas ##############
    
    elif opcao == 4:
        senha_vazamento = getpass.getpass("Digite a senha que deve ser analisada: ")
        for a in senhas:
            if a in senha_vazamento:
                print("\033[1;31mEstá senha foi vazada! Troque o mais rápido possível!\033[m")
                break
        else:
            print("\033[1;32mEsta senha está segura!\033[m")
        time.sleep(2)
        resposta = (input('''Deseja realizar uma nova pesquisa?
        [1] Sim!
        [2] Não!
        '''))
        if resposta == "1":
            print("Realizando uma nova pesquisa...")
            time.sleep(2)                    
        else:
            print("Obrigado por utilizar o \033[;1m\033[1;35mLEAK SEARCH!\033[m")
            time.sleep(2)
            exit()

        ###### Verificador de titulo de eleitor ########

    elif opcao == 5:
        title_eleitor_vazamento = (input("Digite o título de eleitor que deve ser analisado: "))
        for b in num_title_eleitor:
            if b in title_eleitor_vazamento:
                print("\033[1;31mO número de título de eleitor {} foi vazado!\033[m".format(num_title_eleitor))
                break
        else:
            print("\033[1;32mO número de  título de eleitor {} está seguro!\033[m".format(num_title_eleitor))
        time.sleep(2)
        resposta = (input('''Deseja realizar uma nova pesquisa?
        [1] Sim!
        [2] Não!
        '''))
        if resposta == "1":
            print("Realizando uma nova pesquisa...")
            time.sleep(2)                    
        else:
            print("Obrigado por utilizar o \033[;1m\033[1;35mLEAK SEARCH!\033[m")
            time.sleep(2)
            exit()

        ###### Opção para finalizar o programa ##########
    
    elif opcao == 6:
        print ("Obrigado por utilizar o \033[;1m\033[1;35mLEAK SEARCH!\033[m")
        time.sleep(2)
        exit()
    
        ###### Caso a opção não esteja dentre as possíveis ########

    elif opcao != 6:
        print("A opção selecionada é inválida, tente novamente!")
        time.sleep(2)

else:
    print("Obrigado por usar o LEAK SEARCH!")


            
        
    
