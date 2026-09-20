<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc_mx6bxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":201,"height":170};
const content = `<path class="bc_mx6bxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:turso-light" {...props}></Icon>
