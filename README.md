// Listen for the "P" key press
document.addEventListener('keydown', function(event) {
    if (event.key === 'p' || event.key === 'P') {
        // Toggle flight mode
        const player = game.getSurvivalPlayers()[0]; // Get the player object
        player.setCanFly(!player.canFly()); // Toggle flight mode
    }
});
