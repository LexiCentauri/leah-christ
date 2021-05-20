local x,y = term.getSize()
while true do
    local num = math.random(3,x)
    for i=1,num do
        local colBit = 1
        local colNum = math.random(0,14)
        colBit = bit.blshift(colBit,colNum)
        term.setTextColor(colBit)
        write("A")
    end
    sleep(0.01)
    print("")
end