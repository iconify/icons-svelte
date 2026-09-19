<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjz_80bly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pjz_80bly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:user" {...props}></Icon>
