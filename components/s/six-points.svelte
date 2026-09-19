<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cb9hdq23h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cb9hdq23h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:six-points" {...props}></Icon>
