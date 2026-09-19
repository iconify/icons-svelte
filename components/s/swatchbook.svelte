<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6tw3_chu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="a6tw3_chu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:swatchbook" {...props}></Icon>
