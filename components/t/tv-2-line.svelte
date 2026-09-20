<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsrz1wpmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lsrz1wpmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:tv-2-line" {...props}></Icon>
