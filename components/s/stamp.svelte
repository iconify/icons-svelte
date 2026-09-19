<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pn37jeqpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pn37jeqpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:stamp" {...props}></Icon>
