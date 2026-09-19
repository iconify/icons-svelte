<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1rwt2vuq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p1rwt2vuq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:wine-bottle" {...props}></Icon>
