<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvhi8qybv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pvhi8qybv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:three-friends" {...props}></Icon>
