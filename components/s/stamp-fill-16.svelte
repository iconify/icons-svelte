<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xuo324tmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xuo324tmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:stamp-fill-16" {...props}></Icon>
