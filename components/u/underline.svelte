<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rq1njibny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="rq1njibny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:underline" {...props}></Icon>
