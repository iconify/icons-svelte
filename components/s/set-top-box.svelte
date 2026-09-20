<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_2i0ippj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g_2i0ippj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:set-top-box" {...props}></Icon>
