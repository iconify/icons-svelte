<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrrlo7kat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yrrlo7kat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:topaz" {...props}></Icon>
