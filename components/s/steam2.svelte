<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j49_occ8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j49_occ8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:steam2" {...props}></Icon>
