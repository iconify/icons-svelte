<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/veir1qbiz.css';
import '../../css/a/a5u582bgm.css';
import '../../css/g/gy7khnb4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="veir1qbiz"/><circle class="a5u582bgm"/><path class="gy7khnb4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:swimming" {...props}></Icon>
