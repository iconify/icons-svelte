<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pos2pcbxf.css';
import '../../css/s/syd5dvn_a.css';
import '../../css/o/o6ib3twus.css';
import '../../css/e/ezlh-7cze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pos2pcbxf"/><path class="syd5dvn_a"/><path class="o6ib3twus"/><path class="ezlh-7cze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:shootingstar" {...props}></Icon>
