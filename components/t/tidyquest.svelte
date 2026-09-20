<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5twlibpq.css';
import '../../css/d/dkab58b3o.css';
import '../../css/z/zn725acau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x5twlibpq"/><path class="dkab58b3o"/><path class="zn725acau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tidyquest" {...props}></Icon>
