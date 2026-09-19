<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6-ntejpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="p6-ntejpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:square-viadeo" {...props}></Icon>
