<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xcswd5b4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="xcswd5b4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:snow-shower-day" {...props}></Icon>
