<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jf_3kpbwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="jf_3kpbwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:time-entry" {...props}></Icon>
