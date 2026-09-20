<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/os0n-o3_g.css';
import '../../css/a/amn_b-_3e.css';
import '../../css/l/l4css97ah.css';
import '../../css/x/xmpcpabmy.css';
import '../../css/h/hehegibhq.css';
import '../../css/q/qrwhk6b5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<ellipse class="os0n-o3_g"/><path class="amn_b-_3e"/><path class="l4css97ah"/><path class="xmpcpabmy"/><path class="hehegibhq"/><path class="qrwhk6b5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:woman-light-skin-tone-bald" {...props}></Icon>
