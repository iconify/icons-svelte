<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/h/hspj41b0o.css';
import '../../css/t/t-yrq7j-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="hspj41b0o"/><path class="t-yrq7j-h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:token" {...props}></Icon>
