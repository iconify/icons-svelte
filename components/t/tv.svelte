<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lm5q7xb3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="lm5q7xb3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:tv" {...props}></Icon>
