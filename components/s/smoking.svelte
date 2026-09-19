<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-ms6bclb.css';
import '../../css/h/hx5u2eb2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="x-ms6bclb"/><path class="hx5u2eb2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:smoking" {...props}></Icon>
