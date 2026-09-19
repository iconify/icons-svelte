<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tz2cl-9kh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="tz2cl-9kh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:table-cells-row-lock" {...props}></Icon>
