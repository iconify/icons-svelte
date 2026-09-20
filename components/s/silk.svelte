<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/w/wvvun6bpf.css';
import '../../css/g/gvgpw_b_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="wvvun6bpf"/><path class="gvgpw_b_r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:silk" {...props}></Icon>
