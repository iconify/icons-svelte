<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kih7mtb9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kih7mtb9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:smoke-slash" {...props}></Icon>
