<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghnb59b3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="ghnb59b3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:yield-sign-bold" {...props}></Icon>
