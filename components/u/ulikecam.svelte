<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nd9390eio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nd9390eio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:ulikecam" {...props}></Icon>
