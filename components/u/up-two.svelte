<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idb_0ybwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="idb_0ybwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:up-two" {...props}></Icon>
