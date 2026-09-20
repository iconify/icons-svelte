<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfuom7_gb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tfuom7_gb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:texture" {...props}></Icon>
