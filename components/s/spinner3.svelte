<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_eesoi_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="n_eesoi_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:spinner3" {...props}></Icon>
