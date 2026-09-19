<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dha5zw5kn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dha5zw5kn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:waterfalls-v" {...props}></Icon>
