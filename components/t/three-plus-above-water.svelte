<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgb76abzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pgb76abzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:three-plus-above-water" {...props}></Icon>
