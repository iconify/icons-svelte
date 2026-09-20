<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhqb61bvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yhqb61bvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:word-cloud-outline" {...props}></Icon>
