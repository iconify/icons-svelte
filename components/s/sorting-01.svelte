<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxwub093w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sxwub093w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:sorting-01" {...props}></Icon>
