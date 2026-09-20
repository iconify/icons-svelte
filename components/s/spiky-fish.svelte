<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxk-8hbut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bxk-8hbut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:spiky-fish" {...props}></Icon>
