<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qnfpi3hic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="qnfpi3hic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:tiles-2" {...props}></Icon>
