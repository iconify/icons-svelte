<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5-9u1vgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="m5-9u1vgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:scale-balanced" {...props}></Icon>
