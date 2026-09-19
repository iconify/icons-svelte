<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6m48cbdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b6m48cbdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:spoted-flower" {...props}></Icon>
