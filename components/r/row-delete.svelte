<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0119acpd.css';
import '../../css/c/cj-ip0b4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="r0119acpd"/><path class="cj-ip0b4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:row-delete" {...props}></Icon>
