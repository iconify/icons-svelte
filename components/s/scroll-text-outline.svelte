<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmh5xvb-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mmh5xvb-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:scroll-text-outline" {...props}></Icon>
