<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2kvgvbvc.css';
import '../../css/g/g_mfudb8u.css';
import '../../css/a/av7g1gbmu.css';
import '../../css/n/n8137bc8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="g_mfudb8u"/><path class="av7g1gbmu"/><path class="n8137bc8k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:wheat" {...props}></Icon>
