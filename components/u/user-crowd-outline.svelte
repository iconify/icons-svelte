<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0-k8xb8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="z0-k8xb8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:user-crowd-outline" {...props}></Icon>
