<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csed-1b0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="csed-1b0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:tasks-open" {...props}></Icon>
