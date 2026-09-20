<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcezmhb2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vcezmhb2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:triangle-warning-outline" {...props}></Icon>
