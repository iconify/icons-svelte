<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4minvbuf.css';
import '../../css/i/i6s53x8dt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x4minvbuf"/><path class="i6s53x8dt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:zabbix" {...props}></Icon>
