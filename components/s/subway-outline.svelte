<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cz7o87b4w.css';
import '../../css/h/h0x9monpf.css';
import '../../css/v/vdzmghiwr.css';
import '../../css/h/hav3w3rni.css';
import '../../css/k/kz91gbcdp.css';
import '../../css/z/zir5ym1tm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<rect class="cz7o87b4w"/><path class="h0x9monpf"/><rect class="vdzmghiwr"/><circle class="hav3w3rni"/><circle class="kz91gbcdp"/><path class="zir5ym1tm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:subway-outline" {...props}></Icon>
