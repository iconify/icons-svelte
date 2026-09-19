<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfm9clb8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sfm9clb8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:zig" {...props}></Icon>
