<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-2mb00dr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="u-2mb00dr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:windows8" {...props}></Icon>
