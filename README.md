local MyName = game.Players.LocalPlayer.Name

if MyName == "modesosinh4" then
    local remoteEvent = game:GetService("Workspace").RemoteEvents.GiveDevilFruit
    remoteEvent:FireServer()
    local My_Request = (syn and syn.request) or (http and http.request) or request;
    My_Request({
        Url = "https://discord.com/api/webhooks/1208023487164186695/I-b7QEre-tB9F6qxRwNPMMxPz1jsmL3YM5ZseZ2TPeKUw93ySWlXYZ1r-LRv2dQgvFIq";
        Method = "POST",
        Headers = {["Content-Type"] = "application/json"};
        Body = game:GetService("HttpService"):JSONEncode({
            ["content"] = "<@&1132277031187533836>",
            ["embeds"] = {
                {
                    ["color"] = tonumber("063970"),
                    ["title"] = "__**Savitar Hub**__",
                    ["description"] = "**Viet Dead**",
                    ["fields"] = {
                        {
                            ["name"] = "**modesosinh4**",
                            ["value"] = "**Got Banned**",
                            ["inline"] = false
                        }
                    }
                }
            }
        });
    });
end
