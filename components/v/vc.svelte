<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/t/tq71b84bu.css';
import '../../css/j/jr20aub9c.css';
import '../../css/m/m5ixigb2w.css';
import '../../css/x/xuu65oubr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="tq71b84bu"/><path class="jr20aub9c"/><path class="m5ixigb2w"/><path class="xuu65oubr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flagpack:vc" {...props}></Icon>
