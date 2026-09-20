<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmib2_bat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fmib2_bat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tournament" {...props}></Icon>
