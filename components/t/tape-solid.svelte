<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/ql119pv2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ql119pv2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:tape-solid" {...props}></Icon>
