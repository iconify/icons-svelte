<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgjxk0u1q.css';
import '../../css/a/auqkg35_k.css';
import '../../css/h/hw4iexbpi.css';
import '../../css/x/xdn4qlb1g.css';
import '../../css/t/tghi_kbxe.css';
import '../../css/a/amfqz6wme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<circle class="jgjxk0u1q"/><circle class="auqkg35_k"/><circle class="hw4iexbpi"/><circle class="xdn4qlb1g"/><circle class="tghi_kbxe"/><path class="amfqz6wme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="geo:turf-triangle-grid" {...props}></Icon>
