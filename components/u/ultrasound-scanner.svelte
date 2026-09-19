<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/i/ifh0c7aot.css';
import '../../css/k/kqavqurtm.css';
import '../../css/v/vmwtyhbng.css';
import '../../css/f/fj8vt2b8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="ifh0c7aot"/><path class="kqavqurtm"/><path class="vmwtyhbng"/><path class="fj8vt2b8g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:ultrasound-scanner" {...props}></Icon>
