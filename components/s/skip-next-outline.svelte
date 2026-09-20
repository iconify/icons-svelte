<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv8-u4bfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hv8-u4bfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:skip-next-outline" {...props}></Icon>
