<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/q/qc-apv10r.css';
import '../../css/n/n4byf3-kh.css';
import '../../css/s/spbi7bcof.css';
import '../../css/t/tdapwmbfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="qc-apv10r"/><path class="n4byf3-kh"/><path class="spbi7bcof"/><path class="tdapwmbfy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:seedling" {...props}></Icon>
