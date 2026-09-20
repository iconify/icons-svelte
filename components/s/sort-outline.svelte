<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hcxv4abex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hcxv4abex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:sort-outline" {...props}></Icon>
