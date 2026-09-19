<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/um1cdwptq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="um1cdwptq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:wheat-awn-circle-exclamation" {...props}></Icon>
