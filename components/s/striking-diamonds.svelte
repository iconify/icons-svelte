<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yzjtm5bom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yzjtm5bom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:striking-diamonds" {...props}></Icon>
