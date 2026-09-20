<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xs99e4b_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xs99e4b_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:setting-search-outline" {...props}></Icon>
