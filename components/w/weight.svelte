<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_sdc6b1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="k_sdc6b1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:weight" {...props}></Icon>
