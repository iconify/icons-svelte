<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv9qcacyl.css';
import '../../css/q/qy5hs86sc.css';
import '../../css/n/n7wgw62ui.css';
import '../../css/l/lojv2fbzf.css';
import '../../css/t/tvmjk0b5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":480};
const content = `<g class="nv9qcacyl"><path class="qy5hs86sc"/><path class="n7wgw62ui"/><path class="lojv2fbzf"/></g><path class="tvmjk0b5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:sn-4x3" {...props}></Icon>
