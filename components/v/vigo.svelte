<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzlgly3ke.css';
import '../../css/q/qrhmcj17p.css';
import '../../css/i/i-dn492le.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="zzlgly3ke"><path class="qrhmcj17p"/><path class="i-dn492le"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:vigo" {...props}></Icon>
