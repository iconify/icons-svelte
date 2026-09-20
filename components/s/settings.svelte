<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqtq7ab2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="aqtq7ab2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:settings" {...props}></Icon>
