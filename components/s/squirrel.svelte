<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zt8eu321u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zt8eu321u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:squirrel" {...props}></Icon>
