## テキスト出力

Hello Worldと出してみる

* https://photonstorm.github.io/phaser3-docs/Phaser.GameObjects.Text.html#Text

<script type="module">

const config = {
	type: Phaser.AUTO,
	width: 800,
	height: 600,
	physics: {
		default: "arcade",
		arcade: {
			debug: true
		}
	},
	scene: {
		preload: preload,
		create: create,
		update: update
	}
};

const game = new Phaser.Game(config);

function preload()
{
}

function create()
{
	const text = this.add.text(10, 10, "Hello World");
}

function update()
{
}

</script>
