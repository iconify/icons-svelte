<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tyl1b_bqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tyl1b_bqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:signal-cellular-4" {...props}></Icon>
