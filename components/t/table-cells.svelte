<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uj_gb8-5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uj_gb8-5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:table-cells" {...props}></Icon>
