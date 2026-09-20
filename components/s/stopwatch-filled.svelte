<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qescwxe_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="qescwxe_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:stopwatch-filled" {...props}></Icon>
