<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/br_g0_8yr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="br_g0_8yr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:venus-with-mars" {...props}></Icon>
