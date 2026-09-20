<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-hyh_bud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="z-hyh_bud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:water-glass" {...props}></Icon>
