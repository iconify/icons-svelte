<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsgpay9lb.css';
import '../../css/n/ntveefwhq.css';
import '../../css/h/huuajhmrh.css';
import '../../css/c/cd7zj2mlo.css';
import '../../css/p/plt0nhugm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="jsgpay9lb"/><path class="ntveefwhq"/><circle class="huuajhmrh"/><path class="cd7zj2mlo"/><path class="plt0nhugm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:smiling-face-with-horns" {...props}></Icon>
