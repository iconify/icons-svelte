<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xb731ubzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="xb731ubzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:yield-sign-duo" {...props}></Icon>
