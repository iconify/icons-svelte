<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/n/nxjbdabzh.css';
import '../../css/v/vezblbb5g.css';
import '../../css/a/ajone6a4x.css';
import '../../css/q/qsgo5rxvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="nxjbdabzh wm-shadow"/><path class="vezblbb5g wm-shadow"/><path class="ajone6a4x"/><path class="qsgo5rxvw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:sticky-note" {...props}></Icon>
