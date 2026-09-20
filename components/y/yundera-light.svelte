<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmm4mibxx.css';
import '../../css/i/i2a_ir9nf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xmm4mibxx"/><path class="i2a_ir9nf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:yundera-light" {...props}></Icon>
