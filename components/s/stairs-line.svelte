<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrq970bog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nrq970bog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:stairs-line" {...props}></Icon>
