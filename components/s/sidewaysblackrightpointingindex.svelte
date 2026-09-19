<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gev-dachs.css';
import '../../css/u/unw373bpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gev-dachs"/><path class="unw373bpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:sidewaysblackrightpointingindex" {...props}></Icon>
