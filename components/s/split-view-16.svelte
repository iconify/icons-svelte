<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bk3h7-bti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bk3h7-bti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:split-view-16" {...props}></Icon>
