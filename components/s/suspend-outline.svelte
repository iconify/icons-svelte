<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nyozvw1iu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nyozvw1iu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:suspend-outline" {...props}></Icon>
