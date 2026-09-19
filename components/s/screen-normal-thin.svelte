<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1x9vb-ma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s1x9vb-ma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:screen-normal-thin" {...props}></Icon>
