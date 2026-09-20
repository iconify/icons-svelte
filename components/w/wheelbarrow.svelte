<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9qzhvb_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="u9qzhvb_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:wheelbarrow" {...props}></Icon>
