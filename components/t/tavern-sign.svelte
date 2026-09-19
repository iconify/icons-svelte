<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezzt3p5xl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ezzt3p5xl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tavern-sign" {...props}></Icon>
