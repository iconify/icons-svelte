<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vkiwvd2vg.css';
import '../../css/z/z99nws9nc.css';
import '../../css/h/hikk7hbhy.css';
import '../../css/y/yw_ha830o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="vkiwvd2vg"/><path clip-rule="evenodd" class="z99nws9nc"/><path class="hikk7hbhy"/><path clip-rule="evenodd" class="yw_ha830o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:smile-outline" {...props}></Icon>
