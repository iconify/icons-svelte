<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtt32ccdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jtt32ccdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:sort-asc" {...props}></Icon>
