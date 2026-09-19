<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5-kcyezf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="g5-kcyezf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:spinner9" {...props}></Icon>
