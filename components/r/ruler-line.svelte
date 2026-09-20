<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dttdt_m9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dttdt_m9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:ruler-line" {...props}></Icon>
