<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pld9fvbkz.css';
import '../../css/u/uvhrn1bbw.css';
import '../../css/n/nfquxfbmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pld9fvbkz"/><path class="uvhrn1bbw"/><path class="nfquxfbmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:squaredid" {...props}></Icon>
