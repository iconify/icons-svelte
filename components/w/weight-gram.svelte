<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tj85o5bsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tj85o5bsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:weight-gram" {...props}></Icon>
