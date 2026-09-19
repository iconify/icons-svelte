<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/taasc_mln.css';
import '../../css/e/eu8t76b8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="taasc_mln"/><path class="eu8t76b8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:zoom-fit" {...props}></Icon>
