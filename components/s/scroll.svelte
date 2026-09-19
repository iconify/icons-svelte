<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xp9_gjv4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="xp9_gjv4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:scroll" {...props}></Icon>
