package ch.zhaw.iwi.devops.gameoflife;

public class GameofLife {

    public boolean step(boolean currentstate, int nneighbors) {
        if (currentstate && nneighbors < 2) {
            return false;
        } else if (currentstate && 
                    (nneighbors == 2 || nneighbors == 3)) {
            return true;
        } else if (currentstate && nneighbors  > 3) {
            return false;
        } else if (!currentstate  && nneighbors == 3){
           return true;
        }
        
        return currentstate;
    }

}
