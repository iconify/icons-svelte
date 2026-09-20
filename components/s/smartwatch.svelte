<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0z0rdxri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="y0z0rdxri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:smartwatch" {...props}></Icon>
