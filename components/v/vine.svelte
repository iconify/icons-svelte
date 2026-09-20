<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iq13j2e4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="iq13j2e4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:vine" {...props}></Icon>
