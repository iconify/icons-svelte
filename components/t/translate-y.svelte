<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpnll0i1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="zpnll0i1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:translate-y" {...props}></Icon>
