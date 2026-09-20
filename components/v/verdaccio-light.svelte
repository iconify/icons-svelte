<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ac-mt5boh.css';
import '../../css/v/vxr1g-bus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ac-mt5boh"/><path class="vxr1g-bus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:verdaccio-light" {...props}></Icon>
