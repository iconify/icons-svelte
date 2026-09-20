<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gio_f0h-w.css';
import '../../css/u/uany1gj4x.css';
import '../../css/m/mxdeg7sta.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/o/oxy7tjn5z.css';
import '../../css/a/asn11xnnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="gio_f0h-w"/><path class="uany1gj4x"/><path class="mxdeg7sta"/><g class="jn8qy4bru"><path class="oxy7tjn5z"/><path class="asn11xnnf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:running-shirt" {...props}></Icon>
