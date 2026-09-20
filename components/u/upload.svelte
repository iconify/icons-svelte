<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5-g-233d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h5-g-233d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:upload" {...props}></Icon>
