<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzwxxyb8c.css';
import '../../css/k/kvxncwbco.css';
import '../../css/w/wbql4k8nx.css';
import '../../css/h/hvjzb1bja.css';
import '../../css/i/i2ypxfb0a.css';
import '../../css/l/l7-a0ebqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<circle class="pzwxxyb8c"/><circle class="kvxncwbco"/><circle class="wbql4k8nx"/><circle class="hvjzb1bja"/><path class="i2ypxfb0a"/><circle class="l7-a0ebqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="geo:turf-explode" {...props}></Icon>
