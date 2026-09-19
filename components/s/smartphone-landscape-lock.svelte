<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvw-7lb3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":384};
const content = `<path class="rvw-7lb3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:smartphone-landscape-lock" {...props}></Icon>
