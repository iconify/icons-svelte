<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndbkslbvb.css';
import '../../css/c/cdd4wcvmi.css';
import '../../css/e/eodm2abwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ndbkslbvb"/><path class="cdd4wcvmi"/><path class="eodm2abwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sonobarr" {...props}></Icon>
