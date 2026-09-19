<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mst3afbdz.css';
import '../../css/w/wa7hudb5j.css';
import '../../css/g/gl_1tcc4d.css';
import '../../css/o/oe1zm1b9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mst3afbdz"/><path class="wa7hudb5j"/><path class="gl_1tcc4d"/><path class="oe1zm1b9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:sy-1x1" {...props}></Icon>
