<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vsfqp5b1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="vsfqp5b1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:s-q-l-analytics-pool" {...props}></Icon>
