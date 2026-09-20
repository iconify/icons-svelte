<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2v3_yp0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="p2v3_yp0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:volume-down" {...props}></Icon>
