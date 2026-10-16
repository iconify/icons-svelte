<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2p6qtmid.css';
import '../../css/e/ek7btvb6t.css';
import '../../css/n/nzts02p0o.css';
import '../../css/x/xpvdyjr2m.css';
import '../../css/n/nkaouib7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p2p6qtmid"/><path class="ek7btvb6t"/><path class="nzts02p0o"/><path class="xpvdyjr2m"/><path class="nkaouib7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:trash-restore-20" {...props}></Icon>
