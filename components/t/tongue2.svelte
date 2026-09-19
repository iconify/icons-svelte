<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ks14vpbmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ks14vpbmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:tongue2" {...props}></Icon>
