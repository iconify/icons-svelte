<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvzl_-vef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uvzl_-vef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:shuttlecock" {...props}></Icon>
