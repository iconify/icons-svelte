<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e76d37bpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="e76d37bpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:subway" {...props}></Icon>
