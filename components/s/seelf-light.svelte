<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckfic-b8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ckfic-b8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:seelf-light" {...props}></Icon>
