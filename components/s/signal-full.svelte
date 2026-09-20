<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_p7_xt8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="w_p7_xt8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:signal-full" {...props}></Icon>
