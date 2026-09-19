<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdfuk_71m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="sdfuk_71m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:tent-arrow-down-to-line" {...props}></Icon>
