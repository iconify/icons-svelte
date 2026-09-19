<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxuje6u-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nxuje6u-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:vr" {...props}></Icon>
