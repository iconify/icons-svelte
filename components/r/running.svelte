<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twg3zq-7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="twg3zq-7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:running" {...props}></Icon>
