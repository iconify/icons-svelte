<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-cp04bhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u-cp04bhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:wyvern" {...props}></Icon>
