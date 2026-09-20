<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aoqnfibbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aoqnfibbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:video-game-pacman" {...props}></Icon>
