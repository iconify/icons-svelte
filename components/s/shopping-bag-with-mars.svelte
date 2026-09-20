<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_aasy7_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="g_aasy7_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:shopping-bag-with-mars" {...props}></Icon>
