<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqsxe_m5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="vqsxe_m5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:scribd" {...props}></Icon>
