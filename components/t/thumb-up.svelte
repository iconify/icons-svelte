<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/th2m307zq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="th2m307zq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:thumb-up" {...props}></Icon>
