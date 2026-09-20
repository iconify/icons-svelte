<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqdic25tv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vqdic25tv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:search-outline" {...props}></Icon>
