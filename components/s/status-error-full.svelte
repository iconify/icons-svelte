<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvt4wtb1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="kvt4wtb1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:status-error-full" {...props}></Icon>
