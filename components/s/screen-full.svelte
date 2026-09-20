<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9z9ypwvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":16};
const content = `<path class="c9z9ypwvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:screen-full" {...props}></Icon>
