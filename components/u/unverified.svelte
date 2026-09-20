<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azxr97--q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="azxr97--q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:unverified" {...props}></Icon>
