<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rn37jywxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rn37jywxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:torpedo" {...props}></Icon>
