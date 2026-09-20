<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ucqn0pb6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ucqn0pb6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:video-game-tetris" {...props}></Icon>
