<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brnnimy3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="brnnimy3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:ungroup" {...props}></Icon>
