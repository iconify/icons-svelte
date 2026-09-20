<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pyh13cczf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pyh13cczf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:uv" {...props}></Icon>
