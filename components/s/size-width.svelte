<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pye6s3a0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pye6s3a0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:size-width" {...props}></Icon>
