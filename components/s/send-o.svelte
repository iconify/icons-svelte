<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hicvn82qc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1824};
const content = `<path class="hicvn82qc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:send-o" {...props}></Icon>
