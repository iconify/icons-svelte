<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9yzp1ixx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l9yzp1ixx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:trilium-notes-light" {...props}></Icon>
