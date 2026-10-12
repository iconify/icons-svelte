<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mj8m3lbzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mj8m3lbzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:underline-20" {...props}></Icon>
