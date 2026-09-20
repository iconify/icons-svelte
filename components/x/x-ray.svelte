<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrvqps0xa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lrvqps0xa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:x-ray" {...props}></Icon>
