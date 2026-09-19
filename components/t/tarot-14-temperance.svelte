<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0_00t29z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f0_00t29z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tarot-14-temperance" {...props}></Icon>
