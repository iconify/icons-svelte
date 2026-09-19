<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oaqxgfbxx.css';
import '../../css/s/sb3_ircqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oaqxgfbxx"/><path class="sb3_ircqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:save" {...props}></Icon>
