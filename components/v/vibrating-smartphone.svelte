<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfoy-fbzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yfoy-fbzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:vibrating-smartphone" {...props}></Icon>
