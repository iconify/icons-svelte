<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4yt2wozj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="u4yt2wozj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:vest" {...props}></Icon>
