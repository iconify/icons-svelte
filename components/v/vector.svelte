<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xt6er0bdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xt6er0bdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:vector" {...props}></Icon>
