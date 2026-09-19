<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/low_q9xkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="low_q9xkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:three-slashes" {...props}></Icon>
