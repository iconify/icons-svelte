<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfpjty8ao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1920,"height":1792};
const content = `<path class="bfpjty8ao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:users" {...props}></Icon>
