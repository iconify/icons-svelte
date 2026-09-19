<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9khp6ncv.css';
import '../../css/m/m6xypubal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y9khp6ncv"/><path class="m6xypubal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:window-restore" {...props}></Icon>
