<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsg-1ghgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lsg-1ghgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:surface-top-outline" {...props}></Icon>
