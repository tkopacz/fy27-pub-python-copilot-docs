1. Sklonować:

   1. Dokumentacje lab: git clone https://github.com/tkopacz/fy27-pub-python-copilot-docs
   2. Kod: git clone https://github.com/tkopacz/fy27-pub-python-copilot-code

2. Przejrzeć przed warsztatem: https://github.com/tkopacz/fy27-pub-python-copilot-docs/blob/main/lab.md (lub pdf)

3. Upewnić się że są zainstalowane:

   1. (Licencja na Github Copilot)
   2. Visual Studio Code z zalogowanym Copilot - https://code.visualstudio.com/download. Testowane na 1.141.0 (User Setup). Zalogowanie można sprawdzić tu:
      <img src="Z:\Copilot-2026-Workshop\fy27-pub-python-copilot\assets\image-20261011143651953.png" alt="image-20261011143651953" style="zoom:50%;" />
   3. Github Copilot CLI - https://docs.github.com/en/copilot/how-tos/copilot-cli/set-up-copilot-cli/install-copilot-cli . Testowane na GitHub Copilot CLI 1.0.95.
      Jeżeli Github Copilot CLI   jest już zainstalowany - proszę go zaktualizować (wystarczy po uruchomieniu CLI uruchomić `/restart`).
      Upewnić się że jest zalogowanym - jak nie - wykonać `/login`

4. Na wszelki wypadek - w folderze ze sklonowanym kodem uruchomić w Powershell:
   `.\scripts\Setup.ps1 -WithLLM`

   `.\scripts\test.ps1` (jeden błąd - TO JEST OK!)

   `.\scripts\evaluate.ps1 -Mode demo -Output reports\baseline-demo.json`

   (jeżeli się uruchomią - wszystko gotowe)

5. Jeżeli się chce - można globalnie zainstalować Speckit: https://speckit.org/ (polecam)

   1. Jak nie - zainstalowany będzie lokalnie pip-em później / w ramach pracy domowej
   2. Rozszerzenie do Brownfield (https://speckit-community.github.io/extensions/brownfield) będzie zainstalowane później