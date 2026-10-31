<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/b/bq46uowvk.css';
import '../../css/f/f5zdz58kw.css';
import '../../css/y/yx6qcnh6h.css';
import '../../css/w/wq8zqtbdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="bq46uowvk wm-shadow"/><path class="f5zdz58kw wm-shadow"/><path class="yx6qcnh6h"/><path class="wq8zqtbdl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:text-cursor" {...props}></Icon>
