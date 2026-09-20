<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_d0fh6vs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l_d0fh6vs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:syringe-off" {...props}></Icon>
