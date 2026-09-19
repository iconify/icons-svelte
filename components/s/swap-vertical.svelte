<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkghmxvee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gkghmxvee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:swap-vertical" {...props}></Icon>
