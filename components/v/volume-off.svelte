<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jj70ugbpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jj70ugbpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:volume-off" {...props}></Icon>
