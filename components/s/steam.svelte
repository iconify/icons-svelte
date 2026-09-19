<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmi3i5bvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="pmi3i5bvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:steam" {...props}></Icon>
