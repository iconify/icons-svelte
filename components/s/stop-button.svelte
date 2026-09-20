<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-f53ebvb.css';
import '../../css/r/r8o5bwx5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<rect class="z-f53ebvb"/><path class="r8o5bwx5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:stop-button" {...props}></Icon>
