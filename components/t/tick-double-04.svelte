<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cp5zf1d7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cp5zf1d7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:tick-double-04" {...props}></Icon>
