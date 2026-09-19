<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2206fj4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":304,"height":384};
const content = `<path class="t2206fj4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:text-format" {...props}></Icon>
