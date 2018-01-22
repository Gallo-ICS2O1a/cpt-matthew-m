def setup():
    size(400, 600)
    background(204, 102, 0)


def draw():
    line(125, 50, 125, 350)
    line(280, 50, 280, 350)
    line(370, 130, 30, 130)
    line(370, 260, 30, 260)

    textSize(32)
    text("Instructions:", 100, 420)
    fill(0, 102, 153)
    text("Left click for ellipse", 60, 450)
    fill(0, 102, 153, 51)
    text("Right click for rectangle", 20, 480)
    fill(0, 102, 153)
    text("You need 2 players", 65, 530)
    fill(0, 102, 153)
    text("When game is over", 65, 560)
    fill(0, 102, 153)
    text("re-run the program", 65, 590)


def mousePressed():

    if mouseButton == LEFT:
        b = True
        fill(18, 657, 754)
        ellipse(pmouseX, pmouseY, 40, 40)
    elif mouseButton == RIGHT:
        b = False
        fill(300, 60, 78)
        rect(pmouseX, pmouseY, 40, 40)
