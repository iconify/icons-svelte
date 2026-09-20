<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvobarqgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wvobarqgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:search-zoom-out2-filled" {...props}></Icon>
