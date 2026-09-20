<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dl5jfab4x.css';
import '../../css/z/z_xj5lr8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dl5jfab4x"/><path class="z_xj5lr8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:water-manhole" {...props}></Icon>
