<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6lbg1bym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="p6lbg1bym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:surface-left-outline" {...props}></Icon>
