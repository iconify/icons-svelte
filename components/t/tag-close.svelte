<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpxc1bcpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":384};
const content = `<path class="rpxc1bcpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:tag-close" {...props}></Icon>
