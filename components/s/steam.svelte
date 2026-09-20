<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ab6fy1brh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ab6fy1brh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:steam" {...props}></Icon>
