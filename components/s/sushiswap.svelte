<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/c/cxmk01b3w.css';
import '../../css/y/yokpzofkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="cxmk01b3w"/><path class="yokpzofkd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:sushiswap" {...props}></Icon>
