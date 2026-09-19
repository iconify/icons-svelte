<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mo6hfzsfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="mo6hfzsfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:toggle-left" {...props}></Icon>
