<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqrvfl7vl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wqrvfl7vl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:stoned-skull" {...props}></Icon>
