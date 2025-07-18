# SA Course Self-Study Log

<table>
  <thead>
    <tr>
      <th>Date</th>
      <th>Progress & Topic</th>
      <th>HackMD Link</th>
      <th style="width: 80%;">Thoughts & Issues</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>2025-07-10</td>
      <td>
        <ol>
          <li>Build up connection to NYCU workstation</li>
          <li>Studied "vim" command (<code>vimtutor</code>)</li>
          <li>Practice <a href="https://cs.nycu.edu.tw/~unix/basic-commands">unix basic command </li>
        </ol>
      </td>
      <td>
        <ol>
          <li><a href="https://hackmd.io/UhlqyrsbRDuQil3DDhtW0g">Unix 指令</li>
          <li><a href="https://hackmd.io/XbgWnIVKTAqq-djge6OCgA">vimtutor</li>
        </ol>
      </td>
      <td>
        之前就有學過一點點 vim 的指令。現在更全面性地整理與學習覺得更加上手了☺️<br><br>
      </td>
    </tr>
    <tr>
      <td>2025-07-11</td>
      <td>
        <ol>
          <li>Install <a href="https://nasa.cs.nycu.edu.tw/sa/2024/slides/01_Install_FreeBSD.pdf">FreeBSD on VirtualBox</li>
          <li>Finished the instructions in <a href="https://nasa.cs.nycu.edu.tw/sa/2024/slides/hw1.pdf">HW1</li>
        </ol>
      </td>
      <td>
        <ol>
          <a href="https://hackmd.io/UhlqyrsbRDuQil3DDhtW0g">Install FreeBSD using VirtualBox</li>
        </ol>
      </td>
      <td>
        <ol>
          <li>安裝 FreeBSD 時即使成功利用 UEFI 啟動但一直沒辦法成功安裝，嘗試了比較舊的 Release 與 VirtualBox 版本、嘗試改成替代選項 Ubuntu 都沒辦法成功。最後發現是因為我下載的 iso 檔與我的電腦本機作業系統架構不相容。具體來說，我的電腦是 Apple 的 M2 晶片 (ARM64 架構)，但我下載的 iso 檔是 amd64，專門設計給 Intel/AMD 的電腦 (x86-64 架構)。原本想的是使用 VirtualBox 一樣可以相容，後來想到虛擬機硬體等設定還是依賴本機，必定會有影響。之後下載 arm64 架構的 iso 檔就順利安裝 FreeBSD 了！</li>
          <li>作業中要求建立指定名稱的使用者與群組，在建立群組時取錯名字，後來用修改明字的指令輸入錯誤，導致產生了兩個群組 (一個正確名稱、一個錯誤名稱的群組)，之後查詢如何將群組刪除並下達正確指令，最後也成功將錯誤名稱的群組刪除，並順利將使用者加入我創建的群組中。🥹</li>
        </ol>
      </td>
    </tr>
    <tr>
      <td>2025-07-16</td>
      <td>
        <ol>
          <li>Study View of Disk</li>
          <li>Review Operating System: File System</li>
        </ol>
      </td>
      <td>
        <ol>
          <li><a href="https://hackmd.io/@JCH/BJF6-kULge">底層磁碟分區</li>
          <li><a href="https://hackmd.io/UhlqyrsbRDuQil3DDhtW0g](https://hackmd.io/fIlGLmSVRbewJuD7RrZ8Wg">File System and Virtual File System</li>
        </ol>
      </td>
      <td>
        <ol>
          藉由這個機會深入認識磁碟分區並複習之前學過的檔案系統的概念覺得很棒！
        </ol>
      </td>
    </tr>
    <tr>
      <td>2025-07-17</td>
      <td>
        <ol>
          <li>Study Firmware and Storage Framework</li>
          <li>Review Operating System: Virtual File System</li>
        </ol>
      </td>
      <td>
        <ol>
          <li><a href="https://hackmd.io/@JCH/r1muxZIIgl">韌體與儲存框架</li>
          <li><a href="https://hackmd.io/@JCH/SkdFQrSLee">File System and Virtual File System</li>
        </ol>
      </td>
      <td>
        <ol>
          過去學習作業系統只有大致了解整體架構，現在更深入的藉由實例了解他們之間的互動關係。
        </ol>
      </td>
    </tr>
    <tr>
      <td>2025-07-18</td>
      <td>
        <ol>
          <li>Review tmux and Git</li>
          <li>Review Operating System: Process</li>
        </ol>
      </td>
      <td>
        <ol>
          <li><a href="https://hackmd.io/@JCH/rkPf_Yw8ge">tmux</li>
          <li><a href="https://hackmd.io/@JCH/HyCtyAw8gx">Git three stages and file lifecycle</li>
          <li><a href="https://hackmd.io/@JCH/S1AHX6DUlx">Process</li>
        </ol>
      </td>
      <td>
        <ol>
          之前使用 tmux 跟 git 比較偏向會使用指令但不太了解為什麼能夠做到斷線後仍能恢復原本的工作與版本控制，這次學習補足了之前沒學到的部分！
        </ol>
      </td>
    </tr>
    </tbody>
</table>
