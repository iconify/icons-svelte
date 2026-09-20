<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lp2x7ac1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lp2x7ac1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:user-alt" {...props}></Icon>
