<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j51pobcsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j51pobcsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:weight-lifting-down" {...props}></Icon>
