<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtzmx5fad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mtzmx5fad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:tour-van" {...props}></Icon>
