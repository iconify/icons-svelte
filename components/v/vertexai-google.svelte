<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/g/giyy8bcal.css';
import '../../css/b/bjf-fl4_c.css';
import '../../css/s/snglt3lmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="n1lsf0bnc"><path class="giyy8bcal"/><path clip-rule="evenodd" class="bjf-fl4_c"/><path class="snglt3lmz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:vertexai-google" {...props}></Icon>
