<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hyxx4tb5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hyxx4tb5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:temperature-increase" {...props}></Icon>
