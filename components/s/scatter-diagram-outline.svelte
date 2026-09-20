<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gv7b53xgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gv7b53xgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:scatter-diagram-outline" {...props}></Icon>
