<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xq5_v9auw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="xq5_v9auw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:status-circle-ring" {...props}></Icon>
