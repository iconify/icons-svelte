<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agoujac2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="agoujac2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:space-bar" {...props}></Icon>
