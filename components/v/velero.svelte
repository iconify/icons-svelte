<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/msn8vpxnr.css';
import '../../css/o/oj8vp5bxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="msn8vpxnr"/><path class="oj8vp5bxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:velero" {...props}></Icon>
