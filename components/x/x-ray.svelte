<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sflgbubsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sflgbubsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:x-ray" {...props}></Icon>
