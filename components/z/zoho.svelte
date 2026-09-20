<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mumbkij2k.css';
import '../../css/e/e5heefbvr.css';
import '../../css/t/txh2c660v.css';
import '../../css/k/ksqm5cilc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":366};
const content = `<path class="mumbkij2k"/><path class="e5heefbvr"/><path class="txh2c660v"/><path class="ksqm5cilc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:zoho" {...props}></Icon>
