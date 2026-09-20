<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ka1cq2b8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ka1cq2b8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:top-align-outline" {...props}></Icon>
