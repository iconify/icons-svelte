<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udfo3xbfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="udfo3xbfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:wifi-low-gloss" {...props}></Icon>
