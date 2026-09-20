<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrw4lrb7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rrw4lrb7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:stairs-descend-bold" {...props}></Icon>
