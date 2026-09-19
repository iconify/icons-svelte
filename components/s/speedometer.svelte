<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v32xtabhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v32xtabhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:speedometer" {...props}></Icon>
