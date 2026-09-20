<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjrt05b4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pjrt05b4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:umbrella-outline" {...props}></Icon>
