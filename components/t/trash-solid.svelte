<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bva1ywnrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bva1ywnrc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:trash-solid" {...props}></Icon>
