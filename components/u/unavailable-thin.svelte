<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6qgw_b9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a6qgw_b9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:unavailable-thin" {...props}></Icon>
