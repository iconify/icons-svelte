<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/d/d7m39n8ut.css';
import '../../css/u/ur70ribyv.css';
import '../../css/q/q1x80pbnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="d7m39n8ut"/><path class="ur70ribyv"/><path class="q1x80pbnz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:rss" {...props}></Icon>
