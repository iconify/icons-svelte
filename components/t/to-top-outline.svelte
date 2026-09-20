<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pf2nnx-8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pf2nnx-8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:to-top-outline" {...props}></Icon>
